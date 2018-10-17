---
title: SPLS Oct '18
layout: default
uni: University of Strathclyde
day: 17th
month: October
year: 2018
about: About SPLS
time: Time and place
prog: Programme
abst: Abstracts
reg: Registration
---

# Scottish Programming Languages Seminar (SPLS)

## {{ page.uni }}, {{ page.day }} {{ page.month }} {{ page.year }}

Location: Royal College building

Talks: Room 641

Food/coffee: Room 513


The rooms are signposted from the main George Street entrance, and Montrose
Street (James Weir building) entrance.

## About SPLS

The [Scottish Programming Languages Seminar](http://www.dcs.gla.ac.uk/research/spls/)
is an informal meeting for the discussion of any aspect of programming languages.
The next SPLS will take place on Wednesday {{ page.day }} {{ page.month }} at the
{{ page.uni }}.

Information and updates about the {{ page.month }} edition of SPLS will be sent
via the [SPLS Mailing List](https://mr1.dcs.gla.ac.uk/mailman/listinfo/spls).


## Time and place

12:00--17:45, {{ page.day }} {{ page.month }}, {{ page.uni }}. Royal
College building, Room 641.


## Registration

Please add your name to the
[Doodle poll](https://doodle.com/poll/dfufkg7y6qb6psvp) to
register. Any dietary requirements should be made as a comment on the
doodle poll!


## Programme

|When   | What |
|-------|-----------------|
| 12.00 | Lunch (provided) |
| 13.00 | Context Constrained Computation - James Wood |
| 13.30 | Type-Driven Development of SoC Architectures - Jan de Muijnck-Hughes |
| 14.00 | Coffee |
| 14.30 | Industry experience of implementing 80+ DSLs on top of Xtext - Gregory Dyke |
| 15.00 | Notebook Programming Considered Harmful - Jeremy Singer |
| 15.30 | Where the linear lambdas go - Wen Kokke |
| 16.00 | Coffee |
| 16.30 | Generating Efficient Parallel Code for Irregular Shaped Arrays - Federico Pizzuti |
| 17.00 | Announcements? |
| 17.15 | Pub |


## Abstracts

#### Context Constrained Computation - James Wood

In normal typed λ-calculi, variables may be used multiple times, in
multiple contexts, for multiple reasons, as long as the types
agree. The disciplines of linear types and coeffects refine this by
tracking how variables are used. For instance, we might track how many
times a variable is used, or whether it is used covariantly,
contravariantly, or invariantly. Such a discipline yields a general
framework of “context constrained computing”, where constraints on
variables in the context tell us something interesting about the
computation being performed. We will present work in progress on
capturing the “intensional” properties of programs via a family of
Kripke indexed relational semantics that refines a simple
set-theoretic semantics of programs. The value of our approach lies in
its generality and the range of examples covered.

#### Type-Driven Development of SoC Architectures - Jan de Muijnck-Hughes

The protocols that describe the interactions between IP Cores on
System-on-a-Chip (SoC) architectures are well-documented, describing
not only the structural properties of the physical interfaces but also
the behaviour of the emanating signals.  However, there is a
disconnect between the design of SoC architectures, their formal
description, and the verification of their implementation in known
hardware description languages. In this talk I will discuss my work in
designing a modelling language with a substructural type-system that
reasons about the structure of SoC Architectures.

#### Industry experience of implementing 80+ DSLs on top of Xtext - Gregory Dyke

Avaloq is an international leading Fintech company and the creator of
the Avaloq Banking Suite. Domain Specific Languages (DSLs) are used to
customize the business logic of the banking suite. Xtext is an Eclipse
project that provides rich support for the implementation of
DSLs. Xtext is very flexible and easily extensible allowing to apply
it way beyond simple flowchart DSLs. At Avaloq we used Xtext to
implement tools for over 80 DSLs out of which over 50 languages
existed long before we learned about Xtext and hence were designed
without Xtext implementation in mind. In this talk we introduce DSL
Developer Kit, a family of DSLs built on top of Xtext to help with
heavy customization of parsing, indexing, scoping, validation, and
formatting.

#### Notebook Programming Considered Harmful - Jeremy Singer

Millennials write their code in Jupyter Notebooks (formerly known as
IPython). Highly evangelized benefits include (1) familiar
browser-based coding environment, (2) interactive feedback, (3) inline
tutorial commentary and code blocks, and (4) tight integration with
popular libraries e.g. NumPy, matplotlib. Many coders, particularly in
the data science domain, use Jupyter as their development platform of
choice. At Glasgow, we have switched our first year undergraduate
coding labs to Jupyter. _However_ Jupyter is not always a bringer of
jollity. The notebook abstraction has several serious problems, which
expose themselves (at best) as inconveniences to experienced hackers
or (at worst) as conceptual misdirections to novice developers. In
this talk, I will highlight some of these problems and propose
potential fixups.

#### Where the linear lambdas go - Wen Kokke

Have you ever wondered where the lambdas live, and if you could just
grab a random few to see if your compiler works, only to realise
"WHOA, that's kinda hard!" Turns out that linear lambdas live in an
even more elusive land, where none of the existing solutions – as far
as I know – really apply. A common problem with support for those
pesky linear types, really. This talk will drag you though some rather
naive solutions, some existing work, and then end rather abruptly with
a cry for help. Spoilers.

#### Generating Efficient Parallel Code for Irregular Shaped Arrays - Federico Pizzuti

Data types in high-level programming languages capture semantic
information about the program. Compilers for languages such as
Accelerate, Futhark, Delite or Lift have shown how to exploit this
information to produce high-performance code. While these approaches
have the ability to handle multi-dimensional arrays, their type
systems are currently limited to nested arrays of rectangular
shapes. This talk presents our work on lifting some of these
limitations and enable the representation of irregular, yet statically
known shaped, multi-dimensional arrays at the type level. This will
enable the Lift compiler to generate efficient code for applications
operating on irregular-shaped structure, such as matrix-triangle
multiplication or operations on compact representations of tree-like
data structures. In particular, the type system is extended by
allowing the array element type to depend, in a restricted way, on its
position in the enclosing array. We show how existing high-level
patterns together with a couple new primitives naturally express
computations on such data structures. Finally, we show how classical
low-level loop optimisations can be expressed in terms of operations
on such irregular arrays, highlighting their utility even in
applications that are expressible using more traditional methods.



#### Cancelled Talk - Folds, Unfolds, and Metaheuristics - Adam Barwell

Metaheuristics are families of algorithms that describe how to achieve
acceptable solutions for hard optimisation problems. Current
approaches to the design, development, and transformation of
metaheuristic algorithms are predominantly ad hoc. In this talk, we
present work in progress on a constructive approach to the definition
of metaheuristic algorithms that supports mechanical reasoning about
well-known algorithms from metaheuristics literature. This facilitates
a type-driven rewriting system that is able to synthesise known
metaheuristic algorithms. Using our approach, we intend for it to be
possible to determine whether two algorithms are equivalent in terms
of their results, and to choose an algorithm from a set of equivalent
algorithms for a given problem, based on a given cost model, or the
overall fitness of results. We conjecture that it is also possible to
generate new metaheuristic algorithms using our approach.

## Organizers

* [Stuart Gale](http://bishboria.com), {{ page.uni }}


## Acknowledgements

This meeting of SPLS will receive financial support from the
[Theory, Modelling and Computation theme](http://www.sicsa.ac.uk/research/theory-modelling-computation/)
of the [Scottish Informatics and Computer Science Alliance](http://www.sicsa.ac.uk/).

![SICSA logo](sicsa_blue.jpg "SICSA logo")
