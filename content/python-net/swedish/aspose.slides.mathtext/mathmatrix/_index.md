---
title: MathMatrix class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix klass

Specificerar Matrix-objektet, bestående av underordnade element placerade i en eller flera rader och kolumner. Det är viktigt att notera att matriser inte har inbyggda avgränsare. För att placera matrisen i hakparenteser bör du använda avgränsarobjektet (IMathDelimiter). Null-argument kan användas för att skapa luckor i matriser.

**Arv:**[`MathMatrix`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)

MathMatrix-typen exponerar följande medlemmar:

## Konstruktorer

| Konstruktor | Beskrivning |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | Initialiserar ett nytt exempel av MathMatrix-klassen. |

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`row_count`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/row_count/) | Antal rader i matrisen |
| [`column_count`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/column_count/) | Antal kolumner i matrisen |
| [`hide_placeholders`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | Dölj platshållarna för tomma matrix-element<br/>            Standard: false |
| [`base_justification`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/base_justification/) | Anger vertikal justering i förhållande till omgivande text. <br/>            Möjliga värden är top, bottom, och center.<br/>            Standard: Center |
| [`min_column_width`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/min_column_width/) | Minimal kolumnbredd i twips (1/20 av en punkt)<br/>            Avståndet mellan kolumner (även kallat “Column Gap” eller “Gap Width”) läggs till <br/>            MinColumnWidth för att bestämma total Matrix Column Spacing<br/>            (avstånd mellan samma kanter på olika kolumner).<br/>            Standard: 0. |
| [`column_gap_rule`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | Typen av horisontellt avstånd mellan kolumner i en matris; <br/>            Horisontella avståndsenheter kan vara ems eller points (lagrade som twips).<br/>            Standard: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/column_gap/) | Värdet för horisontellt avstånd mellan kolumner i en matris;<br/>            Om ColumnGapRule är satt till 3 ("Exactly") tolkas enheten som twips (1/20 av en punkt)<br/>            Om ColumnGapRule är satt till 4 ("Multiple") tolkas enheten som antal 0.5 em-ökningar.<br/>            Ignoreras i andra fall.<br/>            Standard: 0 |
| [`row_gap_rule`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | Typen av vertikalt avstånd mellan rader i en matris; <br/>            Vertikala avståndsenheter kan vara lines eller points (lagrade som twips).<br/>            Standard: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/row_gap/) | Värdet för vertikalt avstånd mellan rader i en matris;<br/>            Om RowGapRule är satt till 3 ("Exactly") tolkas enheten som twips (1/20 av en punkt)<br/>            Om RowGapRule är satt till 4 ("Multiple") tolkas enheten som halvlånga rader.<br/>            Standard: 0 |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/join/#imathelement) | Ansluter ett matematiskt element och bildar ett matematiskt block |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/join/#str) | Ansluter en matematisk text och bildar ett matematiskt block |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | Skapar en bråkdel med detta täljare och angivet nämnare |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/divide/#str) | Skapar en bråkdel med detta täljare och angivet nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | Skapar en bråkdel av angiven typ med detta täljare och angivet nämnare |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | Skapar en bråkdel av angiven typ med detta täljare och angivet nämnare |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/enclose/#) | Omsluter ett matematiskt element i parentes |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | Omsluter ett matematiskt element i specificerade tecken såsom parentes eller andra tecken som ram |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/function/#imathelement) | Tar en funktion av ett argument med detta exempel som funktionsnamn |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/function/#str) | Tar en funktion av ett argument med detta exempel som funktionsnamn |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | Tar specificerad funktion med detta exempel som argument |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | Tar specificerad funktion med detta exempel som argument |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | Tar specificerad funktion med detta exempel som argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Tar specificerad funktion med detta exempel som argument och specificerat ytterligare argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Tar specificerad funktion med detta exempel som argument och specificerat ytterligare argument |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | Skapar nedsänkt text |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | Skapar nedsänkt text |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | Skapar upphöjd text |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | Skapar upphöjd text |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | Skapar nedsänkt och upphöjd text till höger |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | Skapar nedsänkt och upphöjd text till höger |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | Skapar nedsänkt och upphöjd text till vänster |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | Skapar nedsänkt och upphöjd text till vänster |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | Anger den matematiska roten av given grad från det specificerade argumentet. |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/radical/#str) | Anger den matematiska roten av given grad från det specificerade argumentet. |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | Tar övre gräns |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | Tar övre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | Tar undre gräns |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | Tar undre gräns |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | Skapar en N-är operator |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | Skapar en N-är operator |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | Tar integralen |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | Tar integralen utan gränser |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | Tar integralen |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | Tar integralen |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/group/#) | Placera detta element i en grupp med en bottenklammer |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | Placera detta element i en grupp med ett grupperingstecken såsom bottenklammer eller annat |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/to_border_box/#) | Placera detta element i en kant-box |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Placera detta element i en kant-box |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/to_math_array/#) | Sätter in i en vertikal matris |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/accent/#char) | Sätter ett accenttecken (ett tecken ovanför detta element) |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/overbar/#) | Sätter en stapel ovanpå detta element |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/underbar/#) | Sätter en stapel under detta element |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/to_box/#) | Placera detta element i en icke-visuell låda (logisk gruppering) <br/>            som används för att gruppera komponenter i en ekvation eller annan matematisk text.<br/>            En lådad objekt kan (till exempel) fungera som en operator-emulator med eller utan en justeringspunkt, <br/>            fungera som en radbrytningspunkt, eller grupperas så att radbrytningar inte tillåts inom. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | Hämta den horisontella justeringen för den specificerade kolumnen |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Ställ in den horisontella justeringen för den specificerade kolumnen |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Ställ in den horisontella justeringen för de specificerade kolumnerna |
| [`insert_row_before(self, row_index)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | Infoga en ny rad före den specificerade<br/>            Initialt är alla element i den nya raden None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | Infoga en ny rad efter den specificerade<br/>            Initialt är alla element i den nya raden None. |
| [`delete_row(self, row_index)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/delete_row/#int) | Tar bort den specificerade raden |
| [`insert_column_before(self, column_index)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | Infoga en ny kolumn före den specificerade<br/>            Initialt är alla element i den nya kolumnen None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | Infoga en ny kolumn efter den specificerade<br/>            Initialt är alla element i den nya kolumnen None. |
| [`delete_column(self, column_index)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/delete_column/#int) | Tar bort den specificerade kolumnen |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix/get_children/#) | Hämta barn-element |

### Se också
* klass [`MathElementBase`](/slides/python-net/sv/aspose.slides.mathtext/mathelementbase)
* klass [`MathMatrix`](/slides/python-net/sv/aspose.slides.mathtext/mathmatrix)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)