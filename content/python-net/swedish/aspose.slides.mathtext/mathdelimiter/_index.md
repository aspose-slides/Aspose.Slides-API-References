---
title: MathDelimiter class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter-klass

Specificerar avgränsarobjektet, bestående av öppnings- och stängningstecken (såsom parenteser, klammerparenteser, hakparenteser och vertikala streck), samt ett eller flera matematiska element inuti, separerade av ett angivet tecken. Exempel: (𝑥2); [𝑥2|𝑦2]

**Arv:**[`MathDelimiter`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)

MathDelimiter-typen exponerar följande medlemmar:

## Constructors

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Initierar MathDelimiter med det angivna elementet som enda basargument |

## Properties

| Egenskap | Beskrivning |
| :- | :- |
| [`arguments`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/arguments/) | Ett eller flera matematiska element separerade av avgränsartecken |
| [`beginning_character`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character anger det inledande, eller öppnande, avgränsartecknet.<br/>Matematiska avgränsare är omslutande tecken såsom parenteser, hakparenteser och klammerparenteser.<br/>Standardvärdet: '('. |
| [`separator_character`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character anger tecknet som separerar argument i avgränsarobjektet.<br/>Standardvärdet: '\|'. |
| [`ending_character`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character anger det avslutande, eller stängande, avgränsartecknet.<br/>Matematiska avgränsare är omslutande tecken såsom parenteser, hakparenteser och klammerparenteser.<br/>Standardvärdet: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Anger tillväxten för BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>När true växer avgränsarna vertikalt för att matcha operandens höjd.<br/>Standardvärdet är true |
| [`delimiter_shape`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Anger formen på avgränsarna i avgränsarobjektet.<br/>När det är MathDelimiterShape.Centered är avgränsarna centrerade kring den matematiska axeln i den matematiska texten<br/>och anpassas för att fylla hela höjden på deras innehåll.<br/>När det är MathDelimiterShape.Match ändras deras höjd och form för att exakt matcha deras innehåll. |

## Methods

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Kombinerar ett matematiskt element och bildar ett matematiskt block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/join/#str) | Kombinerar en matematisk text och bildar ett matematiskt block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Skapar ett bråk med detta täljare och angivet nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/divide/#str) | Skapar ett bråk med detta täljare och angivet nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Skapar ett bråk av den angivna typen med detta täljare och angivet nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Skapar ett bråk av den angivna typen med detta täljare och angivet nämnare |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/enclose/#) | Innesluter ett matematikelement i parentes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Innesluter ett matematikelement i specificerade tecken såsom parentes eller andra tecken som ram |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Tar en funktion av ett argument där denna instans används som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/function/#str) | Tar en funktion av ett argument där denna instans används som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Tar angiven funktion där denna instans används som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Tar angiven funktion där denna instans används som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Tar angiven funktion där denna instans används som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar angiven funktion där denna instans används som argument samt ett specificerat ytterligare argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar angiven funktion där denna instans används som argument samt ett specificerat ytterligare argument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Skapar nedsänkt index |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Skapar nedsänkt index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Skapar upphöjd index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Skapar upphöjd index |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar nedsänkt och upphöjd index på höger sida |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Skapar nedsänkt och upphöjd index på höger sida |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar nedsänkt och upphöjd index på vänster sida |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Skapar nedsänkt och upphöjd index på vänster sida |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/radical/#str) | Anger den matematiska roten av given grad från det angivna argumentet. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Tar nedre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Tar nedre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-ärig operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | Skapar en N-ärig operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralen |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Tar integralen utan gränser |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/group/#) | Placera detta element i en grupp med en nedre måsvingeparentes |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Placera detta element i en grupp med ett grupperingstecken såsom nedre måsvingeparentes eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Placera detta element i en kantlåda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placera detta element i en kantlåda |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Sätter in en vertikal array |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/accent/#char) | Sätter ett accenttecken (ett tecken ovanpå detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/overbar/#) | Sätter ett streck över detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/underbar/#) | Sätter ett streck under detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/to_box/#) | Placera detta element i en icke-visuell låda (logisk gruppering)<br/>som används för att gruppera komponenter i en ekvation eller annan matematisk text.<br/>Ett låst objekt kan (till exempel) fungera som en operatoremulator med eller utan en justeringspunkt,<br/>fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inte tillåts inom den. |
| [`delimit(self, separator_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Avgränsar argument med det specificerade avgränsartecknet |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter/get_children/#) | Hämta underordnade element |

### Se även
* klass [`MathDelimiter`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter)
* klass [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)