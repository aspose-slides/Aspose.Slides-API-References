---
title: MathBar class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathbar/
---
## MathBar-klass

Anger bar-funktionen, bestående av ett basargument och ett över- eller understreck

**Arv:**[`MathBar`](/slides/python-net/sv/aspose.slides.mathtext/mathbar) → [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)

Typen MathBar exponerar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/__init__/#imathelement) | Initierar MathBar med överstreck (Topposition) |
| [`__init__(self, element, position)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/__init__/#imathelement-mathtopbotpositions) | Initierar MathBar med specificerad position |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`base`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/base/) | Basargument |
| [`position`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/position/) | Position för stapellinjen. <br/>            Standard: Topp |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/join/#imathelement) | Innesluter ett matematiskt element och bildar ett matematiskt block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/join/#str) | Innesluter en matematisk text och bildar ett matematiskt block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/divide/#imathelement) | Skapar ett bråk med detta täljare och specificerad nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/divide/#str) | Skapar ett bråk med detta täljare och specificerad nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/divide/#imathelement-mathfractiontypes) | Skapar ett bråk av given typ med detta täljare och specificerad nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/divide/#str-mathfractiontypes) | Skapar ett bråk av given typ med detta täljare och specificerad nämnare |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/enclose/#) | Innesluter ett matematiskt element i parentes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/enclose/#char-char) | Innesluter ett matematiskt element i specificerade tecken såsom parentes eller andra tecken som ram |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/function/#imathelement) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/function/#str) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/as_argument_of_function/#imathelement) | Tar specificerad funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/as_argument_of_function/#str) | Tar specificerad funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsofoneargument) | Tar specificerad funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar specificerad funktion med detta objekt som argument och angivet ytterligare argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar specificerad funktion med detta objekt som argument och angivet ytterligare argument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/set_subscript/#imathelement) | Skapar nedsänkt |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/set_subscript/#str) | Skapar nedsänkt |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/set_superscript/#imathelement) | Skapar upphöjd |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/set_superscript/#str) | Skapar upphöjd |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar nedsänkt och upphöjd till höger |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_right/#str-str) | Skapar nedsänkt och upphöjd till höger |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar nedsänkt och upphöjd till vänster |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/set_sub_superscript_on_the_left/#str-str) | Skapar nedsänkt och upphöjd till vänster |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/radical/#imathelement) | Anger den matematiska roten av given grad från angivet argument. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/radical/#str) | Anger den matematiska roten av given grad från angivet argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/set_lower_limit/#imathelement) | Tar nedre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/set_lower_limit/#str) | Tar nedre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-är operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/nary/#mathnaryoperatortypes-str-str) | Skapar en N-är operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralen |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/integral/#mathintegraltypes-str-str) | Tar integralen |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/group/#) | Placera detta element i en grupp med en klammerparentes längst ner |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/group/#char-mathtopbotpositions-mathtopbotpositions) | Placera detta element i en grupp med ett grupperingstecken såsom klammerparentes eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/to_border_box/#) | Placera detta element i en kantlåda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placera detta element i en kantlåda |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/to_math_array/#) | Sätter in i en vertikal matris |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/accent/#char) | Ställer in ett accenttecken (ett tecken ovanför detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/overbar/#) | Ställer in ett streck ovanpå detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/underbar/#) | Ställer in ett streck under detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/to_box/#) | Placera detta element i en icke-visuell låda (logisk gruppering) <br/>            som används för att gruppera komponenter i en ekvation eller annat matematiskt textavsnitt.<br/>            En lådad objekt kan (till exempel) fungera som en operator-emulator med eller utan justeringspunkt, <br/>            fungera som en radbrytpunkt, eller grupperas så att radbrytningar inte tillåts inom den. |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathbar/get_children/#) | Hämta underordnade element |

### Se även
* klass [`MathBar`](/slides/python-net/sv/aspose.slides.mathtext/mathbar)
* klass [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)