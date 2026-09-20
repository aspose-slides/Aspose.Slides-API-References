---
title: MathGroupingCharacter class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter klass

Anger en grupperingstecken ovanför eller under ett uttryck, vanligtvis för att framhäva förhållandet mellan elementen

**Arv:**[`MathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)

MathGroupingCharacter-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | Initierar en ny instans av MathGroupingCharacter-klass <br/>            med standardgrupperingstecken U+23DF (BOTTOM CURLY BRACKET) |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | Initierar en ny instans av MathGroupingCharacter-klass. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`base`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/base/) | Basargument |
| [`character`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/character/) | Grupperingstecken<br/>            Standardvärde: U+23DF (BOTTOM CURLY BRACKET) |
| [`position`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/position/) | Position för gruppningstecken.<br/>            Standard: Bottom |
| [`vertical_justification`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | Vertikal justering av grupptecken.<br/>            Anger objektets justering i förhållande till baslinjen.<br/>            Till exempel, när grupptecknet är ovanför objektet, <br/>            VerticalJustification av Top betyder att objektets topp ligger på baslinjen;<br/>            när VerticalJustification är satt till Bottom, ligger objektets botten på baslinjen<br/>            Standard: Bottom för Position=Top, och Top för Position=Bottom |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | Kombinerar ett matematiskt element och bildar ett matematiskt block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | Kombinerar en matematisk text och bildar ett matematiskt block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | Skapar en bråk med detta täljare och angiven nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | Skapar en bråk med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | Skapar en bråk av den angivna typen med detta täljare och specificerad nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | Skapar en bråk av den angivna typen med detta täljare och specificerad nämnare |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | Innesluter ett matematiskt element i parentes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | Innesluter ett matematiskt element i angivna tecken såsom parentes eller andra tecken som ram |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | Tar en funktion av ett argument med denna instans som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | Tar en funktion av ett argument med denna instans som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | Tar specificerad funktion med denna instans som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | Tar specificerad funktion med denna instans som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | Tar specificerad funktion med denna instans som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar specificerad funktion med denna instans som argument och ett specificerat tilläggsargument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar specificerad funktion med denna instans som argument och ett specificerat tilläggsargument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | Skapar nedsänkt |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | Skapar nedsänkt |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | Skapar upphöjd |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | Skapar upphöjd |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar nedsänkt och upphöjd på höger sida |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | Skapar nedsänkt och upphöjd på högersida |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar nedsänkt och upphöjd på vänster sida |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | Skapar nedsänkt och upphöjd på vänstersida |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | Anger det matematiska roten av given grad från det angivna argumentet. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | Anger det matematiska roten av given grad från det angivna argumentet. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | Tar nedre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | Tar nedre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-är operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | Skapar en N-är operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralet |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralet |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | Tar integralet utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralet |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | Tar integralet |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/group/#) | Placera detta element i en grupp med en nedre krullparentes |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | Placera detta element i en grupp med ett grupptecken såsom nedre krullparentes eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | Placera detta element i en kantlåda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placera detta element i en kantlåda |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | Sätter in en vertikal matris |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | Ställer in ett accenttecken (ett tecken ovanpå detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | Sätter ett streck ovanför detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | Sätter ett streck under detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | Placera detta element i en icke-visuell ruta (logisk gruppering) <br/>            som används för att gruppera komponenter i en ekvation eller annan matematisk text.<br/>            Ett inramat objekt kan (till exempel) fungera som en operatoremulator med eller utan en justeringspunkt, <br/>            fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inte tillåts inom. |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | Hämta underordnade element |

### Se även
* klass [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)
* klass [`MathGroupingCharacter`](/slides/python-net/sv/aspose.slides.mathtext/mathgroupingcharacter)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)