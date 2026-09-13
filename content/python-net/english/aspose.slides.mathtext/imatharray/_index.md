---
title: IMathArray class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/imatharray/
---


## IMathArray class

Specifies a vertical array of equations or any mathematical objects

The IMathArray type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`arguments`](/slides/python-net/aspose.slides.mathtext/imatharray/arguments/) | The set of items of the array |
| [`base_justification`](/slides/python-net/aspose.slides.mathtext/imatharray/base_justification/) | Specifies alignment of the array relative to surrounding text<br/>            Text outside of the array can be aligned with the bottom, top, or center of a array object.<br/>            Default value: Center |
| [`maximum_distribution`](/slides/python-net/aspose.slides.mathtext/imatharray/maximum_distribution/) | Maximum Distribution<br/>            When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [`object_distribution`](/slides/python-net/aspose.slides.mathtext/imatharray/object_distribution/) | Object Distribution<br/>            When true, the contents of the array are spaced to the maximum width of the array object. |
| [`row_spacing_rule`](/slides/python-net/aspose.slides.mathtext/imatharray/row_spacing_rule/) | The type of vertical spacing between array elements |
| [`row_spacing`](/slides/python-net/aspose.slides.mathtext/imatharray/row_spacing/) | Spacing between rows of an array<br/>            It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points <br/>            or Multiple in which case the unit of measure is half-lines.<br/>            Default: 0 |

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/aspose.slides.mathtext/imatharray/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/aspose.slides.mathtext/imatharray/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/aspose.slides.mathtext/imatharray/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/aspose.slides.mathtext/imatharray/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/aspose.slides.mathtext/imatharray/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/aspose.slides.mathtext/imatharray/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/aspose.slides.mathtext/imatharray/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/aspose.slides.mathtext/imatharray/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/aspose.slides.mathtext/imatharray/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/aspose.slides.mathtext/imatharray/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/aspose.slides.mathtext/imatharray/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/aspose.slides.mathtext/imatharray/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/aspose.slides.mathtext/imatharray/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/aspose.slides.mathtext/imatharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/aspose.slides.mathtext/imatharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/aspose.slides.mathtext/imatharray/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/aspose.slides.mathtext/imatharray/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/aspose.slides.mathtext/imatharray/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/aspose.slides.mathtext/imatharray/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/aspose.slides.mathtext/imatharray/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/aspose.slides.mathtext/imatharray/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/aspose.slides.mathtext/imatharray/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/aspose.slides.mathtext/imatharray/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/aspose.slides.mathtext/imatharray/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/aspose.slides.mathtext/imatharray/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/aspose.slides.mathtext/imatharray/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/aspose.slides.mathtext/imatharray/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/aspose.slides.mathtext/imatharray/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/aspose.slides.mathtext/imatharray/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/aspose.slides.mathtext/imatharray/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/aspose.slides.mathtext/imatharray/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/aspose.slides.mathtext/imatharray/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/aspose.slides.mathtext/imatharray/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/aspose.slides.mathtext/imatharray/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/aspose.slides.mathtext/imatharray/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/aspose.slides.mathtext/imatharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/aspose.slides.mathtext/imatharray/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/aspose.slides.mathtext/imatharray/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/aspose.slides.mathtext/imatharray/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/aspose.slides.mathtext/imatharray/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/aspose.slides.mathtext/imatharray/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/aspose.slides.mathtext/imatharray/to_box/#) |  |


### See Also
* module [`aspose.slides.mathtext`](/slides/python-net/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)

