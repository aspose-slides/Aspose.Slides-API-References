---
title: IMathFraction class
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.mathtext/imathfraction/
---
## IMathFraction osztály

Meghatározza a tört objektumot, amely számlálóval és nevezővel rendelkezik, amelyeket egy törtvonal választ el.  
            A törtvonal lehet vízszintes vagy átlós, a tört tulajdonságaitól függően.  
            A tört objektumot arra is használják, hogy a stack függvényt ábrázolják, amely egy elemet a másik fölé helyez, törtvonal nélkül.

Az IMathFraction típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`fraction_type`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/fraction_type/) | Tört típus<br/>            Alapértelmezett: Bar |
| [`numerator`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/numerator/) | Számláló |
| [`denominator`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/denominator/) | Nevező |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathfraction/to_box/#) |  |

### Lásd még
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)