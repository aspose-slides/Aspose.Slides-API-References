---
title: MathBlock class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/mathblock/
---


## MathBlock class

Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line.
            All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.

**Inheritance:**[`MathBlock`](/slides/python-net/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)

The MathBlock type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides.mathtext/mathblock/__init__/#) | Initializes a new instance of the MathBlock class. |
| [`__init__`](/slides/python-net/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Creates a new mathematical block and puts specified element in it |
| [`__init__`](/slides/python-net/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Properties

| Property | Description |
| :- | :- |
| [`count`](/slides/python-net/aspose.slides.mathtext/mathblock/count/) | Gets the number of child math elements actually contained in the collection.<br/>            Read-only **int**. |
| [`is_read_only`](/slides/python-net/aspose.slides.mathtext/mathblock/is_read_only/) | Returns false because child elements collection can be modified. |
| [`as_i_math_element_collection`](/slides/python-net/aspose.slides.mathtext/mathblock/as_i_math_element_collection/) |  |
| [`as_i_math_element`](/slides/python-net/aspose.slides.mathtext/mathblock/as_i_math_element/) |  |
| [`as_i_enumerable`](/slides/python-net/aspose.slides.mathtext/mathblock/as_i_enumerable/) |  |

## Indexer

| Name | Description |
| :- | :- |
| [index] |  |

## Methods

| Method | Description |
| :- | :- |
| [`join`](/slides/python-net/aspose.slides.mathtext/mathblock/join/#imathelement) | Joins a mathematical element with this mathematical block |
| [`join`](/slides/python-net/aspose.slides.mathtext/mathblock/join/#str) | Joins a mathematical text with this mathematical block |
| [`divide`](/slides/python-net/aspose.slides.mathtext/mathblock/divide/#imathelement) | Creates a fraction with this numerator and specified denominator |
| [`divide`](/slides/python-net/aspose.slides.mathtext/mathblock/divide/#str) | Creates a fraction with this numerator and specified denominator |
| [`divide`](/slides/python-net/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [`divide`](/slides/python-net/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [`enclose`](/slides/python-net/aspose.slides.mathtext/mathblock/enclose/#char-char) | Encloses child elements of this block in specified characters such as parenthesis or another characters as framing |
| [`enclose`](/slides/python-net/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | Encloses child elements of this block in specified characters such as parenthesis or another as framing<br/>            and delimit with a separator character |
| [`enclose`](/slides/python-net/aspose.slides.mathtext/mathblock/enclose/#) | Encloses a math element in parenthesis |
| [`function`](/slides/python-net/aspose.slides.mathtext/mathblock/function/#imathelement) | Takes a function of an argument using this instance as the function name |
| [`function`](/slides/python-net/aspose.slides.mathtext/mathblock/function/#str) | Takes a function of an argument using this instance as the function name |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Takes specified function using this instance as the argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Takes specified function using this instance as the argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Takes specified function using this instance as the argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Takes specified function using this instance as the argument and specified additional argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Takes specified function using this instance as the argument and specified additional argument |
| [`set_subscript`](/slides/python-net/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Creates subscript |
| [`set_subscript`](/slides/python-net/aspose.slides.mathtext/mathblock/set_subscript/#str) | Creates subscript |
| [`set_superscript`](/slides/python-net/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Creates superscript |
| [`set_superscript`](/slides/python-net/aspose.slides.mathtext/mathblock/set_superscript/#str) | Creates superscript |
| [`set_sub_superscript_on_the_right`](/slides/python-net/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Creates subscript and superscript on the right |
| [`set_sub_superscript_on_the_right`](/slides/python-net/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Creates subscript and superscript on the right |
| [`set_sub_superscript_on_the_left`](/slides/python-net/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Creates subscript and superscript on the left |
| [`set_sub_superscript_on_the_left`](/slides/python-net/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Creates subscript and superscript on the left |
| [`radical`](/slides/python-net/aspose.slides.mathtext/mathblock/radical/#imathelement) | Specifies the mathematical root of the given degree from the specified argument. |
| [`radical`](/slides/python-net/aspose.slides.mathtext/mathblock/radical/#str) | Specifies the mathematical root of the given degree from the specified argument. |
| [`set_upper_limit`](/slides/python-net/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Takes upper limit |
| [`set_upper_limit`](/slides/python-net/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Takes upper limit |
| [`set_lower_limit`](/slides/python-net/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Takes lower limit |
| [`set_lower_limit`](/slides/python-net/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Takes lower limit |
| [`nary`](/slides/python-net/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Creates a N-ary operator |
| [`nary`](/slides/python-net/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Creates a N-ary operator |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Takes the integral |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Takes the integral |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Takes the integral without limits |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Takes the integral |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Takes the integral |
| [`group`](/slides/python-net/aspose.slides.mathtext/mathblock/group/#) | Places this element in a group using a bottom curly bracket |
| [`group`](/slides/python-net/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [`to_border_box`](/slides/python-net/aspose.slides.mathtext/mathblock/to_border_box/#) | Places this element in a border-box |
| [`to_border_box`](/slides/python-net/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Places this element in a border-box |
| [`to_math_array`](/slides/python-net/aspose.slides.mathtext/mathblock/to_math_array/#) | Puts child elements in a vertical array |
| [`accent`](/slides/python-net/aspose.slides.mathtext/mathblock/accent/#char) | Sets an accent mark (a character on the top of this element) |
| [`overbar`](/slides/python-net/aspose.slides.mathtext/mathblock/overbar/#) | Sets a bar on the top of this element |
| [`underbar`](/slides/python-net/aspose.slides.mathtext/mathblock/underbar/#) | Sets a bar on the bottom of this element |
| [`to_box`](/slides/python-net/aspose.slides.mathtext/mathblock/to_box/#) | Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [`get_children`](/slides/python-net/aspose.slides.mathtext/mathblock/get_children/#) | Get children elements |
| [`add`](/slides/python-net/aspose.slides.mathtext/mathblock/add/#imathelement) | Adds a math element to the end of the collection. |
| [`clear`](/slides/python-net/aspose.slides.mathtext/mathblock/clear/#) | Removes all elements from the collection. |
| [`contains`](/slides/python-net/aspose.slides.mathtext/mathblock/contains/#imathelement) | Determines whether the collection contains a specific value. |
| [`copy_to`](/slides/python-net/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Copy to specified array. |
| [`remove`](/slides/python-net/aspose.slides.mathtext/mathblock/remove/#imathelement) | Removes the first occurrence of a specific object from the collection. |
| [`index_of`](/slides/python-net/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Determines the index of a specific math element in collection. |
| [`insert`](/slides/python-net/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Inserts a MathElement into the collection at the specified index. |
| [`remove_at`](/slides/python-net/aspose.slides.mathtext/mathblock/remove_at/#int) | Removes the element at the specified index of the collection. |
| [`join_block`](/slides/python-net/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Joins another mathematical block with this one |
| [`delimit`](/slides/python-net/aspose.slides.mathtext/mathblock/delimit/#char) | Delimits child elements with separator character (without the brackets) |
| [`write_as_math_ml`](/slides/python-net/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Saves content of this [`MathBlock`](/slides/python-net/aspose.slides.mathtext/mathblock) as MathML |

### See Also
* class [`MathBlock`](/slides/python-net/aspose.slides.mathtext/mathblock)
* class [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)
