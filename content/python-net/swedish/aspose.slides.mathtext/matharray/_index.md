---
title: MathArray class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/matharray/
---
## MathArray klass

Specificerar en vertikal matris av ekvationer eller andra matematiska objekt

**Arv:**[`MathArray`](/slides/python-net/sv/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)

MathArray-typen exponerar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/__init__/#imathelement) | Skapar en matematisk matris och placerar det specificerade elementet i den |
| [`__init__(self, elements)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`arguments`](/slides/python-net/sv/aspose.slides.mathtext/matharray/arguments/) | Mängden av element i matrisen |
| [`base_justification`](/slides/python-net/sv/aspose.slides.mathtext/matharray/base_justification/) | Anger justering av matrisen i förhållande till omgivande text<br/>            Text utanför matrisen kan justeras med botten, toppen eller mitten av ett matrisobjekt.<br/>            Standardvärde: Center |
| [`maximum_distribution`](/slides/python-net/sv/aspose.slides.mathtext/matharray/maximum_distribution/) | Maximal fördelning<br/>            När true, matrisen sprids till den maximala bredden av det innehållande elementet (sida, kolumn, cell etc.). |
| [`object_distribution`](/slides/python-net/sv/aspose.slides.mathtext/matharray/object_distribution/) | Objektfördelning<br/>            När true, innehållet i matrisen sprids till den maximala bredden av matrisobjektet. |
| [`row_spacing_rule`](/slides/python-net/sv/aspose.slides.mathtext/matharray/row_spacing_rule/) | Typen av vertikal avstånd mellan matrisens element<br/>            Standard: SingleLineGap |
| [`row_spacing`](/slides/python-net/sv/aspose.slides.mathtext/matharray/row_spacing/) | Avstånd mellan rader i en matris<br/>            Den används endast när RowSpacingRule är satt till 3 Exactly, i vilket fall måttenheten är punkter <br/>            eller Multiple, i vilket fall måttenheten är halvlinjer.<br/>            Standard: 0 |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/join/#imathelement) | Sammanfogar ett matematiskt element och bildar ett matematiskt block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/join/#str) | Sammanfogar ett matematiskt element och bildar ett matematiskt block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/divide/#imathelement) | Skapar ett bråk med detta täljare och specificerad nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/divide/#str) | Skapar ett bråk med detta täljare och specificerad nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | Skapar ett bråk av den specificerade typen med detta täljare och specificerad nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | Skapar ett bråk av den specificerade typen med detta täljare och specificerad nämnare |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/enclose/#) | Innesluter ett matematiskt element i parentes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/enclose/#char-char) | Innesluter ett matematiskt element i specificerade tecken såsom parentes eller andra tecken som ram |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/function/#imathelement) | Tar en funktion av ett argument med detta exemplar som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/function/#str) | Tar en funktion av ett argument med detta exemplar som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | Tar specificerad funktion med detta exemplar som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | Tar specificerad funktion med detta exemplar som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | Tar specificerad funktion med detta exemplar som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar specificerad funktion med detta exemplar som argument och specificerat extra argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar specificerad funktion med detta exemplar som argument och specificerat extra argument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | Skapar nedsänkt index |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/set_subscript/#str) | Skapar nedsänkt index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | Skapar upphöjd text |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/set_superscript/#str) | Skapar upphöjd text |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar nedsänkt och upphöjd text på högra sidan |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | Skapar nedsänkt och upphöjd text på högra sidan |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar nedsänkt och upphöjd text på vänstra sidan |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | Skapar nedsänkt och upphöjd text på vänstra sidan |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/radical/#imathelement) | Anger den matematiska roten av given grad från specificerat argument. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/radical/#str) | Anger den matematiska roten av given grad från specificerat argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | Tar undre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/set_lower_limit/#str) | Tar undre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-ary operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | Skapar en N-ary operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralen |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | Tar integralen |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/group/#) | Placera detta element i en grupp med en nedre klammerparentes |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | Placera detta element i en grupp med ett grupperande tecken såsom nedre klammerparentes eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/to_border_box/#) | Placera detta element i en kantlåda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placera detta element i en kantlåda |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/to_math_array/#) | Sätter in en vertikal matris |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/accent/#char) | Sätter ett accenttecken (ett tecken ovanpå detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/overbar/#) | Sätter ett streck ovanpå detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/underbar/#) | Sätter ett streck under detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/to_box/#) | Placera detta element i en icke-visuell ruta (logisk gruppering) <br/>            som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text.<br/>            Ett inramat objekt kan (till exempel) fungera som en operatoremulator med eller utan en justeringspunkt, <br/>            fungera som en radbrytpunkt, eller grupperas så att radbrytningar inte tillåts inom. |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/matharray/get_children/#) | Hämtar barnelement |

### Se även
* klass [`MathArray`](/slides/python-net/sv/aspose.slides.mathtext/matharray)
* klass [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)