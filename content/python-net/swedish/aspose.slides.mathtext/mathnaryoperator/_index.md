---
title: MathNaryOperator class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator klass

Specificerar ett N-ärt matematiskt objekt, såsom Summation och Integral.  
Det består av en operator, en bas (eller operand), och valfria övre och nedre gränser.  
Exempel på N-ära operatorer är: Summation, Union, Intersection, Integral

**Arv:**[`MathNaryOperator`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)

MathNaryOperator-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | Initierar en ny instans av MathNaryOperator-klassen. |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | Initierar en ny instans av MathNaryOperator-klassen. |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | Initierar en ny instans av MathNaryOperator-klassen. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`base`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/base/) | Basargument |
| [`subscript`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/subscript/) | Specificerar ett indexargument som exempelvis i fallet med en integral sätter den nedre gränsen |
| [`superscript`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/superscript/) | Specificerar ett upphöjt argument som exempelvis i fallet med en integral sätter den övre gränsen |
| [`operator`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/operator/) | N-ärig operator-tecken<br/>            Till exempel: '∑', '∫' |
| [`limit_location`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/limit_location/) | Placeringen av gränserna (index och upphöjt) |
| [`grow_to_match_operand_height`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | Operator-tecknet växer vertikalt för att matcha operandens höjd |
| [`hide_subscript`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | Dölj index |
| [`hide_superscript`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | Dölj upphöjt |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | Kombinerar ett matematiskt element och bildar ett matematiskt block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/join/#str) | Kombinerar en matematisk text och bildar ett matematiskt block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | Skapar en bråk med detta täljare och specificerad nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/divide/#str) | Skapar en bråk med detta täljare och specificerad nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | Skapar en bråk av den specificerade typen med detta täljare och specificerad nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | Skapar en bråk av den specificerade typen med detta täljare och specificerad nämnare |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/enclose/#) | Innesluter ett matematiskt element i parentes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | Innesluter ett matematiskt element i specificerade tecken såsom parentes eller andra tecken som ram |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | Tar en funktion av ett argument med denna instans som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/function/#str) | Tar en funktion av ett argument med denna instans som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | Tar specificerad funktion med denna instans som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | Tar specificerad funktion med denna instans som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | Tar specificerad funktion med denna instans som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar specificerad funktion med denna instans som argument och specificerat ytterligare argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar specificerad funktion med denna instans som argument och specificerat ytterligare argument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | Skapar index |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | Skapar index |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | Skapar upphöjt |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | Skapar upphöjt |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar index och upphöjt till höger |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | Skapar index och upphöjt till höger |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar index och upphöjt till vänster |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | Skapar index och upphöjt till vänster |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | Specificerar den matematiska roten av given grad från det specificerade argumentet. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/radical/#str) | Specificerar den matematiska roten av given grad från det specificerade argumentet. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | Tar nedre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | Tar nedre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-ärig operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | Skapar en N-ärig operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralen |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | Tar integralen |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/group/#) | Placera detta element i en grupp med en nedre måsvinge |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | Placera detta element i en grupp med ett grupperingstecken såsom nedre måsvinge eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | Placera detta element i en kantlåda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placera detta element i en kantlåda |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | Sätter in en vertikal matris |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/accent/#char) | Ställer in ett accenttecken (ett tecken ovanpå detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/overbar/#) | Ställer in ett streck ovanpå detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/underbar/#) | Ställer in ett streck under detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/to_box/#) | Placera detta element i en icke-visuell låda (logisk gruppering) <br/>            som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text.<br/>            Ett inramat objekt kan (till exempel) fungera som en operator-emulator med eller utan en justeringspunkt, <br/>            fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inte tillåts inom. |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator/get_children/#) | Hämta underordnade element |

### Se även
* klass [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)
* klass [`MathNaryOperator`](/slides/python-net/sv/aspose.slides.mathtext/mathnaryoperator)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)