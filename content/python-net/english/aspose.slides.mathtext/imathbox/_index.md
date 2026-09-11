---
title: IMathBox class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/imathbox/
---


## IMathBox class

Specifies the logical boxing (packaging) of mathematical element.
            For example, a boxed object can serve as an operator emulator with or without an alignment point, 
            serve as a line break point, or be grouped such as not to allow line breaks within.
            For example, the "==" operator should be boxed to prevent line breaks.

The IMathBox type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/aspose.slides.mathtext/imathbox/base/) | Base argument |
| [`operator_emulator`](/slides/python-net/aspose.slides.mathtext/imathbox/operator_emulator/) | Operator Emulator.<br/>            When true, the box and its contents behave as a single operator and inherit the properties of an operator. <br/>            This means, for example, that the character can serve as a point for a line break and can be aligned to other operators.<br/>            Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='.<br/>            Default value: false |
| [`no_break`](/slides/python-net/aspose.slides.mathtext/imathbox/no_break/) | No break.<br/>            This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box.<br/>            This can be important for operator emulators that consist of more than one binary operator. <br/>            When this element is not specified, breaks can occur inside box.<br/>            Default: true |
| [`differential`](/slides/python-net/aspose.slides.mathtext/imathbox/differential/) | Differential.<br/>            When true, the box acts as a differential (e.g., 𝑑𝑥 in an integrand), and receives the appropriate <br/>            horizontal spacing for the mathematical differential.<br/>            Default: false |
| [`alignment_point`](/slides/python-net/aspose.slides.mathtext/imathbox/alignment_point/) | When true, this operator emulator serves as an alignment point; that is, <br/>            designated alignment points in other equations can be aligned with it.<br/>            Default: false |
| [`explicit_break`](/slides/python-net/aspose.slides.mathtext/imathbox/explicit_break/) | Explicit break specifies whether there is a line break at the start of the Box object, <br/>            such that the line wraps at the start of the box object.<br/>            Specifies the number of the operator on the previous line of mathematical text which shall<br/>            be used as the alignment point for the current line of mathematical text<br/>            possible values: 1..255<br/>            Default: 0 (no explicit break) |

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/aspose.slides.mathtext/imathbox/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/aspose.slides.mathtext/imathbox/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/aspose.slides.mathtext/imathbox/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/aspose.slides.mathtext/imathbox/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/aspose.slides.mathtext/imathbox/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/aspose.slides.mathtext/imathbox/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/aspose.slides.mathtext/imathbox/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/aspose.slides.mathtext/imathbox/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/aspose.slides.mathtext/imathbox/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/aspose.slides.mathtext/imathbox/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/aspose.slides.mathtext/imathbox/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/aspose.slides.mathtext/imathbox/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/aspose.slides.mathtext/imathbox/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/aspose.slides.mathtext/imathbox/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/aspose.slides.mathtext/imathbox/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/aspose.slides.mathtext/imathbox/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/aspose.slides.mathtext/imathbox/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/aspose.slides.mathtext/imathbox/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/aspose.slides.mathtext/imathbox/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/aspose.slides.mathtext/imathbox/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/aspose.slides.mathtext/imathbox/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/aspose.slides.mathtext/imathbox/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/aspose.slides.mathtext/imathbox/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/aspose.slides.mathtext/imathbox/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/aspose.slides.mathtext/imathbox/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/aspose.slides.mathtext/imathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/aspose.slides.mathtext/imathbox/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/aspose.slides.mathtext/imathbox/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/aspose.slides.mathtext/imathbox/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/aspose.slides.mathtext/imathbox/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/aspose.slides.mathtext/imathbox/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/aspose.slides.mathtext/imathbox/to_box/#) |  |


### See Also
* module [`aspose.slides.mathtext`](/slides/python-net/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)

