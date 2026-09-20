---
title: IMathMatrix class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix klass

Anger matris-objektet, bestående av underordnade element som är placerade i en eller flera rader och kolumner.  
Det är viktigt att notera att matriser inte har inbyggda avgränsare.  
För att placera matrisen i hakparenteser bör du använda avgränsareobjektet (IMathDelimiter).  
Null-argument kan användas för att skapa luckor i matriser.

IMathMatrix-typen visar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`row_count`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/row_count/) | Antal rader i matrisen |
| [`column_count`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/column_count/) | Antal kolumner i matrisen |
| [`hide_placeholders`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Dölj platshållarna för tomma matrixelement<br/>            Standard: false |
| [`base_justification`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/base_justification/) | Anger vertikal justering i förhållande till omgivande text. <br/>            Möjliga värden är top, bottom, och center.<br/>            Standard: Center |
| [`min_column_width`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/min_column_width/) | Minsta kolumnbredd i twips (1/20 av en punkt)<br/>            Avståndet mellan kolumner (även kallat “Column Gap” eller “Gap Width”) läggs till <br/>            MinColumnWidth för att bestämma den totala Matrix Column Spacing<br/>            (avståndet mellan samma kanter på olika kolumner).<br/>            Standard: 0. |
| [`column_gap_rule`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | Typen av horisontellt avstånd mellan kolumner i en matris; <br/>            Enheter för horisontellt avstånd kan vara ems eller points (lagrade som twips).<br/>            Standard: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/column_gap/) | Värdet på horisontellt avstånd mellan kolumner i en matris;<br/>            Om ColumnGapRule är satt till 3 ("Exactly"), tolkas enheten som twips (1/20 av en punkt)<br/>            Om ColumnGapRule är satt till 4 ("Multiple"), tolkas enheten som antal 0.5 em-steg.<br/>            Ignoreras i andra fall.<br/>            Standard: 0 |
| [`row_gap_rule`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | Typen av vertikalt avstånd mellan rader i en matris; <br/>            Enheter för vertikalt avstånd kan vara lines eller points (lagrade som twips).<br/>            Standard: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/row_gap/) | Värdet på vertikalt avstånd mellan rader i en matris;<br/>            Om RowGapRule är satt till 3 ("Exactly"), tolkas enheten som twips (1/20 av en punkt)<br/>            Om RowGapRule är satt till 4 ("Multiple"), tolkas enheten som halva lines.<br/>            Standard: 0 |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | Hämta den horisontella justeringen för den angivna kolumnen |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Ställ in den horisontella justeringen för den angivna kolumnen |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Ställ in den horisontella justeringen för de angivna kolumnerna |
| [`insert_row_before(self, row_index)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | Infoga en ny rad före den angivna<br/>            Alla element i den nya raden är initialt None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | Infoga en ny rad efter den angivna<br/>            Alla element i den nya raden är initialt None. |
| [`delete_row(self, row_index)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/delete_row/#int) | Tar bort den angivna raden |
| [`insert_column_before(self, column_index)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | Infoga en ny kolumn före den angivna<br/>            Alla element i den nya kolumnen är initialt None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | Infoga en ny kolumn efter den angivna<br/>            Alla element i den nya kolumnen är initialt None. |
| [`delete_column(self, column_index)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/delete_column/#int) | Tar bort den angivna kolumnen |
| [`get_children(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/sv/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### Se även
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)