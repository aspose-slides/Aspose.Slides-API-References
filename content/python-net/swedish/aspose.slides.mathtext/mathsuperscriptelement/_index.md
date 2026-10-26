---
title: MathSuperscriptElement class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathsuperscriptelement/
---
## MathSuperscriptElement klass

Specificerar superskriptobjektet, som består av ett basobjekt 
            och ett förminskat superskript placerat ovanför och till höger

**Arv:**[`MathSuperscriptElement`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement) → [`BaseScript`](/slides/python-net/sv/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)

Typen MathSuperscriptElement exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, base_arg, super_script)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/__init__/#imathelement-imathelement) | Initialiserar en ny instans av MathSuperscriptElement-klassen. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`base`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/base/) | Basargument |
| [`superscript`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/superscript/) | Superskript |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/join/#imathelement) | Kopplar ihop ett matematiskt element och bildar ett matematiskt block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/join/#str) | Kopplar ihop en matematisk text och bildar ett matematiskt block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/divide/#imathelement) | Skapar ett bråk med detta täljare och angiven nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/divide/#str) | Skapar ett bråk med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/divide/#imathelement-mathfractiontypes) | Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/divide/#str-mathfractiontypes) | Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/enclose/#) | Innesluter ett matematiskt element i parentes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/enclose/#char-char) | Innesluter ett matematiskt element i angivna tecken, såsom parentes eller andra tecken som ram |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/function/#imathelement) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/function/#str) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#imathelement) | Tar en angiven funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#str) | Tar en angiven funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Tar en angiven funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar en angiven funktion med detta objekt som argument och angivet ytterligare argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar en angiven funktion med detta objekt som argument och angivet ytterligare argument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/set_subscript/#imathelement) | Skapar nedsänkt index |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/set_subscript/#str) | Skapar nedsänkt index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/set_superscript/#imathelement) | Skapar upphöjt index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/set_superscript/#str) | Skapar upphöjt index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar nedsänkt och upphöjt index på höger sida |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | Skapar nedsänkt och upphöjt index på höger sida |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar nedsänkt och upphöjt index på vänster sida |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | Skapar nedsänkt och upphöjt index på vänster sida |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/radical/#imathelement) | Specificerar den matematiska roten av given grad från angivet argument. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/radical/#str) | Specificerar den matematiska roten av given grad från angivet argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/set_lower_limit/#imathelement) | Tar nedre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/set_lower_limit/#str) | Tar nedre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-är operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | Skapar en N-är operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralen |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-str-str) | Tar integralen |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/group/#) | Placera detta element i en grupp med en nedre klammerparentes |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Placera detta element i en grupp med ett grupperingstecken, såsom nedre klammerparentes eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/to_border_box/#) | Placera detta element i en kantlåda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placera detta element i en kantlåda |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/to_math_array/#) | Sätter in i en vertikal matris |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/accent/#char) | Ställer in en accent (ett tecken ovanpå detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/overbar/#) | Ställer in en strecklinje ovanpå detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/underbar/#) | Ställer in en strecklinje under detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/to_box/#) | Placera detta element i en icke-visuell ruta (logisk gruppering) <br/>            som används för att gruppera komponenter i en ekvation eller annan matematisk text.<br/>            Ett inramat objekt kan (till exempel) fungera som en operatoremulator med eller utan en justeringspunkt, <br/>            fungera som en radbrytning eller grupperas så att radbrytningar inte tillåts inom. |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement/get_children/#) | Hämta underordnade element |


### Se även
* klass [`BaseScript`](/slides/python-net/sv/aspose.slides.mathtext/basescript)
* klass [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)
* klass [`MathSuperscriptElement`](/slides/python-net/sv/aspose.slides.mathtext/mathsuperscriptelement)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)