---
title: MathFraction
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
weight: 610
url: /python-net/aspose.slides.mathtext/mathfraction/
---

## MathFraction class

Specifies the fraction object, consisting of a numerator and denominator separated by a fraction bar.<br/>            The fraction bar can be horizontal or diagonal, depending on the fraction properties.<br/>            The fraction object is also used to represent the stack function, which places one element above another, with no fraction bar.

The MathFraction type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|MathFraction(numerator, denominator, fraction_type)|Initializes a new instance of the MathFraction class|
|MathFraction(numerator, denominator)|Initializes a new instance of the MathFraction class|
## Properties
| Name | Description |
| :- | :- |
|fraction_type|Fraction type<br/>            Default: Bar|
|numerator|Numerator|
|denominator|Denominator|
|as_i_math_element|Allows to get base IMathElement interface<br/>            [IMathElement](/slides/python-net/aspose.slides.mathtext/imathelement/)|
## Methods
| Name | Description |
| :- | :- |
|join(math_element)|Joins a mathematical element and forms a mathematical block|
|join(math_text)|Joins a mathematical text and forms a mathematical block|
|divide(denominator)|Creates a fraction with this numerator and specified denominator|
|divide(denominator)|Creates a fraction with this numerator and specified denominator|
|divide(denominator, fraction_type)|Creates a fraction of the specified type with this numerator and specified denominator|
|divide(denominator, fraction_type)|Creates a fraction of the specified type with this numerator and specified denominator|
|enclose()|Encloses a math element in parenthesis|
|enclose(beginning_character, ending_character)|Encloses a math element in specified characters such as parenthesis or another characters as framing|
|function(function_argument)|Takes a function of an argument using this instance as the function name|
|function(function_argument)|Takes a function of an argument using this instance as the function name|
|as_argument_of_function(function_name)|Takes specified function using this instance as the argument|
|as_argument_of_function(function_name)|Takes specified function using this instance as the argument|
|as_argument_of_function(function_type)|Takes specified function using this instance as the argument|
|as_argument_of_function(function_type, additional_argument)|Takes specified function using this instance as the argument and specified additional argument|
|as_argument_of_function(function_type, additional_argument)|Takes specified function using this instance as the argument and specified additional argument|
|set_subscript(subscript)|Creates subscript|
|set_subscript(subscript)|Creates subscript|
|set_superscript(superscript)|Creates superscript|
|set_superscript(superscript)|Creates superscript|
|set_sub_superscript_on_the_right(subscript, superscript)|Creates subscript and superscript on the right|
|set_sub_superscript_on_the_right(subscript, superscript)|Creates subscript and superscript on the right|
|set_sub_superscript_on_the_left(subscript, superscript)|Creates subscript and superscript on the left|
|set_sub_superscript_on_the_left(subscript, superscript)|Creates subscript and superscript on the left|
|radical(degree)|Specifies the mathematical root of the given degree from the specified argument.|
|radical(degree)|Specifies the mathematical root of the given degree from the specified argument.|
|set_upper_limit(limit)|Takes upper limit|
|set_upper_limit(limit)|Takes upper limit|
|set_lower_limit(limit)|Takes lower limit|
|set_lower_limit(limit)|Takes lower limit|
|nary(type, lower_limit, upper_limit)|Creates a N-ary operator|
|nary(type, lower_limit, upper_limit)|Creates a N-ary operator|
|integral(integral_type, lower_limit, upper_limit, limit_locations)|Takes the integral|
|integral(integral_type, lower_limit, upper_limit)|Takes the integral|
|integral(integral_type)|Takes the integral|
|integral(integral_type, lower_limit, upper_limit, limit_locations)|Takes the integral|
|integral(integral_type, lower_limit, upper_limit)|Takes the integral|
|group()|Places this element in a group using a bottom curly bracket|
|group(character, position, vertical_justification)|Places this element in a group using a grouping character such as bottom curly bracket or another|
|to_border_box()|Places this element in a border-box|
|to_border_box(hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)|Places this element in a border-box|
|to_math_array()|Puts in a vertical array|
|accent(accent_character)|Sets an accent mark (a character on the top of this element)|
|overbar()|Sets a bar on the top of this element|
|underbar()|Sets a bar on the bottom of this element|
|to_box()|Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within.|
|get_children()|Get children elements|

### See Also

* namespace [aspose.slides.mathtext](/slides/python-net/aspose.slides.mathtext/)
* assembly [Aspose.Slides](/slides/python-net/)
