---
title: MathematicalText class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText klass

Matematisk text

**Arv:**[`MathematicalText`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext) → [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)

MathematicalText-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/__init__/#) | Standardkonstruktor (skapa String.Empty-värde) |
| [`__init__(self, math_symbol)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/__init__/#char) | Skapa MathText med en enda symbol |
| [`__init__(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/__init__/#str) | Skapa MathematicalText från text |
| [`__init__(self, math_text, portion_format)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/__init__/#str-iportionformat) | Skapa MathematicalText från text och formatinställningar |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`value`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/value/) | Textvärde |
| [`format`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/format/) | Egenskaper för textformatering |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/join/#imathelement) | Kombinerar ett matematiskt element och bildar ett matematiskt block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/join/#str) | Kombinerar en matematisk text och bildar ett matematiskt block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/divide/#imathelement) | Skapar ett bråk med detta täljare och angiven nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/divide/#str) | Skapar ett bråk med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/divide/#imathelement-mathfractiontypes) | Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/divide/#str-mathfractiontypes) | Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/enclose/#) | Innesluter ett matematiskt element i parentes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/enclose/#char-char) | Innesluter ett matematiskt element i specificerade tecken såsom parentes eller andra tecken som ram |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/function/#imathelement) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/function/#str) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#imathelement) | Tar en specificerad funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#str) | Tar en specificerad funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsofoneargument) | Tar en specificerad funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar en specificerad funktion med detta objekt som argument och ett specificerat ytterligare argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar en specificerad funktion med detta objekt som argument och ett specificerat ytterligare argument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/set_subscript/#imathelement) | Skapar nedsänkt |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/set_subscript/#str) | Skapar nedsänkt |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/set_superscript/#imathelement) | Skapar upphöjt |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/set_superscript/#str) | Skapar upphöjt |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar nedsänkt och upphöjt på höger sida |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#str-str) | Skapar nedsänkt och upphöjt på höger sida |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar nedsänkt och upphöjt på vänster sida |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#str-str) | Skapar nedsänkt och upphöjt på vänster sida |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/radical/#imathelement) | Anger den matematiska roten av given grad från det specificerade argumentet. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/radical/#str) | Anger den matematiska roten av given grad från det specificerade argumentet. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#imathelement) | Tar nedre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#str) | Tar nedre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-är operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-str-str) | Skapar en N-är operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralen |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str) | Tar integralen |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/group/#) | Placera detta element i en grupp med en nedre klammerparentes |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/group/#char-mathtopbotpositions-mathtopbotpositions) | Placera detta element i en grupp med ett grupperingstecken såsom nedre klammerparentes eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/to_border_box/#) | Placera detta element i en ramruta |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placera detta element i en ramruta |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/to_math_array/#) | Sätter in en vertikal matris |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/accent/#char) | Sätter ett accenttecken (ett tecken ovanpå detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/overbar/#) | Sätter en linje ovanpå detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/underbar/#) | Sätter en linje under detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/to_box/#) | Placera detta element i en icke-visuell ruta (logisk gruppering) <br/>            som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text.<br/>            Ett inramat objekt kan (till exempel) fungera som en operator-emulator med eller utan en justeringspunkt, <br/>            fungera som en radbrytning, eller grupperas så att radbrytningar inte tillåts inom. |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext/get_children/#) |  |

### Se också
* klass [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)
* klass [`MathematicalText`](/slides/python-net/sv/aspose.slides.mathtext/mathematicaltext)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)