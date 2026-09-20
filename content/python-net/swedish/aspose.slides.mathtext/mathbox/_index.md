---
title: MathBox class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathbox/
---
## MathBox klass

Specificerar den logiska boxningen (paketeringen) av ett matematiskt element.
            Till exempel kan ett inramat objekt fungera som en operator-emulator med eller utan en justeringspunkt, 
            fungera som en radbrytpunkten, eller grupperas så att radbrytningar inte tillåts inom det.
            Till exempel bör operatorn "==" boxas för att förhindra radbrytningar.

**Inheritance:**[`MathBox`](/slides/python-net/sv/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)

MathBox-typen exponerar följande medlemmar:

## Konstruktörer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/__init__/#imathelement) | Initierar MathBox med det specificerade elementet som argument |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`base`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/base/) | Basargument |
| [`operator_emulator`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/operator_emulator/) | Operator-emulator.<br/>            När true beter sig rutan och dess innehåll som en enda operator och ärver egenskaperna hos en operator. <br/>            Detta innebär till exempel att tecknet kan fungera som en punkt för ett radbryt och kan justeras till andra operatorer.<br/>            Operator-emulatorer används ofta när ett eller flera glyffer kombineras för att bilda en operator, såsom '=='.<br/>            Standardvärde: false |
| [`no_break`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/no_break/) | Ingen brytning<br/>            Denna egenskap specificerar egenskapen "unbreakable" på objektets ruta. När true kan inga radbrytningar inträffa inom rutan.<br/>            Detta kan vara viktigt för operator-emulatorer som består av mer än en binär operator. <br/>            När detta element inte är specificerat kan brytningar inträffa i rutan.<br/>            Standard: true |
| [`differential`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/differential/) | Differential<br/>            När true fungerar rutan som en differential (t.ex. 𝑑𝑥 i en integrand), och får lämplig <br/>            horisontell avstånd för den matematiska differentialen.<br/>            Standard: false |
| [`alignment_point`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/alignment_point/) | När true fungerar denna operator-emulator som en justeringspunkt; det vill säga, <br/>            utsedda justeringspunkter i andra ekvationer kan justeras med den.<br/>            Standard: false |
| [`explicit_break`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/explicit_break/) | Explicit brytning anger om det finns ett radbryt i början av Box-objektet, <br/>            så att raden bryts vid början av box-objektet.<br/>            Anger numret på operatorn på föregående rad med matematisk text som ska<br/>            användas som justeringspunkt för den aktuella raden med matematisk text<br/>            möjliga värden: 1..255<br/>            Standard: 0 (ingen explicit brytning) |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/join/#imathelement) | Sammanfogar ett matematiskt element och bildar ett matematiskt block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/join/#str) | Sammanfogar ett matematiskt element och bildar ett matematiskt block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/divide/#imathelement) | Skapar ett bråk med detta täljare och angiven nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/divide/#str) | Skapar ett bråk med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | Skapar ett bråk av den angivna typen med detta täljare och angiven nämnare |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/enclose/#) | Omger ett matematiskt element med parenteser |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/enclose/#char-char) | Omger ett matematiskt element med specificerade tecken, såsom parenteser eller andra tecken som ram |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/function/#imathelement) | Tar en funktion av ett argument där detta element används som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/function/#str) | Tar en funktion av ett argument där detta element används som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | Tar angiven funktion där detta element används som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | Tar angiven funktion där detta element används som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | Tar angiven funktion där detta element används som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar angiven funktion där detta element används som argument och ett specificerat extra argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar angiven funktion där detta element används som argument och ett specificerat extra argument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | Skapar nedsänkt |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/set_subscript/#str) | Skapar nedsänkt |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | Skapar upphöjt |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/set_superscript/#str) | Skapar upphöjt |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar nedsänkt och upphöjt på högra sidan |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | Skapar nedsänkt och upphöjt på högra sidan |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar nedsänkt och upphöjt på vänstra sidan |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | Skapar nedsänkt och upphöjt på vänstra sidan |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/radical/#imathelement) | Specificerar den matematiska roten av given grad från det specificerade argumentet. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/radical/#str) | Specificerar den matematiska roten av given grad från det specificerade argumentet. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | Tar nedre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | Tar nedre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-är operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | Skapar en N-är operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralen |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | Tar integralen |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/group/#) | Placera detta element i en grupp med en nedre krullparentes |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Placera detta element i en grupp med ett grupperingstecken såsom nedre krullparentes eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/to_border_box/#) | Placera detta element i en kantlåda |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placera detta element i en kantlåda |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/to_math_array/#) | Sätter in en vertikal matris |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/accent/#char) | Sätter ett accenttecken (ett tecken ovanpå detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/overbar/#) | Sätter ett streck ovanpå detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/underbar/#) | Sätter ett streck under detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/to_box/#) | Placera detta element i en icke-visuell ruta (logisk gruppering) <br/>            som används för att gruppera komponenter i en ekvation eller annan instans av matematisk text.<br/>            Ett inramat objekt kan (till exempel) fungera som en operator-emulator med eller utan en justeringspunkt, <br/>            fungera som en radbrytpunkten, eller grupperas så att radbrytningar inte tillåts inom det. |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathbox/get_children/#) | Hämta underordnade element |

### Se även
* klass [`MathBox`](/slides/python-net/sv/aspose.slides.mathtext/mathbox)
* klass [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)