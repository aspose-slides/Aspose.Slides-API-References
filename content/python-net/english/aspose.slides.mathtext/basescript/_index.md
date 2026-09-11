---
title: BaseScript class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/basescript/
---


## BaseScript class

Math script

**Inheritance:**[`BaseScript`](/slides/python-net/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)

The BaseScript type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/aspose.slides.mathtext/basescript/base/) | Base argument |

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/aspose.slides.mathtext/basescript/join/#imathelement) | Joins a mathematical element and forms a mathematical block |
| [`join(self, math_text)`](/slides/python-net/aspose.slides.mathtext/basescript/join/#str) | Joins a mathematical text and forms a mathematical block |
| [`divide(self, denominator)`](/slides/python-net/aspose.slides.mathtext/basescript/divide/#imathelement) | Creates a fraction with this numerator and specified denominator |
| [`divide(self, denominator)`](/slides/python-net/aspose.slides.mathtext/basescript/divide/#str) | Creates a fraction with this numerator and specified denominator |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/aspose.slides.mathtext/basescript/divide/#imathelement-mathfractiontypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/aspose.slides.mathtext/basescript/divide/#str-mathfractiontypes) | Creates a fraction of the specified type with this numerator and specified denominator |
| [`enclose(self)`](/slides/python-net/aspose.slides.mathtext/basescript/enclose/#) | Encloses a math element in parenthesis |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/aspose.slides.mathtext/basescript/enclose/#char-char) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [`function(self, function_argument)`](/slides/python-net/aspose.slides.mathtext/basescript/function/#imathelement) | Takes a function of an argument using this instance as the function name |
| [`function(self, function_argument)`](/slides/python-net/aspose.slides.mathtext/basescript/function/#str) | Takes a function of an argument using this instance as the function name |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/aspose.slides.mathtext/basescript/as_argument_of_function/#imathelement) | Takes specified function using this instance as the argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/aspose.slides.mathtext/basescript/as_argument_of_function/#str) | Takes specified function using this instance as the argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/aspose.slides.mathtext/basescript/as_argument_of_function/#mathfunctionsofoneargument) | Takes specified function using this instance as the argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/aspose.slides.mathtext/basescript/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Takes specified function using this instance as the argument and specified additional argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/aspose.slides.mathtext/basescript/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Takes specified function using this instance as the argument and specified additional argument |
| [`set_subscript(self, subscript)`](/slides/python-net/aspose.slides.mathtext/basescript/set_subscript/#imathelement) | Creates subscript |
| [`set_subscript(self, subscript)`](/slides/python-net/aspose.slides.mathtext/basescript/set_subscript/#str) | Creates subscript |
| [`set_superscript(self, superscript)`](/slides/python-net/aspose.slides.mathtext/basescript/set_superscript/#imathelement) | Creates superscript |
| [`set_superscript(self, superscript)`](/slides/python-net/aspose.slides.mathtext/basescript/set_superscript/#str) | Creates superscript |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/aspose.slides.mathtext/basescript/set_sub_superscript_on_the_right/#imathelement-imathelement) | Creates subscript and superscript on the right |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/aspose.slides.mathtext/basescript/set_sub_superscript_on_the_right/#str-str) | Creates subscript and superscript on the right |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/aspose.slides.mathtext/basescript/set_sub_superscript_on_the_left/#imathelement-imathelement) | Creates subscript and superscript on the left |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/aspose.slides.mathtext/basescript/set_sub_superscript_on_the_left/#str-str) | Creates subscript and superscript on the left |
| [`radical(self, degree)`](/slides/python-net/aspose.slides.mathtext/basescript/radical/#imathelement) | Specifies the mathematical root of the given degree from the specified argument. |
| [`radical(self, degree)`](/slides/python-net/aspose.slides.mathtext/basescript/radical/#str) | Specifies the mathematical root of the given degree from the specified argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/aspose.slides.mathtext/basescript/set_upper_limit/#imathelement) | Takes upper limit |
| [`set_upper_limit(self, limit)`](/slides/python-net/aspose.slides.mathtext/basescript/set_upper_limit/#str) | Takes upper limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/aspose.slides.mathtext/basescript/set_lower_limit/#imathelement) | Takes lower limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/aspose.slides.mathtext/basescript/set_lower_limit/#str) | Takes lower limit |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/aspose.slides.mathtext/basescript/nary/#mathnaryoperatortypes-imathelement-imathelement) | Creates a N-ary operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/aspose.slides.mathtext/basescript/nary/#mathnaryoperatortypes-str-str) | Creates a N-ary operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/aspose.slides.mathtext/basescript/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Takes the integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/aspose.slides.mathtext/basescript/integral/#mathintegraltypes-imathelement-imathelement) | Takes the integral |
| [`integral(self, integral_type)`](/slides/python-net/aspose.slides.mathtext/basescript/integral/#mathintegraltypes) | Takes the integral without limits |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/aspose.slides.mathtext/basescript/integral/#mathintegraltypes-str-str-mathlimitlocations) | Takes the integral |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/aspose.slides.mathtext/basescript/integral/#mathintegraltypes-str-str) | Takes the integral |
| [`group(self)`](/slides/python-net/aspose.slides.mathtext/basescript/group/#) | Places this element in a group using a bottom curly bracket |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/aspose.slides.mathtext/basescript/group/#char-mathtopbotpositions-mathtopbotpositions) | Places this element in a group using a grouping character such as bottom curly bracket or another |
| [`to_border_box(self)`](/slides/python-net/aspose.slides.mathtext/basescript/to_border_box/#) | Places this element in a border-box |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/aspose.slides.mathtext/basescript/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Places this element in a border-box |
| [`to_math_array(self)`](/slides/python-net/aspose.slides.mathtext/basescript/to_math_array/#) | Puts in a vertical array |
| [`accent(self, accent_character)`](/slides/python-net/aspose.slides.mathtext/basescript/accent/#char) | Sets an accent mark (a character on the top of this element) |
| [`overbar(self)`](/slides/python-net/aspose.slides.mathtext/basescript/overbar/#) | Sets a bar on the top of this element |
| [`underbar(self)`](/slides/python-net/aspose.slides.mathtext/basescript/underbar/#) | Sets a bar on the bottom of this element |
| [`to_box(self)`](/slides/python-net/aspose.slides.mathtext/basescript/to_box/#) | Places this element in a non-visual box (logical grouping) <br/>            which is used to group components of an equation or other instance of mathematical text.<br/>            A boxed object can (for example) serve as an operator emulator with or without an alignment point, <br/>            serve as a line break point, or be grouped such as not to allow line breaks within. |
| [`get_children(self)`](/slides/python-net/aspose.slides.mathtext/basescript/get_children/#) |  |


### See Also
* class [`BaseScript`](/slides/python-net/aspose.slides.mathtext/basescript)
* class [`MathElementBase`](/slides/python-net/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)

