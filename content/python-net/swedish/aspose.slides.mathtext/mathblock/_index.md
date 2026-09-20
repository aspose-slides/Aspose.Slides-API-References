---
title: MathBlock class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathblock/
---
## MathBlock klass

Specificerar en instans av matematisk text som finns i ett MathParagraph och börjar på en egen rad.
All matematiska områden, inklusive ekvationer, uttryck, matriser av ekvationer eller uttryck samt formler representeras av ett math block.

**Arv:**[`MathBlock`](/slides/python-net/sv/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)

MathBlock-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/__init__/#) | Initierar en ny instans av MathBlock klass. |
| [`__init__(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Skapar ett nytt matematiskt block och placerar angivet element i det |
| [`__init__(self, math_elements)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`count`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/count/) | Hämtar antalet underordnade matematiska element som faktiskt finns i samlingen.<br/>            Skrivskyddad **int**. |
| [`is_read_only`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/is_read_only/) | Returnerar false eftersom samlingen av underordnade element kan modifieras. |

Hämtar eller anger IMathElement på det angivna indexet.

## Indexer

| Namn | Beskrivning |
| :- | :- |
| [`[index]`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/__getitem__/) | Det nollbaserade indexet för objektet |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/join/#imathelement) | Kombinerar ett matematiskt element med detta matematiska block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/join/#str) | Kombinerar en matematisk text med detta matematiska block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/divide/#imathelement) | Skapar en bråkdel med detta täljare och angiven nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/divide/#str) | Skapar en bråkdel med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Skapar en bråkdel av den angivna typen med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Skapar en bråkdel av den angivna typen med detta täljare och angiven nämnare |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/enclose/#char-char) | Innesluter underordnade element i detta block med angivna tecken som parenteser eller andra tecken som ram |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | Innesluter underordnade element i detta block med angivna tecken som parenteser eller andra som ram<br/>            och avgränsar med ett separerande tecken |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/enclose/#) | Innesluter ett matematiskt element i parenteser |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/function/#imathelement) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/function/#str) | Tar en funktion av ett argument med detta objekt som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Tar angiven funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Tar angiven funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Tar angiven funktion med detta objekt som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar angiven funktion med detta objekt som argument och ett angivet ytterligare argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar angiven funktion med detta objekt som argument och ett angivet ytterligare argument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Skapar nedsänkt index |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/set_subscript/#str) | Skapar nedsänkt index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Skapar upphöjt index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/set_superscript/#str) | Skapar upphöjt index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar nedsänkt och upphöjt index på höger sida |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Skapar nedsänkt och upphöjt index på höger sida |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar nedsänkt och upphöjt index på vänster sida |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Skapar nedsänkt och upphöjt index på vänster sida |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/radical/#imathelement) | Anger det matematiska roten av given grad från det angivna argumentet. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/radical/#str) | Anger det matematiska roten av given grad från det angivna argumentet. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Tar nedre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Tar nedre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-är operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Skapar en N-är operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralen |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Tar integralen |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/group/#) | Placera detta element i en grupp med en nedre måsvinge |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Placera detta element i en grupp med ett grupperingstecken såsom nedre måsvinge eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/to_border_box/#) | Placera detta element i en ramruta |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placera detta element i en ramruta |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/to_math_array/#) | Sätter underordnade element i en vertikal matris |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/accent/#char) | Sätter ett accenttecken (ett tecken ovanpå detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/overbar/#) | Sätter en stapel ovanpå detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/underbar/#) | Sätter en stapel under detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/to_box/#) | Placera detta element i en icke-visuell ruta (logisk gruppering) <br/>            som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text.<br/>            Ett inramat objekt kan (till exempel) fungera som en operatoremulator med eller utan justeringspunkt, <br/>            fungera som en radbrytpunkt, eller grupperas så att radbrytningar inte tillåts inom den. |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/get_children/#) | Hämta underordnade element |
| [`add(self, item)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/add/#imathelement) | Lägger till ett matematiskt element i slutet av samlingen. |
| [`clear(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/clear/#) | Tar bort alla element från samlingen. |
| [`contains(self, item)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/contains/#imathelement) | Avgör om samlingen innehåller ett specifikt värde. |
| [`copy_to(self, array, array_index)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Kopiera till angiven array. |
| [`remove(self, item)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/remove/#imathelement) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [`index_of(self, item)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Avgör indexet för ett specifikt matematiskt element i samlingen. |
| [`insert(self, index, item)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Infogar ett MathElement i samlingen på det angivna indexet. |
| [`remove_at(self, index)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/remove_at/#int) | Tar bort elementet på det angivna indexet i samlingen. |
| [`join_block(self, other)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Kombinerar ett annat matematiskt block med detta |
| [`delimit(self, separator_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/delimit/#char) | Avgränsar underordnade element med separerande tecken (utan klamrar) |
| [`write_as_math_ml(self, stream)`](/slides/python-net/sv/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Sparar innehållet i denna [`MathBlock`](/slides/python-net/sv/aspose.slides.mathtext/mathblock) som MathML |

### Se också
* klass [`MathBlock`](/slides/python-net/sv/aspose.slides.mathtext/mathblock)
* klass [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)