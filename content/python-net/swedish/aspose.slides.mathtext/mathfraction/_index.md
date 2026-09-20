---
title: MathFraction class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathfraction/
---
## MathFraction klass

Specificerar fraktionobjektet, bestående av en täljare och en nämnare separerade av ett bråkstreck.
            Bråkstrecket kan vara horisontellt eller diagonalt, beroende på bråkegenskaperna.
            Fraktionobjektet används också för att representera stack-funktionen, som placerar ett element ovanpå ett annat, utan bråkstreck.

**Arv:**[`MathFraction`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction) → [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)

MathFraction-typen exponerar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, numerator, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement-mathfractiontypes) | Initialiserar MathFraction med angiven täljare, nämnare och typ |
| [`__init__(self, numerator, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement) | Initialiserar ett MathFraction av typen 'Bar' med angiven täljare och nämnare |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`fraction_type`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/fraction_type/) | Fraktionstyp<br/>            Standard: Bar |
| [`numerator`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/numerator/) | Täljare |
| [`denominator`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/denominator/) | Nämnare |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/join/#imathelement) | Sammanfogar ett matematiskt element och bildar ett matematiskt block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/join/#str) | Sammanfogar en matematisk text och bildar ett matematiskt block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/divide/#imathelement) | Skapar ett bråk med denna täljare och angiven nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/divide/#str) | Skapar ett bråk med denna täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/divide/#imathelement-mathfractiontypes) | Skapar ett bråk av den angivna typen med denna täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/divide/#str-mathfractiontypes) | Skapar ett bråk av den angivna typen med denna täljare och angiven nämnare |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/enclose/#) | Inramar ett matematiskt element i parentes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/enclose/#char-char) | Inramar ett matematiskt element i specificerade tecken, såsom parentes eller andra inramningstecken |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/function/#imathelement) | Tar en funktion av ett argument där denna instans används som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/function/#str) | Tar en funktion av ett argument där denna instans används som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/as_argument_of_function/#imathelement) | Tar en specificerad funktion där denna instans används som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/as_argument_of_function/#str) | Tar en specificerad funktion där denna instans används som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsofoneargument) | Tar en specificerad funktion där denna instans används som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar en specificerad funktion där denna instans används som argument och ett specificerat extra argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar en specificerad funktion där denna instans används som argument och ett specificerat extra argument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/set_subscript/#imathelement) | Skapar nedsänkt index |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/set_subscript/#str) | Skapar nedsänkt index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/set_superscript/#imathelement) | Skapar upphöjt index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/set_superscript/#str) | Skapar upphöjt index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar nedsänkt och upphöjt index till höger |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#str-str) | Skapar nedsänkt och upphöjt index till höger |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar nedsänkt och upphöjt index till vänster |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#str-str) | Skapar nedsänkt och upphöjt index till vänster |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/radical/#imathelement) | Anger den matematiska roten av given grad från det specificerade argumentet. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/radical/#str) | Anger den matematiska roten av given grad från det specificerade argumentet. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/set_lower_limit/#imathelement) | Tar nedre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/set_lower_limit/#str) | Tar nedre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-är operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-str-str) | Skapar en N-är operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralen |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str) | Tar integralen |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/group/#) | Placerar detta element i en grupp med en nedre klammerparentes |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/group/#char-mathtopbotpositions-mathtopbotpositions) | Placerar detta element i en grupp med ett grupperande tecken, såsom en nedre klammerparentes eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/to_border_box/#) | Placerar detta element i en kant-ruta |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placerar detta element i en kant-ruta |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/to_math_array/#) | Lägg in i en vertikal matris |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/accent/#char) | Sätter ett accenteringsmärke (ett tecken ovanpå detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/overbar/#) | Sätter ett streck överst på detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/underbar/#) | Sätter ett streck nederst på detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/to_box/#) | Placerar detta element i en icke-visuell ruta (logisk gruppering) <br/>            som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text.<br/>            Ett inramat objekt kan (till exempel) fungera som en operatoremulator med eller utan justeringspunkt, <br/>            fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inte tillåts inom. |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction/get_children/#) | Hämta underordnade element |

### Se också
* klass [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)
* klass [`MathFraction`](/slides/python-net/sv/aspose.slides.mathtext/mathfraction)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)