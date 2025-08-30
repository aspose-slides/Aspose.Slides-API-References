---
title: MathArray class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/matharray/
---


## MathArray class

Specifies a vertical array of equations or any mathematical objects

**Inheritance:**[`MathArray`](/slides/python-net/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)

The MathArray type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides.mathtext/matharray/__init__/#asposeslidesmathtextimathelement) | Creates a mathematical array and places the specified element in it |
| [`__init__`](/slides/python-net/aspose.slides.mathtext/matharray/__init__/#systemcollectionsgenericienumerable1asposeslidesmathtextimathelement) |  |

## Properties

| Property | Description |
| :- | :- |
| [`arguments`](/slides/python-net/aspose.slides.mathtext/matharray/arguments/) | The set of items of the array |
| [`base_justification`](/slides/python-net/aspose.slides.mathtext/matharray/base_justification/) | Specifies alignment of the array relative to surrounding text<br/>            Text outside of the array can be aligned with the bottom, top, or center of a array object.<br/>            Default value: Center |
| [`maximum_distribution`](/slides/python-net/aspose.slides.mathtext/matharray/maximum_distribution/) | Maximum Distribution<br/>            When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [`object_distribution`](/slides/python-net/aspose.slides.mathtext/matharray/object_distribution/) | Object Distribution<br/>            When true, the contents of the array are spaced to the maximum width of the array object. |
| [`row_spacing_rule`](/slides/python-net/aspose.slides.mathtext/matharray/row_spacing_rule/) | The type of vertical spacing between array elements<br/>            Default: SingleLineGap |
| [`row_spacing`](/slides/python-net/aspose.slides.mathtext/matharray/row_spacing/) | Spacing between rows of an array<br/>            It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points <br/>            or Multiple in which case the unit of measure is half-lines.<br/>            Default: 0 |

## Methods

| Method | Description |
| :- | :- |
| [`join`](/slides/python-net/aspose.slides.mathtext/matharray/join/#asposeslidesmathtextimathelement) | Joins a mathematical element and forms a mathematical block |
| [`join`](/slides/python-net/aspose.slides.mathtext/matharray/join/#str) | Joins a mathematical text and forms a mathematical block |
| [`divide`](/slides/python-net/aspose.slides.mathtext/matharray/divide/#asposeslidesmathtextimathelement) | Creates a fraction with this numerator and specified denominator |
| [`divide`](/slides/python-net/aspose.slides.mathtext/matharray/divide/#str) | Creates a fraction with this numerator and specified denominator |
| [`divide`](/slides/python-net/aspose.slides.mathtext/matharray/divide/#asposeslidesmathtextimathelement-asposeslidesmathtextmathfractiontypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [`divide`](/slides/python-net/aspose.slides.mathtext/matharray/divide/#str-asposeslidesmathtextmathfractiontypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [`enclose`](/slides/python-net/aspose.slides.mathtext/matharray/enclose/#) | Encloses a math element in parenthesis |
| [`enclose`](/slides/python-net/aspose.slides.mathtext/matharray/enclose/#systemchar-systemchar) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [`function`](/slides/python-net/aspose.slides.mathtext/matharray/function/#asposeslidesmathtextimathelement) | Takes a function of an argument using this instance as the function name |
| [`function`](/slides/python-net/aspose.slides.mathtext/matharray/function/#str) | Takes a function of an argument using this instance as the function name |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/matharray/as_argument_of_function/#asposeslidesmathtextimathelement) | Takes specified function using this instance as the argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | Takes specified function using this instance as the argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/matharray/as_argument_of_function/#asposeslidesmathtextmathfunctionsofoneargument) | Takes specified function using this instance as the argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/matharray/as_argument_of_function/#asposeslidesmathtextmathfunctionsoftwoarguments-asposeslidesmathtextimathelement) | Takes specified function using this instance as the argument and specified additional argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/matharray/as_argument_of_function/#asposeslidesmathtextmathfunctionsoftwoarguments-str) | Takes specified function using this instance as the argument and specified additional argument |
| [`set_subscript`](/slides/python-net/aspose.slides.mathtext/matharray/set_subscript/#asposeslidesmathtextimathelement) | Creates subscript |
| [`set_subscript`](/slides/python-net/aspose.slides.mathtext/matharray/set_subscript/#str) | Creates subscript |
| [`set_superscript`](/slides/python-net/aspose.slides.mathtext/matharray/set_superscript/#asposeslidesmathtextimathelement) | Creates superscript |
| [`set_superscript`](/slides/python-net/aspose.slides.mathtext/matharray/set_superscript/#str) | Creates superscript |
| [`set_sub_superscript_on_the_right`](/slides/python-net/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#asposeslidesmathtextimathelement-asposeslidesmathtextimathelement) | Creates subscript and superscript on the right |
| [`set_sub_superscript_on_the_right`](/slides/python-net/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | Creates subscript and superscript on the right |
| [`set_sub_superscript_on_the_left`](/slides/python-net/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#asposeslidesmathtextimathelement-asposeslidesmathtextimathelement) | Creates subscript and superscript on the left |
| [`set_sub_superscript_on_the_left`](/slides/python-net/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | Creates subscript and superscript on the left |
| [`radical`](/slides/python-net/aspose.slides.mathtext/matharray/radical/#asposeslidesmathtextimathelement) | Specifies the mathematical root of the given degree from the specified argument. |
| [`radical`](/slides/python-net/aspose.slides.mathtext/matharray/radical/#str) | Specifies the mathematical root of the given degree from the specified argument. |
| [`set_upper_limit`](/slides/python-net/aspose.slides.mathtext/matharray/set_upper_limit/#asposeslidesmathtextimathelement) | Takes upper limit |
| [`set_upper_limit`](/slides/python-net/aspose.slides.mathtext/matharray/set_upper_limit/#str) | Takes upper limit |
| [`set_lower_limit`](/slides/python-net/aspose.slides.mathtext/matharray/set_lower_limit/#asposeslidesmathtextimathelement) | Takes lower limit |
| [`set_lower_limit`](/slides/python-net/aspose.slides.mathtext/matharray/set_lower_limit/#str) | Takes lower limit |
| [`nary`](/slides/python-net/aspose.slides.mathtext/matharray/nary/#asposeslidesmathtextmathnaryoperatortypes-asposeslidesmathtextimathelement-asposeslidesmathtextimathelement) | Creates a N-ary operator |
| [`nary`](/slides/python-net/aspose.slides.mathtext/matharray/nary/#asposeslidesmathtextmathnaryoperatortypes-str-str) | Creates a N-ary operator |
| [`integral`](/slides/python-net/aspose.slides.mathtext/matharray/integral/#asposeslidesmathtextmathintegraltypes-asposeslidesmathtextimathelement-asposeslidesmathtextimathelement-asposeslidesmathtextmathlimitlocations) | Takes the integral |
| [`integral`](/slides/python-net/aspose.slides.mathtext/matharray/integral/#asposeslidesmathtextmathintegraltypes-asposeslidesmathtextimathelement-asposeslidesmathtextimathelement) | Takes the integral |
| [`integral`](/slides/python-net/aspose.slides.mathtext/matharray/integral/#asposeslidesmathtextmathintegraltypes) | Takes the integral without limits |
| [`integral`](/slides/python-net/aspose.slides.mathtext/matharray/integral/#asposeslidesmathtextmathintegraltypes-str-str-asposeslidesmathtextmathlimitlocations) | Takes the integral |
| [`integral`](/slides/python-net/aspose.slides.mathtext/matharray/integral/#asposeslidesmathtextmathintegraltypes-str-str) | Takes the integral |
| [`group`](/slides/python-net/aspose.slides.mathtext/matharray/group/#) | Places this element in a group using a bottom curly bracket |
| [`group`](/slides/python-net/aspose.slides.mathtext/matharray/group/#systemchar-asposeslidesmathtextmathtopbotpositions-asposeslidesmathtextmathtopbotpositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [`to_border_box`](/slides/python-net/aspose.slides.mathtext/matharray/to_border_box/#) | Places this element in a border-box |
| [`to_border_box`](/slides/python-net/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Places this element in a border-box |
| [`to_math_array`](/slides/python-net/aspose.slides.mathtext/matharray/to_math_array/#) | Puts in a vertical array |
| [`accent`](/slides/python-net/aspose.slides.mathtext/matharray/accent/#systemchar) | Sets an accent mark (a character on the top of this element) |
| [`overbar`](/slides/python-net/aspose.slides.mathtext/matharray/overbar/#) | Sets a bar on the top of this element |
| [`underbar`](/slides/python-net/aspose.slides.mathtext/matharray/underbar/#) | Sets a bar on the bottom of this element |
| [`to_box`](/slides/python-net/aspose.slides.mathtext/matharray/to_box/#) | Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [`get_children`](/slides/python-net/aspose.slides.mathtext/matharray/get_children/#) | Get children elements |


### Examples

Example:


### See Also
* class [`MathArray`](/slides/python-net/aspose.slides.mathtext/matharray)
* class [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)

