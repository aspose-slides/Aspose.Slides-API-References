---
title: IMathMatrix class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix classe

Specifica l'oggetto Matrix, composto da elementi figli disposti in una o più righe e colonne.  
È importante notare che le matrici non hanno delimitatori integrati.  
Per inserire la matrice tra parentesi è necessario utilizzare l'oggetto delimitatore (IMathDelimiter).  
È possibile usare argomenti null per creare spazi vuoti nelle matrici.

Il tipo IMathMatrix espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`row_count`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/row_count/) | Numero di righe nella matrice |
| [`column_count`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/column_count/) | Numero di colonne nella matrice |
| [`hide_placeholders`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Nascondi i segnaposto per gli elementi vuoti della matrice<br/>            Default: false |
| [`base_justification`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/base_justification/) | Specifica l'allineamento verticale rispetto al testo circostante. <br/>            Possible values are top, bottom, and center.<br/>            Default: Center |
| [`min_column_width`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/min_column_width/) | Larghezza minima della colonna in twip (1/20 di punto)<br/>            The gap spacing (also referred to as “Column Gap” or “Gap Width”) is added to <br/>            the MinColumnWidth to determine the total Matrix Column Spacing<br/>            (distance between the same edges of different columns).<br/>            Default: 0. |
| [`column_gap_rule`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | Il tipo di spaziatura orizzontale tra le colonne di una matrice; <br/>            Horizontal spacing units can be ems or points (stored as twips).<br/>            Default: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/column_gap/) | Il valore della spaziatura orizzontale tra le colonne di una matrice;<br/>            If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)<br/>            If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments.<br/>            In other cases ignored.<br/>            Default: 0 |
| [`row_gap_rule`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | Il tipo di spaziatura verticale tra le righe di una matrice; <br/>            Vertical spacing units can be lines or points (stored as twips).<br/>            Default: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/row_gap/) | Il valore della spaziatura verticale tra le righe di una matrice;<br/>            If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point)<br/>            If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines.<br/>            Default: 0 |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | Ottieni l'allineamento orizzontale della colonna specificata |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Imposta l'allineamento orizzontale della colonna specificata |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Imposta l'allineamento orizzontale delle colonne specificate |
| [`insert_row_before(self, row_index)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | Inserisci una nuova riga prima di quella specificata<br/>            Initially all elements in the new row are None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | Inserisci una nuova riga dopo quella specificata<br/>            Initially all elements in the new row are None. |
| [`delete_row(self, row_index)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/delete_row/#int) | Elimina la riga specificata |
| [`insert_column_before(self, column_index)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | Inserisci una nuova colonna prima di quella specificata<br/>            Initially all elements in the new column are None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | Inserisci una nuova colonna dopo quella specificata<br/>            Initially all elements in the new column are None. |
| [`delete_column(self, column_index)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/delete_column/#int) | Elimina la colonna specificata |
| [`get_children(self)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/it/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### Vedi anche
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)