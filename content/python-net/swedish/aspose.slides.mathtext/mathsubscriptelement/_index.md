---
title: MathSubscriptElement class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathsubscriptelement/
---
## MathSubscriptElement klass

Specificerar subskriptobjektet, som består av en bas och ett nedsänkt index i reducerad storlek placerat under och till höger.

**Arv:**[`MathSubscriptElement`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement) → [`BaseScript`](/slides/python-net/sv/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)

MathSubscriptElement-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, base_arg, sub_script)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/__init__/#imathelement-imathelement) | Initierar en ny instans av MathSubscriptElement-klass. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`base`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/base/) | Basargument |
| [`subscript`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/subscript/) | Nedsänkt index |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/join/#imathelement) | Sammanfogar ett matematiskt element och bildar ett matematiskt block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/join/#str) | Sammanfogar en matematisk text och bildar ett matematiskt block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/divide/#imathelement) | Skapar en bråkdel med detta täljare och angivet nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/divide/#str) | Skapar en bråkdel med detta täljare och angivet nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/divide/#imathelement-mathfractiontypes) | Skapar en bråkdel av angiven typ med detta täljare och angivet nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/divide/#str-mathfractiontypes) | Skapar en bråkdel av angiven typ med detta täljare och angivet nämnare |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/enclose/#) | Innesluter ett matematiskt element i parentes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/enclose/#char-char) | Innesluter ett matematiskt element i angivna tecken såsom parentes eller andra tecken som ram |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/function/#imathelement) | Tar en funktion av ett argument med denna instans som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/function/#str) | Tar en funktion av ett argument med denna instans som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#imathelement) | Tar angiven funktion med denna instans som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#str) | Tar angiven funktion med denna instans som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Tar angiven funktion med denna instans som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar angiven funktion med denna instans som argument och angivet ytterligare argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar angiven funktion med denna instans som argument och angivet ytterligare argument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/set_subscript/#imathelement) | Skapar nedsänkt index |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/set_subscript/#str) | Skapar nedsänkt index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/set_superscript/#imathelement) | Skapar upphöjt index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/set_superscript/#str) | Skapar upphöjt index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar nedsänkt och upphöjt index till höger |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_right/#str-str) | Skapar nedsänkt och upphöjt index till höger |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar nedsänkt och upphöjt index till vänster |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_left/#str-str) | Skapar nedsänkt och upphöjt index till vänster |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/radical/#imathelement) | Anger den matematiska roten av angiven grad från det specificerade argumentet. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/radical/#str) | Anger den matematiska roten av angiven grad från det specificerade argumentet. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/set_lower_limit/#imathelement) | Tar nedre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/set_lower_limit/#str) | Tar nedre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-är operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/nary/#mathnaryoperatortypes-str-str) | Skapar en N-är operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralen |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-str-str) | Tar integralen |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/group/#) | Placera detta element i en grupp med en nedre måsvinge |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Placera detta element i en grupp med ett grupperingstecken såsom nedre måsvinge eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/to_border_box/#) | Placera detta element i en kantruta |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placera detta element i en kantruta |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/to_math_array/#) | Sätter in en vertikal matris |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/accent/#char) | Ställer in ett accenttecken (ett tecken ovanpå detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/overbar/#) | Ställer in ett streck över detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/underbar/#) | Ställer in ett streck under detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/to_box/#) | Placera detta element i en icke-visuell ruta (logisk gruppering) <br/>            som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text.<br/>            Ett inramat objekt kan (till exempel) fungera som en operatoremulator med eller utan en justeringspunkt, <br/>            fungera som ett radbrytningsställe, eller grupperas så att radbrytningar inte tillåts inom. |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement/get_children/#) | Hämta underordnade element |

### Se också
* klass [`BaseScript`](/slides/python-net/sv/aspose.slides.mathtext/basescript)
* klass [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)
* klass [`MathSubscriptElement`](/slides/python-net/sv/aspose.slides.mathtext/mathsubscriptelement)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)