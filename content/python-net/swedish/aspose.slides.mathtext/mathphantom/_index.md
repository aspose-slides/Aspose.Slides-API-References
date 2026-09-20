---
title: MathPhantom class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathphantom/
---
## MathPhantom klass

Representerar ett fantom-matematikobjekt (<m:phant>) som påverkar layouten för sitt underordnade element
            utan att nödvändigtvis visa det. Ett fantom kan dölja sitt grunduttryck samtidigt som det bevarar
            dess bredd, höjd eller djup för att justera formler eller reservera utrymme.
            Synlighet och geometribeteende styrs av egenskaper som Show, ZeroWid, ZeroAsc,
            ZeroDesc och Transp.

**Arv:**[`MathPhantom`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)

MathPhantom-typen exponerar följande medlemmar:

## Konstruktörer

| Konstruktör | Beskrivning |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | Initialiserar en ny instans av klassen [`MathPhantom`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom) <br/>            med det angivna basmatematiska elementet. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`base`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/base/) | Basargument |
| [`show`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/show/) | Hämtar eller anger ett värde som indikerar om baselementet visas. |
| [`zero_width`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/zero_width/) | Hämtar eller anger ett värde som indikerar om bredden på baselementet <br/>            ska behandlas som noll. |
| [`zero_asc`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/zero_asc/) | Hämtar eller anger ett värde som indikerar om uppstigningen (höjden över baslinjen) <br/>            för baselementet ska behandlas som noll. |
| [`zero_desc`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/zero_desc/) | Hämtar eller anger ett värde som indikerar om nedstigningen (djupet under baslinjen)<br/>            för baselementet ska behandlas som noll. |
| [`transp`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/transp/) | Hämtar eller anger ett värde som indikerar om fantomet är transparent <br/>            för klassbaserade avståndsregler. |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/join/#imathelement) | Kombinerar ett matematiskt element och bildar ett matematiskt block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/join/#str) | Kombinerar en matematisk text och bildar ett matematiskt block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/divide/#imathelement) | Skapar en bråk med detta täljare och angiven nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/divide/#str) | Skapar en bråk med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | Skapar en bråk av den angivna typen med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | Skapar en bråk av den angivna typen med detta täljare och angiven nämnare |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/enclose/#) | Omsluter ett matematiskt element i parentes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/enclose/#char-char) | Omsluter ett matematiskt element i angivna tecken såsom parentes eller andra tecken som ram |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/function/#imathelement) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/function/#str) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | Tar angiven funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | Tar angiven funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | Tar angiven funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar angiven funktion med detta objekt som argument och ett angivet extra argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar angiven funktion med detta objekt som argument och ett angivet extra argument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | Skapar nedsänkt text |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/set_subscript/#str) | Skapar nedsänkt text |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | Skapar upphöjd text |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/set_superscript/#str) | Skapar upphöjd text |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar nedsänkt och upphöjd text till höger |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | Skapar nedsänkt och upphöjd text till höger |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar nedsänkt och upphöjd text till vänster |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | Skapar nedsänkt och upphöjd text till vänster |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/radical/#imathelement) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/radical/#str) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | Tar nedre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | Tar nedre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-är operatör |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | Skapar en N-är operatör |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralen |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | Tar integralen |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/group/#) | Placera detta element i en grupp med en klammerparentes längst ner |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | Placera detta element i en grupp med ett grupperingstecken såsom en underkantig klammerparentes eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/to_border_box/#) | Placera detta element i en kantlåda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placera detta element i en kantlåda |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/to_math_array/#) | Sätter in en vertikal matris |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/accent/#char) | Sätter ett accenttecken (ett tecken ovanpå detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/overbar/#) | Sätter ett streck ovanpå detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/underbar/#) | Sätter ett streck under detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/to_box/#) | Placera detta element i en icke-visuell låda (logisk gruppering) <br/>            som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text.<br/>            Ett låst objekt kan (till exempel) fungera som en operatoremulärmedator med eller utan en justeringspunkt, <br/>            fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inte tillåts inom. |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom/get_children/#) | Hämta underordnade element |


### Se även
* klass [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)
* klass [`MathPhantom`](/slides/python-net/sv/aspose.slides.mathtext/mathphantom)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)