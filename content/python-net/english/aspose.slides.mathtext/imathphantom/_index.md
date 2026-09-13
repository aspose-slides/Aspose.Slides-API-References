---
title: IMathPhantom class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.mathtext/imathphantom/
---


## IMathPhantom class

Represents a phantom math object (<m:phant>) that affects the layout of its child element
            without necessarily displaying it. A phantom can hide its base expression while preserving
            its width, height, or depth to align formulas or reserve space. 
            Visibility and geometry behavior are controlled by properties such as Show, ZeroWid, ZeroAsc, 
            ZeroDesc, and Transp.

The IMathPhantom type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/aspose.slides.mathtext/imathphantom/base/) | Base argument |
| [`show`](/slides/python-net/aspose.slides.mathtext/imathphantom/show/) | Gets or sets a value indicating whether the base element is displayed. |
| [`zero_width`](/slides/python-net/aspose.slides.mathtext/imathphantom/zero_width/) | Gets or sets a value indicating whether the width of the base element <br/>            should be treated as zero. |
| [`zero_asc`](/slides/python-net/aspose.slides.mathtext/imathphantom/zero_asc/) | Gets or sets a value indicating whether the ascent (height above baseline) <br/>            of the base element should be treated as zero. |
| [`zero_desc`](/slides/python-net/aspose.slides.mathtext/imathphantom/zero_desc/) | Gets or sets a value indicating whether the descent (depth below baseline)<br/>            of the base element should be treated as zero. |
| [`transp`](/slides/python-net/aspose.slides.mathtext/imathphantom/transp/) | Gets or sets a value indicating whether the phantom is transparent <br/>            for class-based spacing rules. |

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/aspose.slides.mathtext/imathphantom/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/aspose.slides.mathtext/imathphantom/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/aspose.slides.mathtext/imathphantom/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/aspose.slides.mathtext/imathphantom/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/aspose.slides.mathtext/imathphantom/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/aspose.slides.mathtext/imathphantom/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/aspose.slides.mathtext/imathphantom/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/aspose.slides.mathtext/imathphantom/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/aspose.slides.mathtext/imathphantom/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/aspose.slides.mathtext/imathphantom/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/aspose.slides.mathtext/imathphantom/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/aspose.slides.mathtext/imathphantom/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/aspose.slides.mathtext/imathphantom/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/aspose.slides.mathtext/imathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/aspose.slides.mathtext/imathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/aspose.slides.mathtext/imathphantom/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/aspose.slides.mathtext/imathphantom/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/aspose.slides.mathtext/imathphantom/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/aspose.slides.mathtext/imathphantom/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/aspose.slides.mathtext/imathphantom/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/aspose.slides.mathtext/imathphantom/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/aspose.slides.mathtext/imathphantom/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/aspose.slides.mathtext/imathphantom/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/aspose.slides.mathtext/imathphantom/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/aspose.slides.mathtext/imathphantom/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/aspose.slides.mathtext/imathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/aspose.slides.mathtext/imathphantom/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/aspose.slides.mathtext/imathphantom/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/aspose.slides.mathtext/imathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/aspose.slides.mathtext/imathphantom/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/aspose.slides.mathtext/imathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/aspose.slides.mathtext/imathphantom/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/aspose.slides.mathtext/imathphantom/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/aspose.slides.mathtext/imathphantom/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/aspose.slides.mathtext/imathphantom/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/aspose.slides.mathtext/imathphantom/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/aspose.slides.mathtext/imathphantom/to_box/#) |  |


### See Also
* module [`aspose.slides.mathtext`](/slides/python-net/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)

