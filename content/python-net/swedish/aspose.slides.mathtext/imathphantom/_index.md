---
title: IMathPhantom class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/imathphantom/
---
## IMathPhantom klass

Representerar ett fantommatematiktobjekt (<m:phant>) som påverkar layouten för dess underordnade element utan att nödvändigtvis visa det. Ett fantom kan dölja sitt basuttryck samtidigt som dess bredd, höjd eller djup bevaras för att justera formler eller reservera utrymme. Synlighet och geometribeteende styrs av egenskaper såsom Show, ZeroWid, ZeroAsc, ZeroDesc och Transp.

The IMathPhantom type exposes the following members:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`base`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/base/) | Basargument |
| [`show`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/show/) | Hämtar eller anger ett värde som indikerar om baselementet visas. |
| [`zero_width`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/zero_width/) | Hämtar eller anger ett värde som indikerar om bredden på baselementet <br/>            ska behandlas som noll. |
| [`zero_asc`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/zero_asc/) | Hämtar eller anger ett värde som indikerar om stigningen (höjd över baslinjen) <br/>            för baselementet ska behandlas som noll. |
| [`zero_desc`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/zero_desc/) | Hämtar eller anger ett värde som indikerar om nedstigningen (djup under baslinjen)<br/>            för baselementet ska behandlas som noll. |
| [`transp`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/transp/) | Hämtar eller anger ett värde som indikerar om fantomet är transparent <br/>            för klassbaserade avståndsregler. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathphantom/to_box/#) |  |

### Se även
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)