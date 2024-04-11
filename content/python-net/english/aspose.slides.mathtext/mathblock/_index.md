---
title: MathBlock
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/mathblock/
---


MathBlock class

Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line.
            All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.

**Inheritance:**[`MathBlock`](/slides/python-net/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)

The MathBlock type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#/) | Initializes a new instance of the MathBlock class. |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement/) | Creates a new mathematical block and puts specified element in it |
| [__init__](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#Iterable[IMathElement]/) |  |

## Properties

| Property | Description |
| :- | :- |
| [count](/slides/python-net/aspose.slides.mathtext/mathblock/count/) | Gets the number of child math elements actually contained in the collection.<br/>            Read-only <br/>.NET type System.Int32. |
| [is_read_only](/slides/python-net/aspose.slides.mathtext/mathblock/is_read_only/) | Returns false because child elements collection can be modified. |
| [as_i_math_element_collection](/slides/python-net/aspose.slides.mathtext/mathblock/as_i_math_element_collection/) |  |
| [as_i_math_element](/slides/python-net/aspose.slides.mathtext/mathblock/as_i_math_element/) |  |
| [as_i_enumerable](/slides/python-net/aspose.slides.mathtext/mathblock/as_i_enumerable/) |  |

## Indexer

| Name | Description |
| :- | :- |
| [index] |  |

## Methods

| Method | Description |
| :- | :- |
| [join](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement/) | Joins a mathematical element with this mathematical block |
| [join](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#string/) | Joins a mathematical text with this mathematical block |
| [divide](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement/) | Creates a fraction with this numerator and specified denominator |
| [divide](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#string/) | Creates a fraction with this numerator and specified denominator |
| [divide](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement-MathFractionTypes/) | Creates a fraction of the specified type with this numerator and specified denominator |
| [divide](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#string-MathFractionTypes/) | Creates a fraction of the specified type with this numerator and specified denominator |
| [enclose](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#char-char/) | Encloses child elements of this block in specified characters such as parenthesis or another characters as framing |
| [enclose](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#char-char-char/) | Encloses child elements of this block in specified characters such as parenthesis or another as framing<br/>            and delimit with a separator character |
| [enclose](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#/) | Encloses a math element in parenthesis |
| [function](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement/) | Takes a function of an argument using this instance as the function name |
| [function](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#string/) | Takes a function of an argument using this instance as the function name |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement/) | Takes specified function using this instance as the argument |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#string/) | Takes specified function using this instance as the argument |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#MathFunctionsOfOneArgument/) | Takes specified function using this instance as the argument |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#MathFunctionsOfTwoArguments-IMathElement/) | Takes specified function using this instance as the argument and specified additional argument |
| [as_argument_of_function](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#MathFunctionsOfTwoArguments-string/) | Takes specified function using this instance as the argument and specified additional argument |
| [set_subscript](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement/) | Creates subscript |
| [set_subscript](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#string/) | Creates subscript |
| [set_superscript](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement/) | Creates superscript |
| [set_superscript](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#string/) | Creates superscript |
| [set_sub_superscript_on_the_right](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement-IMathElement/) | Creates subscript and superscript on the right |
| [set_sub_superscript_on_the_right](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#string-string/) | Creates subscript and superscript on the right |
| [set_sub_superscript_on_the_left](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement-IMathElement/) | Creates subscript and superscript on the left |
| [set_sub_superscript_on_the_left](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#string-string/) | Creates subscript and superscript on the left |
| [radical](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement/) | Specifies the mathematical root of the given degree from the specified argument. |
| [radical](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#string/) | Specifies the mathematical root of the given degree from the specified argument. |
| [set_upper_limit](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement/) | Takes upper limit |
| [set_upper_limit](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#string/) | Takes upper limit |
| [set_lower_limit](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement/) | Takes lower limit |
| [set_lower_limit](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#string/) | Takes lower limit |
| [nary](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#MathNaryOperatorTypes-IMathElement-IMathElement/) | Creates a N-ary operator |
| [nary](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#MathNaryOperatorTypes-string-string/) | Creates a N-ary operator |
| [integral](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#MathIntegralTypes-IMathElement-IMathElement-MathLimitLocations/) | Takes the integral |
| [integral](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#MathIntegralTypes-IMathElement-IMathElement/) | Takes the integral |
| [integral](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#MathIntegralTypes/) | Takes the integral without limits |
| [integral](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#MathIntegralTypes-string-string-MathLimitLocations/) | Takes the integral |
| [integral](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#MathIntegralTypes-string-string/) | Takes the integral |
| [group](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#/) | Places this element in a group using a bottom curly bracket |
| [group](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#char-MathTopBotPositions-MathTopBotPositions/) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [to_border_box](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#/) | Places this element in a border-box |
| [to_border_box](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#bool-bool-bool-bool-bool-bool-bool-bool/) | Places this element in a border-box |
| [to_math_array](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#/) | Puts child elements in a vertical array |
| [accent](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#char/) | Sets an accent mark (a character on the top of this element) |
| [overbar](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#/) | Sets a bar on the top of this element |
| [underbar](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#/) | Sets a bar on the bottom of this element |
| [to_box](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#/) | Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [get_children](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#/) | Get children elements |
| [add](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement/) | Adds a math element to the end of the collection. |
| [clear](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#/) | Removes all elements from the collection. |
| [contains](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement/) | Determines whether the collection contains a specific value. |
| [copy_to](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#List[IMathElement]-int/) | Copy to specified array. |
| [remove](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement/) | Removes the first occurrence of a specific object from the collection. |
| [index_of](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathElement/) | Determines the index of a specific math element in collection. |
| [insert](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#int-IMathElement/) | Inserts a MathElement into the collection at the specified index. |
| [remove_at](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#int/) | Removes the element at the specified index of the collection. |
| [join_block](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#IMathBlock/) | Joins another mathematical block with this one |
| [delimit](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#char/) | Delimits child elements with separator character (without the brackets) |
| [write_as_math_ml](/slides/python-net/aspose.slides.mathtext/mathblock/mathblock/#System.IO.Stream/) | Saves content of this <br/>[`MathBlock`](/slides/python-net/aspose.slides.mathtext/mathblock) as MathML |

