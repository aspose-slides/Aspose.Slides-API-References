---
title: MathRadical class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathradical/
---
## MathRadical klass

Specificerar radicalfunktionen, bestående av en bas och en valfri grad.
            Exempel på radikalobjekt är √𝑥.

**Arv:**[`MathRadical`](/slides/python-net/sv/aspose.slides.mathtext/mathradical) → [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)

MathRadical-typen exponerar följande medlemmar:

## Konstruktörer

| Constructor | Description |
| :- | :- |
| [`__init__(self, base_argument, degree_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/__init__/#imathelement-imathelement) | Initierar en ny instans av MathRadical-klassen. |

## Egenskaper

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/base/) | Basargument |
| [`degree`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/degree/) | Gradargument |
| [`hide_degree`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/hide_degree/) | Dölj grad<br/>            När den är sann visas inte graden, som i √𝑥 |

## Metoder

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/join/#imathelement) | Kombinerar ett matematiskt element och bildar ett matematiskt block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/join/#str) | Kombinerar en matematisk text och bildar ett matematiskt block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/divide/#imathelement) | Skapar en bråkdel med detta täljare och specificerad nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/divide/#str) | Skapar en bråkdel med detta täljare och specificerad nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/divide/#imathelement-mathfractiontypes) | Skapar en bråkdel av den specificerade typen med detta täljare och specificerad nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/divide/#str-mathfractiontypes) | Skapar en bråkdel av den specificerade typen med detta täljare och specificerad nämnare |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/enclose/#) | Innesluter ett matematiskt element i parentes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/enclose/#char-char) | Innesluter ett matematiskt element i specificerade tecken såsom parentes eller andra tecken som ram |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/function/#imathelement) | Tar en funktion av ett argument med denna instans som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/function/#str) | Tar en funktion av ett argument med denna instans som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/as_argument_of_function/#imathelement) | Tar specificerad funktion med denna instans som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/as_argument_of_function/#str) | Tar specificerad funktion med denna instans som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsofoneargument) | Tar specificerad funktion med denna instans som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar specificerad funktion med denna instans som argument och specificerat ytterligare argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar specificerad funktion med denna instans som argument och specificerat ytterligare argument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/set_subscript/#imathelement) | Skapar index |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/set_subscript/#str) | Skapar index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/set_superscript/#imathelement) | Skapar exponent |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/set_superscript/#str) | Skapar exponent |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar index och exponent till höger |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_right/#str-str) | Skapar index och exponent till höger |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar index och exponent till vänster |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/set_sub_superscript_on_the_left/#str-str) | Skapar index och exponent till vänster |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/radical/#imathelement) | Specificerar den matematiska roten av given grad från det specificerade argumentet. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/radical/#str) | Specificerar den matematiska roten av given grad från det specificerade argumentet. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/set_lower_limit/#imathelement) | Tar nedre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/set_lower_limit/#str) | Tar nedre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-är operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/nary/#mathnaryoperatortypes-str-str) | Skapar en N-är operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralen |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/integral/#mathintegraltypes-str-str) | Tar integralen |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/group/#) | Placera detta element i en grupp med en klammerparentes nedtill |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/group/#char-mathtopbotpositions-mathtopbotpositions) | Placera detta element i en grupp med ett grupperingstecken såsom en klammerparentes nedtill eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/to_border_box/#) | Placera detta element i en kantlåda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placera detta element i en kantlåda |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/to_math_array/#) | Sätter in en vertikal matris |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/accent/#char) | Sätter ett accenttecken (ett tecken ovanför detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/overbar/#) | Sätter ett streck över detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/underbar/#) | Sätter ett streck under detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/to_box/#) | Placera detta element i en icke-visuell ruta (logisk gruppering) <br/>            som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text.<br/>            En inramad objekt kan (till exempel) fungera som en operatoremulator med eller utan en justeringspunkt, <br/>            fungera som en radbrytpunkt, eller grupperas så att radbrytningar inte tillåts inom. |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathradical/get_children/#) | Hämta underordnade element |


### Se också
* klass [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)
* klass [`MathRadical`](/slides/python-net/sv/aspose.slides.mathtext/mathradical)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)