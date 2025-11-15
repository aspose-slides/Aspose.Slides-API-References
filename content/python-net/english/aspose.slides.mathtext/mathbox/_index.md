---
title: MathBox class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/mathbox/
---


## MathBox class

Specifies the logical boxing (packaging) of mathematical element.
            For example, a boxed object can serve as an operator emulator with or without an alignment point, 
            serve as a line break point, or be grouped such as not to allow line breaks within.
            For example, the "==" operator should be boxed to prevent line breaks.

**Inheritance:**[`MathBox`](/slides/python-net/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)

The MathBox type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides.mathtext/mathbox/__init__/#imathelement) | Initializes MathBox with the specified element as an argument |

## Properties

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/aspose.slides.mathtext/mathbox/base/) | Base argument |
| [`operator_emulator`](/slides/python-net/aspose.slides.mathtext/mathbox/operator_emulator/) | Operator Emulator.<br/>            When true, the box and its contents behave as a single operator and inherit the properties of an operator. <br/>            This means, for example, that the character can serve as a point for a line break and can be aligned to other operators.<br/>            Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='.<br/>            Default value: false |
| [`no_break`](/slides/python-net/aspose.slides.mathtext/mathbox/no_break/) | No break<br/>            This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box.<br/>            This can be important for operator emulators that consist of more than one binary operator. <br/>            When this element is not specified, breaks can occur inside box.<br/>            Default: true |
| [`differential`](/slides/python-net/aspose.slides.mathtext/mathbox/differential/) | Differential<br/>            When true, the box acts as a differential (e.g., 𝑑𝑥 in an integrand), and receives the appropriate <br/>            horizontal spacing for the mathematical differential.<br/>            Default: false |
| [`alignment_point`](/slides/python-net/aspose.slides.mathtext/mathbox/alignment_point/) | When true, this operator emulator serves as an alignment point; that is, <br/>            designated alignment points in other equations can be aligned with it.<br/>            Default: false |
| [`explicit_break`](/slides/python-net/aspose.slides.mathtext/mathbox/explicit_break/) | Explicit break specifies whether there is a line break at the start of the Box object, <br/>            such that the line wraps at the start of the box object.<br/>            Specifies the number of the operator on the previous line of mathematical text which shall<br/>            be used as the alignment point for the current line of mathematical text<br/>            possible values: 1..255<br/>            Default: 0 (no explicit break) |

## Methods

| Method | Description |
| :- | :- |
| [`join`](/slides/python-net/aspose.slides.mathtext/mathbox/join/#imathelement) | Joins a mathematical element and forms a mathematical block |
| [`join`](/slides/python-net/aspose.slides.mathtext/mathbox/join/#str) | Joins a mathematical text and forms a mathematical block |
| [`divide`](/slides/python-net/aspose.slides.mathtext/mathbox/divide/#imathelement) | Creates a fraction with this numerator and specified denominator |
| [`divide`](/slides/python-net/aspose.slides.mathtext/mathbox/divide/#str) | Creates a fraction with this numerator and specified denominator |
| [`divide`](/slides/python-net/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [`divide`](/slides/python-net/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [`enclose`](/slides/python-net/aspose.slides.mathtext/mathbox/enclose/#) | Encloses a math element in parenthesis |
| [`enclose`](/slides/python-net/aspose.slides.mathtext/mathbox/enclose/#char-char) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [`function`](/slides/python-net/aspose.slides.mathtext/mathbox/function/#imathelement) | Takes a function of an argument using this instance as the function name |
| [`function`](/slides/python-net/aspose.slides.mathtext/mathbox/function/#str) | Takes a function of an argument using this instance as the function name |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | Takes specified function using this instance as the argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | Takes specified function using this instance as the argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | Takes specified function using this instance as the argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Takes specified function using this instance as the argument and specified additional argument |
| [`as_argument_of_function`](/slides/python-net/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Takes specified function using this instance as the argument and specified additional argument |
| [`set_subscript`](/slides/python-net/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | Creates subscript |
| [`set_subscript`](/slides/python-net/aspose.slides.mathtext/mathbox/set_subscript/#str) | Creates subscript |
| [`set_superscript`](/slides/python-net/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | Creates superscript |
| [`set_superscript`](/slides/python-net/aspose.slides.mathtext/mathbox/set_superscript/#str) | Creates superscript |
| [`set_sub_superscript_on_the_right`](/slides/python-net/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Creates subscript and superscript on the right |
| [`set_sub_superscript_on_the_right`](/slides/python-net/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | Creates subscript and superscript on the right |
| [`set_sub_superscript_on_the_left`](/slides/python-net/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Creates subscript and superscript on the left |
| [`set_sub_superscript_on_the_left`](/slides/python-net/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | Creates subscript and superscript on the left |
| [`radical`](/slides/python-net/aspose.slides.mathtext/mathbox/radical/#imathelement) | Specifies the mathematical root of the given degree from the specified argument. |
| [`radical`](/slides/python-net/aspose.slides.mathtext/mathbox/radical/#str) | Specifies the mathematical root of the given degree from the specified argument. |
| [`set_upper_limit`](/slides/python-net/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | Takes upper limit |
| [`set_upper_limit`](/slides/python-net/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | Takes upper limit |
| [`set_lower_limit`](/slides/python-net/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | Takes lower limit |
| [`set_lower_limit`](/slides/python-net/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | Takes lower limit |
| [`nary`](/slides/python-net/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Creates a N-ary operator |
| [`nary`](/slides/python-net/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | Creates a N-ary operator |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Takes the integral |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | Takes the integral |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | Takes the integral without limits |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Takes the integral |
| [`integral`](/slides/python-net/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | Takes the integral |
| [`group`](/slides/python-net/aspose.slides.mathtext/mathbox/group/#) | Places this element in a group using a bottom curly bracket |
| [`group`](/slides/python-net/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [`to_border_box`](/slides/python-net/aspose.slides.mathtext/mathbox/to_border_box/#) | Places this element in a border-box |
| [`to_border_box`](/slides/python-net/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Places this element in a border-box |
| [`to_math_array`](/slides/python-net/aspose.slides.mathtext/mathbox/to_math_array/#) | Puts in a vertical array |
| [`accent`](/slides/python-net/aspose.slides.mathtext/mathbox/accent/#char) | Sets an accent mark (a character on the top of this element) |
| [`overbar`](/slides/python-net/aspose.slides.mathtext/mathbox/overbar/#) | Sets a bar on the top of this element |
| [`underbar`](/slides/python-net/aspose.slides.mathtext/mathbox/underbar/#) | Sets a bar on the bottom of this element |
| [`to_box`](/slides/python-net/aspose.slides.mathtext/mathbox/to_box/#) | Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [`get_children`](/slides/python-net/aspose.slides.mathtext/mathbox/get_children/#) | Get children elements |


### See Also
* class [`MathBox`](/slides/python-net/aspose.slides.mathtext/mathbox)
* class [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)

