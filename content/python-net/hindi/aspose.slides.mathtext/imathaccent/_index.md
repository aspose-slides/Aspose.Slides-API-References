---
title: IMathAccent class
second_title: Aspose.Slides for Python के माध्यम से .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.mathtext/imathaccent/
---
## IMathAccent क्लास

एक्सेंट फ़ंक्शन को निर्दिष्ट करता है, जिसमें एक बेस और एक संयोजित डायक्रिटिकल मार्क शामिल है।  
Example: 𝑎́

IMathAccent टाइप निम्नलिखित सदस्यों को उजागर करता है:

## गुण

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/base/) | वह तर्क जिस पर एक्सेंट लागू किया गया था |
| [`character`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/character/) | Accent Character<br/>The value should be within the range of (U+0300–U+036F) or(U+20D0–U+20EF)<br/>Default value: Combining Circumflex Accent (U+0302) |

## विधियाँ

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/hi/aspose.slides.mathtext/imathaccent/to_box/#) |  |

### संबंधित देखें
* मॉड्यूल [`aspose.slides.mathtext`](/slides/python-net/hi/aspose.slides.mathtext)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)