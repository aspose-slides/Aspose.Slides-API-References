---
title: MathBorderBox class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox klass

Ritar en rektangulär eller annan ram runt IMathElement.

**Arv:**[`MathBorderBox`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox) → [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)

MathBorderBox-typen exponerar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/__init__/#imathelement) | Skapar ett MathBorderBox-element med rektangulär ram |
| [`__init__(self, element, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/__init__/#imathelement-bool-bool-bool-bool-bool-bool-bool-bool) | Skapar ett MathBorderBox-element |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`base`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/base/) | Basargument |
| [`hide_top`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/hide_top/) | Dölj övre kant (standard är falskt) - anger den dolda eller visade statusen för den övre kanten på ramboxen. |
| [`hide_bottom`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/hide_bottom/) | Dölj nedre kant (standard är falskt) - anger den dolda eller visade statusen för den nedre kanten på ramboxen. |
| [`hide_left`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/hide_left/) | Dölj vänster kant (standard är falskt) - anger den dolda eller visade statusen för den vänstra kanten på ramboxen. |
| [`hide_right`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/hide_right/) | Dölj högra kant (standard är falskt) - anger den dolda eller visade statusen för den högra kanten på ramboxen. |
| [`strikethrough_horizontal`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/strikethrough_horizontal/) | Genomstrykning horisontell (standard är falskt) - anger den dolda eller visade statusen för en genomstruken horisontell linje. |
| [`strikethrough_vertical`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/strikethrough_vertical/) | Genomstrykning vertikal (standard är falskt) - anger den dolda eller visade statusen för en genomstruken vertikal linje. |
| [`strikethrough_bottom_left_to_top_right`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/strikethrough_bottom_left_to_top_right/) | Genomstrykning nedre vänster till övre högra (standard är falskt).<br/>            Anger den dolda eller visade statusen för en genomstruken diagonal linje från det nedre vänstra hörnet till det övre högra hörnet på ramboxen. |
| [`strikethrough_top_left_to_bottom_right`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/strikethrough_top_left_to_bottom_right/) | Genomstrykning övre vänster till nedre högra (standard är falskt).<br/>            Anger den dolda eller visade statusen för en genomstruken diagonal linje från det övre vänstra hörnet till det nedre högra hörnet på ramboxen. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/join/#imathelement) | Kombinerar ett matematiskt element och bildar ett matematiskt block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/join/#str) | Kombinerar en matematisk text och bildar ett matematiskt block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/divide/#imathelement) | Skapar en bråkdel med detta täljare och angiven nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/divide/#str) | Skapar en bråkdel med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/divide/#imathelement-mathfractiontypes) | Skapar en bråkdel av angiven typ med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/divide/#str-mathfractiontypes) | Skapar en bråkdel av angiven typ med detta täljare och angiven nämnare |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/enclose/#) | Innesluter ett matematikelement i parentes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/enclose/#char-char) | Innesluter ett matematikelement i angivna tecken såsom parentes eller andra tecken som ram |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/function/#imathelement) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/function/#str) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#imathelement) | Tar angiven funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#str) | Tar angiven funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsofoneargument) | Tar angiven funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar angiven funktion med detta objekt som argument och angivet ytterligare argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar angiven funktion med detta objekt som argument och angivet ytterligare argument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/set_subscript/#imathelement) | Skapar nedsänkt index |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/set_subscript/#str) | Skapar nedsänkt index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/set_superscript/#imathelement) | Skapar upphöjt index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/set_superscript/#str) | Skapar upphöjt index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar nedsänkt och upphöjt index på höger sida |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#str-str) | Skapar nedsänkt och upphöjt index på höger sida |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar nedsänkt och upphöjt index på vänster sida |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#str-str) | Skapar nedsänkt och upphöjt index på vänster sida |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/radical/#imathelement) | Anger den matematiska roten av given grad från angivet argument. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/radical/#str) | Anger den matematiska roten av given grad från angivet argument. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/set_lower_limit/#imathelement) | Tar nedre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/set_lower_limit/#str) | Tar nedre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-är operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-str-str) | Skapar en N-är operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralen |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str) | Tar integralen |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/group/#) | Placera detta element i en grupp med en nedre klammerparentes |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Placera detta element i en grupp med ett grupperingstecken såsom nedre klammerparentes eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/to_border_box/#) | Placera detta element i en rambox |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placera detta element i en rambox |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/to_math_array/#) | Sätter in en vertikal matris |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/accent/#char) | Ställer in ett accenttecken (ett tecken ovanför detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/overbar/#) | Ställer in ett streck ovanpå detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/underbar/#) | Ställer in ett streck under detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/to_box/#) | Placera detta element i en icke-visuell box (logisk gruppering) <br/>            som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text.<br/>            Ett inramat objekt kan (till exempel) fungera som en operatoremulådere utan eller med en justeringspunkt, <br/>            fungera som en radbrytpunkt, eller grupperas så att radbrytningar inte tillåts inom. |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox/get_children/#) | Hämta underordnade element |


### Se även
* klass [`MathBorderBox`](/slides/python-net/sv/aspose.slides.mathtext/mathborderbox)
* klass [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)