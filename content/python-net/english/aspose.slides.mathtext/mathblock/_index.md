---
title: MathBlock class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/
---


## MathBlock class

Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line.
            All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.

**Inheritance:**[`MathBlock`](/slides/python-net/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)

The MathBlock type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#) | Initializes a new instance of the MathBlock class. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement) | Creates a new mathematical block and puts specified element in it |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#Iterable[IMathElement]) |  |

## Properties

| Property | Description |
| :- | :- |
| [count](/slides/python-net/aspose.slides.mathtext/count) | Gets the number of child math elements actually contained in the collection.<br/>            Read-only :py:class:`int`. |
| [is_read_only](/slides/python-net/aspose.slides.mathtext/is_read_only) | Returns false because child elements collection can be modified. |
| [as_i_math_element_collection](/slides/python-net/aspose.slides.mathtext/as_i_math_element_collection) |  |
| [as_i_math_element](/slides/python-net/aspose.slides.mathtext/as_i_math_element) |  |
| [as_i_enumerable](/slides/python-net/aspose.slides.mathtext/as_i_enumerable) |  |

## Indexer

| Name | Description |
| :- | :- |
| [index] |  |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement) | Joins a mathematical element with this mathematical block |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#string) | Joins a mathematical text with this mathematical block |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement) | Creates a fraction with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#string) | Creates a fraction with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement-MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#string-MathFractionTypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#char-char) | Encloses child elements of this block in specified characters such as parenthesis or another characters as framing |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#char-char-char) | Encloses child elements of this block in specified characters such as parenthesis or another as framing<br/>            and delimit with a separator character |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#) | Encloses a math element in parenthesis |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement) | Takes a function of an argument using this instance as the function name |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#string) | Takes a function of an argument using this instance as the function name |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement) | Takes specified function using this instance as the argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#string) | Takes specified function using this instance as the argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#MathFunctionsOfOneArgument) | Takes specified function using this instance as the argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#MathFunctionsOfTwoArguments-IMathElement) | Takes specified function using this instance as the argument and specified additional argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#MathFunctionsOfTwoArguments-string) | Takes specified function using this instance as the argument and specified additional argument |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement) | Creates subscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#string) | Creates subscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement) | Creates superscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#string) | Creates superscript |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement-IMathElement) | Creates subscript and superscript on the right |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#string-string) | Creates subscript and superscript on the right |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement-IMathElement) | Creates subscript and superscript on the left |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#string-string) | Creates subscript and superscript on the left |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement) | Specifies the mathematical root of the given degree from the specified argument. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#string) | Specifies the mathematical root of the given degree from the specified argument. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement) | Takes upper limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#string) | Takes upper limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement) | Takes lower limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#string) | Takes lower limit |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#MathNaryOperatorTypes-IMathElement-IMathElement) | Creates a N-ary operator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#MathNaryOperatorTypes-string-string) | Creates a N-ary operator |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#MathIntegralTypes-IMathElement-IMathElement-MathLimitLocations) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#MathIntegralTypes-IMathElement-IMathElement) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#MathIntegralTypes) | Takes the integral without limits |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#MathIntegralTypes-string-string-MathLimitLocations) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#MathIntegralTypes-string-string) | Takes the integral |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#) | Places this element in a group using a bottom curly bracket |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#char-MathTopBotPositions-MathTopBotPositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#) | Places this element in a border-box |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#bool-bool-bool-bool-bool-bool-bool-bool) | Places this element in a border-box |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#) | Puts child elements in a vertical array |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#char) | Sets an accent mark (a character on the top of this element) |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#) | Sets a bar on the top of this element |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#) | Sets a bar on the bottom of this element |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#) | Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#) | Get children elements |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement) | Adds a math element to the end of the collection. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#) | Removes all elements from the collection. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement) | Determines whether the collection contains a specific value. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#List[IMathElement]-int) | Copy to specified array. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement) | Removes the first occurrence of a specific object from the collection. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathElement) | Determines the index of a specific math element in collection. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#int-IMathElement) | Inserts a MathElement into the collection at the specified index. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#int) | Removes the element at the specified index of the collection. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#IMathBlock) | Joins another mathematical block with this one |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#char) | Delimits child elements with separator character (without the brackets) |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/#System.IO.Stream) | Saves content of this :py:class:`aspose.slides.mathtext.MathBlock` as MathML |

