---
title: IMathBox class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.mathtext/imathbox/
---
## IMathBox třída

Určuje logické zabalení (balení) matematického elementu.  
            Například zabalený objekt může sloužit jako emulátor operátoru s nebo bez bodu zarovnání,  
            sloužit jako bod zalomení řádku, nebo být seskupen tak, aby neumožňoval zalomení řádků uvnitř.  
            Například operátor „==“ by měl být zabalen, aby se zabránilo zalomení řádku.

Typ IMathBox představuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/base/) | Základní argument |
| [`operator_emulator`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/operator_emulator/) | Emulátor operátoru.<br/>            Když je true, krabice a její obsah se chovají jako jeden operátor a dědí vlastnosti operátoru. <br/>            To znamená například, že znak může sloužit jako bod pro zalomení řádku a může být zarovnán k ostatním operátorům.<br/>            Emulátory operátorů jsou často používány, když se jeden nebo více glifů spojuje do operátoru, jako je '=='.<br/>            Výchozí hodnota: false |
| [`no_break`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/no_break/) | Bez zalomení.<br/>            Toto vlastnost určuje vlastnost „unbreakable“ na objektové krabici. Když je true, žádné zalomení řádku se v krabici nevyskytne.<br/>            To může být důležité pro emulátory operátorů, které se skládají z více než jednoho binárního operátoru. <br/>            Když tento prvek není určen, mohou se v krabici vyskytovat zalomení.<br/>            Výchozí: true |
| [`differential`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/differential/) | Differenciál.<br/>            Když je true, krabice se chová jako diferenciál (např. 𝑑𝑥 v integrandu) a získá odpovídající <br/>            vodorovné odsazení pro matematický diferenciál.<br/>            Výchozí: false |
| [`alignment_point`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/alignment_point/) | Když je true, tento emulátor operátoru slouží jako zarovnávací bod; to znamená, <br/>            že určené zarovnávací body v jiných rovnicích mohou být s ním zarovnány.<br/>            Výchozí: false |
| [`explicit_break`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/explicit_break/) | Explicitní zalomení určuje, zda na začátku objektu Box je zalomení řádku, <br/>            takže řádek se zalamuje na začátku objektu Box.<br/>            Určuje číslo operátoru na předchozím řádku matematického textu, který bude<br/>            použit jako zarovnávací bod pro aktuální řádek matematického textu<br/>            možné hodnoty: 1..255<br/>            Výchozí: 0 (žádné explicitní zalomení) |

## Metody

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathbox/to_box/#) |  |

### Viz také
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)