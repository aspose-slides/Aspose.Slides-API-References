---
title: MathLimit class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathlimit/
---
## MathLimit klass

Specificerar Limit-objektet, bestående av text på baslinjen och förminskad text omedelbart ovanför eller under den.

**Arv:**[`MathLimit`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit) → [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)

MathLimit-typen exponerar följande medlemmar:

## Konstruktörer

| Konstruktör | Beskrivning |
| :- | :- |
| [`__init__(self, base_arg, limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement-bool) | Initierar en ny instans av MathLimit-klass. |
| [`__init__(self, base_arg, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement) | Initierar en ny instans av MathLimit-klass med lägre gräns |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`base`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/base/) | Basargument |
| [`limit`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/limit/) | Gränsargument |
| [`upper_limit`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/upper_limit/) | Specificerar övre eller nedre gräns |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/join/#imathelement) | Kombinerar ett matematiskt element och bildar ett matematiskt block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/join/#str) | Kombinerar en matematisk text och bildar ett matematiskt block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/divide/#imathelement) | Skapar ett bråk med detta täljare och angiven nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/divide/#str) | Skapar ett bråk med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/divide/#imathelement-mathfractiontypes) | Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/divide/#str-mathfractiontypes) | Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/enclose/#) | Innesluter ett matematiskt element i parenteser |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/enclose/#char-char) | Innesluter ett matematiskt element i specificerade tecken, t.ex. parenteser eller andra tecken som ram |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/function/#imathelement) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/function/#str) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/as_argument_of_function/#imathelement) | Tar en specificerad funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/as_argument_of_function/#str) | Tar en specificerad funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsofoneargument) | Tar en specificerad funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar en specificerad funktion med detta objekt som argument och ett specificerat ytterligare argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar en specificerad funktion med detta objekt som argument och ett specificerat ytterligare argument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/set_subscript/#imathelement) | Skapar nedsänkt index |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/set_subscript/#str) | Skapar nedsänkt index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/set_superscript/#imathelement) | Skapar upphöjt index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/set_superscript/#str) | Skapar upphöjt index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar nedsänkt och upphöjt index till höger |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#str-str) | Skapar nedsänkt och upphöjt index till höger |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar nedsänkt och upphöjt index till vänster |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#str-str) | Skapar nedsänkt och upphöjt index till vänster |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/radical/#imathelement) | Specificerar den matematiska roten av given grad från det specificerade argumentet. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/radical/#str) | Specificerar den matematiska roten av given grad från det specificerade argumentet. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/set_lower_limit/#imathelement) | Tar nedre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/set_lower_limit/#str) | Tar nedre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-är operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-str-str) | Skapar en N-är operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralen |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str) | Tar integralen |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/group/#) | Placera detta element i en grupp med en nedre klammerparentes |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/group/#char-mathtopbotpositions-mathtopbotpositions) | Placera detta element i en grupp med ett grupperingstecken, så som nedre klammerparentes eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/to_border_box/#) | Placera detta element i en kantlåda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placera detta element i en kantlåda |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/to_math_array/#) | Sätter in i en vertikal matris |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/accent/#char) | Sätter ett accenttecken (ett tecken ovanpå detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/overbar/#) | Sätter ett streck ovanpå detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/underbar/#) | Sätter ett streck under detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/to_box/#) | Placera detta element i en icke-visuell ruta (logisk gruppering) <br/>            som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text.<br/>            Ett inramat objekt kan (till exempel) fungera som en operator-emulator med eller utan en justeringspunkt, <br/>            fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inte tillåts inom. |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit/get_children/#) | Hämta underordnade element |

### Se även
* klass [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)
* klass [`MathLimit`](/slides/python-net/sv/aspose.slides.mathtext/mathlimit)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)