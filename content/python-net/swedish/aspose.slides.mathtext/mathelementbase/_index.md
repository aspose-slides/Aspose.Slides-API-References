---
title: MathElementBase class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase-klass

Bas-klass för IMathElement med implementeringen av vissa metoder som är gemensamma för alla ärvda klasser  
För internt bruk endast. Ärvd klass måste vara IMathElement.

MathElementBase-typen exponerar följande medlemmar:

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/join/#imathelement) | Kopplar ihop ett matematiskt element och bildar ett matematiskt block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/join/#str) | Kopplar ihop en matematisk text och bildar ett matematiskt block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/divide/#imathelement) | Skapar ett bråk med detta täljare och angiven nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/divide/#str) | Skapar ett bråk med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/divide/#imathelement-mathfractiontypes) | Skapar ett bråk av den specificerade typen med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/divide/#str-mathfractiontypes) | Skapar ett bråk av den specificerade typen med detta täljare och angiven nämnare |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/enclose/#) | Innesluter ett matematiskt element i parenteser |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/enclose/#char-char) | Innesluter ett matematiskt element i specificerade tecken, t.ex. parenteser eller andra tecken som ram |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/function/#imathelement) | Tar en funktion med ett argument där denna instans används som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/function/#str) | Tar en funktion med ett argument där denna instans används som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#imathelement) | Tar en specificerad funktion där denna instans används som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#str) | Tar en specificerad funktion där denna instans används som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsofoneargument) | Tar en specificerad funktion där denna instans används som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar en specificerad funktion där denna instans används som argument och ett specificerat ytterligare argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar en specificerad funktion där denna instans används som argument och ett specificerat ytterligare argument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/set_subscript/#imathelement) | Skapar ett nedre index |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/set_subscript/#str) | Skapar ett nedre index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/set_superscript/#imathelement) | Skapar ett upphöjt index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/set_superscript/#str) | Skapar ett upphöjt index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar nedre och upphöjt index på höger sida |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#str-str) | Skapar nedre och upphöjt index på höger sida |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar nedre och upphöjt index på vänster sida |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#str-str) | Skapar nedre och upphöjt index på vänster sida |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/radical/#imathelement) | Anger det matematiska roten av given grad från det specificerade argumentet. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/radical/#str) | Anger det matematiska roten av given grad från det specificerade argumentet. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/set_lower_limit/#imathelement) | Tar nedre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/set_lower_limit/#str) | Tar nedre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-är operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-str-str) | Skapar en N-är operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralen |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str) | Tar integralen |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/group/#) | Placera detta element i en grupp med en nedre klammerparentes |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/group/#char-mathtopbotpositions-mathtopbotpositions) | Placera detta element i en grupp med ett grupperings-tecken såsom en nedre klammerparentes eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/to_border_box/#) | Placera detta element i en kantruta |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placera detta element i en kantruta |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/to_math_array/#) | Sätter in en vertikal matris |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/accent/#char) | Sätter ett accenteringsmärke (ett tecken ovanför detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/overbar/#) | Sätter ett streck ovanpå detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/underbar/#) | Sätter ett streck under detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/to_box/#) | Placera detta element i en icke-visuell ruta (logisk gruppering) <br/> som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text.<br/> Ett inramat objekt kan (till exempel) fungera som en operatoremulator med eller utan en justeringspunkt, <br/> fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inte tillåts inom. |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase/get_children/#) |  |

### Se även
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)