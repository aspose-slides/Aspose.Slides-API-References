---
title: IMathMatrix class
second_title: Aspose.Slides pro Python prostřednictvím .NET API referenční příručka
description: 
type: docs
url: /cs/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix třída

Specifikuje objekt Matrix, který se skládá z podřízených prvků uspořádaných v jednom nebo více řádcích a sloupcích. 
            Je důležité poznamenat, že matice nemají vestavěné oddělovače. 
            Pro umístění matice do závorek byste měli použít objekt oddělovače (IMathDelimiter).
            Null argumenty lze použít k vytvoření mezer v maticích.

The IMathMatrix type exposes the following members:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`row_count`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/row_count/) | Počet řádků v matici |
| [`column_count`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/column_count/) | Počet sloupců v matici |
| [`hide_placeholders`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Skrýt zástupné symboly pro prázdné prvky matice<br/>            Výchozí: false |
| [`base_justification`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/base_justification/) | Určuje svislé zarovnání vzhledem k okolnímu textu.<br/>            Možné hodnoty jsou top, bottom, a center.<br/>            Výchozí: Center |
| [`min_column_width`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/min_column_width/) | Minimální šířka sloupce v jednotkách twip (1/20 bodu)<br/>            Prostor mezi sloupci (také nazýván „Column Gap“ nebo „Gap Width“) se přičítá k <br/>            MinColumnWidth pro určení celkového rozestupu sloupců matice<br/>            (vzdálenost mezi stejnými okraji různých sloupců).<br/>            Výchozí: 0. |
| [`column_gap_rule`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | Typ vodorovného rozestupu mezi sloupci matice;<br/>            Jednotky vodorovného rozestupu mohou být ems nebo body (uloženy jako twips).<br/>            Výchozí: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/column_gap/) | Hodnota vodorovného rozestupu mezi sloupci matice;<br/>            Pokud je ColumnGapRule nastaven na 3 ("Exactly"), jednotka je interpretována jako twip (1/20 bodu)<br/>            Pokud je ColumnGapRule nastaven na 4 ("Multiple"), jednotka je interpretována jako počet 0.5-em kroků.<br/>            V ostatních případech ignorováno.<br/>            Výchozí: 0 |
| [`row_gap_rule`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | Typ svislého rozestupu mezi řádky matice;<br/>            Jednotky svislého rozestupu mohou být řádky nebo body (uloženy jako twips).<br/>            Výchozí: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/row_gap/) | Hodnota svislého rozestupu mezi řádky matice;<br/>            Pokud je RowGapRule nastaven na 3 ("Exactly"), jednotka je interpretována jako twip (1/20 bodu)<br/>            Pokud je RowGapRule nastaven na 4 ("Multiple"), jednotka je interpretována jako půl-řádky.<br/>            Výchozí: 0 |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | Získá vodorovné zarovnání zadaného sloupce |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Nastaví vodorovné zarovnání zadaného sloupce |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Nastaví vodorovné zarovnání zadaných sloupců |
| [`insert_row_before(self, row_index)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | Vloží nový řádek před zadaný řádek<br/>            Na počátku jsou všechny prvky v novém řádku None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | Vloží nový řádek za zadaný řádek<br/>            Na počátku jsou všechny prvky v novém řádku None. |
| [`delete_row(self, row_index)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/delete_row/#int) | Odstraní zadaný řádek |
| [`insert_column_before(self, column_index)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | Vloží nový sloupec před zadaný sloupec<br/>            Na počátku jsou všechny prvky v novém sloupci None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | Vloží nový sloupec za zadaný sloupec<br/>            Na počátku jsou všechny prvky v novém sloupci None. |
| [`delete_column(self, column_index)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/delete_column/#int) | Odstraní zadaný sloupec |
| [`get_children(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/cs/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### Viz také
* modul [`aspose.slides.mathtext`](/slides/python-net/cs/aspose.slides.mathtext)
* knihovna [`Aspose.Slides`](/slides/python-net)