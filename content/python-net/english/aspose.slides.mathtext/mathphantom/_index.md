---
title: MathPhantom class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/mathphantom/
---


## MathPhantom class

Represents a phantom math object (<m:phant>) that affects the layout of its child element
            without necessarily displaying it. A phantom can hide its base expression while preserving
            its width, height, or depth to align formulas or reserve space. 
            Visibility and geometry behavior are controlled by properties such as Show, ZeroWid, ZeroAsc, 
            ZeroDesc, and Transp.

**Inheritance:**[`MathPhantom`](/slides/python-net/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)

The MathPhantom type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | Initializes a new instance of the [`MathPhantom`](/slides/python-net/aspose.slides.mathtext/mathphantom) class <br/>            using the specified base math element. |

## Properties

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/aspose.slides.mathtext/mathphantom/base/) | Base argument |
| [`show`](/slides/python-net/aspose.slides.mathtext/mathphantom/show/) | Gets or sets a value indicating whether the base element is displayed. |
| [`zero_width`](/slides/python-net/aspose.slides.mathtext/mathphantom/zero_width/) | Gets or sets a value indicating whether the width of the base element <br/>            should be treated as zero. |
| [`zero_asc`](/slides/python-net/aspose.slides.mathtext/mathphantom/zero_asc/) | Gets or sets a value indicating whether the ascent (height above baseline) <br/>            of the base element should be treated as zero. |
| [`zero_desc`](/slides/python-net/aspose.slides.mathtext/mathphantom/zero_desc/) | Gets or sets a value indicating whether the descent (depth below baseline)<br/>            of the base element should be treated as zero. |
| [`transp`](/slides/python-net/aspose.slides.mathtext/mathphantom/transp/) | Gets or sets a value indicating whether the phantom is transparent <br/>            for class-based spacing rules. |

## Methods

| Method | Description |
| :- | :- |
| [`join`](/slides/python-net/aspose.slides.mathtext/mathphantom/join/#imathelement) | Joins a mathematical element and forms a mathematical block |
| [`join`](/slides/python-net/aspose.slides.mathtext/mathphantom/join/#str) | Joins a mathematical text and forms a mathematical block |
| [`divide`](/slides/python-net/aspose.slides.mathtext/mathphantom/divide/#imathelement) | Creates a fraction with this numerator and specified denominator |
| [`divide`](/slides/python-net/aspose.slides.mathtext/mathphantom/divide/#str) | Creates a fraction with this numerator and specified denominator |
| [`divide`](/slides/python-net/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [`divide`](/slides/python-net/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [`enclose`](/slides/python-net/aspose.slides.mathtext/mathphantom/enclose/#) | Encloses a math element in parenthesis |
| [`enclose`](/slides/python-net/aspose.slides.mathtext/mathphantom/enclose/#char-char) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [`function`](/slides/python-net/aspose.slides.mathtext/mathphantom/function/#imathelement) | Takes a function of an argument using this instance as the function name |
| [`function`](/slides/python-net/aspose.slides.mathtext/mathphantom/function/#str) | Takes a function of an argument using this instance as the function name |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | Takes specified function using this instance as the argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | Takes specified function using this instance as the argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | Takes specified function using this instance as the argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Takes specified function using this instance as the argument and specified additional argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Takes specified function using this instance as the argument and specified additional argument |
| [`set_subscript`](/slides/python-net/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | Creates subscript |
| [`set_subscript`](/slides/python-net/aspose.slides.mathtext/mathphantom/set_subscript/#str) | Creates subscript |
| [`set_superscript`](/slides/python-net/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | Creates superscript |
| [`set_superscript`](/slides/python-net/aspose.slides.mathtext/mathphantom/set_superscript/#str) | Creates superscript |
| [`set_sub_superscript_on_the_right`](/slides/python-net/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | Creates subscript and superscript on the right |
| [`set_sub_superscript_on_the_right`](/slides/python-net/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | Creates subscript and superscript on the right |
| [`set_sub_superscript_on_the_left`](/slides/python-net/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | Creates subscript and superscript on the left |
| [`set_sub_superscript_on_the_left`](/slides/python-net/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | Creates subscript and superscript on the left |
| [`radical`](/slides/python-net/aspose.slides.mathtext/mathphantom/radical/#imathelement) | Specifies the mathematical root of the given degree from the specified argument. |
| [`radical`](/slides/python-net/aspose.slides.mathtext/mathphantom/radical/#str) | Specifies the mathematical root of the given degree from the specified argument. |
| [`set_upper_limit`](/slides/python-net/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | Takes upper limit |
| [`set_upper_limit`](/slides/python-net/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | Takes upper limit |
| [`set_lower_limit`](/slides/python-net/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | Takes lower limit |
| [`set_lower_limit`](/slides/python-net/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | Takes lower limit |
| [`nary`](/slides/python-net/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | Creates a N-ary operator |
| [`nary`](/slides/python-net/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | Creates a N-ary operator |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Takes the integral |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | Takes the integral |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | Takes the integral without limits |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | Takes the integral |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | Takes the integral |
| [`group`](/slides/python-net/aspose.slides.mathtext/mathphantom/group/#) | Places this element in a group using a bottom curly bracket |
| [`group`](/slides/python-net/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [`to_border_box`](/slides/python-net/aspose.slides.mathtext/mathphantom/to_border_box/#) | Places this element in a border-box |
| [`to_border_box`](/slides/python-net/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Places this element in a border-box |
| [`to_math_array`](/slides/python-net/aspose.slides.mathtext/mathphantom/to_math_array/#) | Puts in a vertical array |
| [`accent`](/slides/python-net/aspose.slides.mathtext/mathphantom/accent/#char) | Sets an accent mark (a character on the top of this element) |
| [`overbar`](/slides/python-net/aspose.slides.mathtext/mathphantom/overbar/#) | Sets a bar on the top of this element |
| [`underbar`](/slides/python-net/aspose.slides.mathtext/mathphantom/underbar/#) | Sets a bar on the bottom of this element |
| [`to_box`](/slides/python-net/aspose.slides.mathtext/mathphantom/to_box/#) | Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [`get_children`](/slides/python-net/aspose.slides.mathtext/mathphantom/get_children/#) | Get children elements |


### See Also
* class [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)
* class [`MathPhantom`](/slides/python-net/aspose.slides.mathtext/mathphantom)
* module [`aspose.slides.mathtext`](/slides/python-net/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)

