# Talks
Repository of slides from various talks that I’ve given

# Type-Safe Datatype-Generic Programming in F#
18/09/2019 | F#unctional Londoners Meetup Group<br>
Video: https://skillsmatter.com/skillscasts/14430-f-sharpunctional-londoners-september<br>
Slides: https://github.com/nickcowle/Talks/blob/master/Type-Safe%20Datatype-Generic%20Programming%20in%20F%23.pdf

Datatype-generic programming is a powerful technique that allows you to parameterise your functions by the shape of the types that they are invoked with. A simple example of datatype-generic programming is a pretty-printer for arbitrary record types – it inspects the structure of the record type at runtime to find its fields and then prints the value of each field in turn.

In .NET languages, datatype-generic programming is typically achieved through a combination of generic type parameters and reflection, but this method suffers from the proliferation of obj values and therefore unsafe code.

In this talk, we’ll take a look at three libraries:
* TypeEquality - https://github.com/G-Research/TypeEquality
* HCollections - https://github.com/nickcowle/HCollections
* TeqCrate - https://github.com/nickcowle/TeqCrate

We’ll show that when taken together, these libraries offer a type-safe abstraction layer over simple reflection. By using them, we can create our own libraries that are not only type-safe with respect to their public API, but whose internal implementations are completely type-safe as well.

# Initial Algebras for the uninitiated
12/03/2019 | F#unctional Londoners Meetup Group<br>
Video: https://skillsmatter.com/skillscasts/13176-f-sharpunctional-londoners<br>
Slides: https://github.com/nickcowle/Talks/blob/master/Initial%20Algebras%20for%20the%20Uninitiated.pdf

The concept of the initial algebra, borrowed from Category Theory, is a simple but powerful one that allows you to completely separate the description and interpretation of your APIs. In this talk, we'll find out what exactly an initial algebra is, along with how to define and create your own initial algebras in F#. We'll cover some of the advantages and practical aspects of writing initial algebras and find out how they relate to similar concepts like the free monad.

# Lightning Talk: Existentials - Playing Hide and Seek With Your Types
05/04/2018 | F# eXchange 2018<br>
Video: https://skillsmatter.com/skillscasts/11633-lightning-talk-existentials-playing-hide-and-seek-with-your-types<br>
Slides: https://github.com/nickcowle/Talks/blob/master/Existentials%20-%20Playing%20Hide%20and%20Seek%20With%20Your%20Types.pdf

Like all good ideas in type theory, existential types have been around for a long time but are rarely used or given the prominence they deserve. Existential types offer a powerful mechanism for developers to create rich and completely type-safe data structures and APIs that are otherwise impossible to express.

In this lightening talk, Nick will share with you what existential types are, how it's possible to represent them in F# and give some practical examples of where you might find them useful.
