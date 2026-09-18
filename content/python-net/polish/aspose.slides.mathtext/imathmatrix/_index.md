---
title: IMathMatrix class
second_title: Aspose.Slides dla Pythona przez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix klasa

Określa obiekt Matrix, składający się z elementów podrzędnych rozmieszczonych w jednym lub kilku wierszach i kolumnach.  
Należy zauważyć, że macierze nie mają wbudowanych delimitatorów.  
Aby umieścić macierz w nawiasach, należy użyć obiektu delimitatora (IMathDelimiter).  
Argumenty null mogą być używane do tworzenia przerw w macierzach.

The IMathMatrix type exposes the following members:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`row_count`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/row_count/) | Liczba wierszy w macierzy |
| [`column_count`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/column_count/) | Liczba kolumn w macierzy |
| [`hide_placeholders`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Ukryj symbole zastępcze dla pustych elementów macierzy<br/>            Domyślnie: false |
| [`base_justification`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/base_justification/) | Określa pionowe wyrównanie względem otaczającego tekstu. <br/>            Dostępne wartości to top, bottom i center.<br/>            Domyślnie: Center |
| [`min_column_width`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/min_column_width/) | Minimalna szerokość kolumny w twips (1/20 punktu)<br/>            Odstęp między kolumnami (nazywany również „Column Gap” lub „Gap Width”) jest dodawany do <br/>            MinColumnWidth w celu określenia całkowitego odstępu kolumn macierzy<br/>            (odległość pomiędzy tymi samymi krawędziami różnych kolumn).<br/>            Domyślnie: 0. |
| [`column_gap_rule`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | Typ poziomego odstępu między kolumnami macierzy; <br/>            Jednostki poziomego odstępu mogą być em lub punkty (przechowywane jako twips).<br/>            Domyślnie: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/column_gap/) | Wartość poziomego odstępu między kolumnami macierzy;<br/>            Jeśli ColumnGapRule ma wartość 3 (\"Exactly\"), jednostka jest interpretowana jako twips (1/20 punktu)<br/>            Jeśli ColumnGapRule ma wartość 4 (\"Multiple\"), jednostka jest interpretowana jako liczba przyrostów 0,5 em.<br/>            W innych przypadkach ignorowane.<br/>            Domyślnie: 0 |
| [`row_gap_rule`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | Typ pionowego odstępu między wierszami macierzy; <br/>            Jednostki pionowego odstępu mogą być linie lub punkty (przechowywane jako twips).<br/>            Domyślnie: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/row_gap/) | Wartość pionowego odstępu między wierszami macierzy;<br/>            Jeśli RowGapRule ma wartość 3 (\"Exactly\"), jednostka jest interpretowana jako twips (1/20 punktu)<br/>            Jeśli RowGapRule ma wartość 4 (\"Multiple\"), jednostka jest interpretowana jako połowy linii.<br/>            Domyślnie: 0 |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | Pobiera poziome wyrównanie określonej kolumny |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Ustawia poziome wyrównanie określonej kolumny |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Ustawia poziome wyrównanie określonych kolumn |
| [`insert_row_before(self, row_index)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | Wstawia nowy wiersz przed określonym<br/>            Początkowo wszystkie elementy w nowym wierszu są None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | Wstawia nowy wiersz po określonym<br/>            Początkowo wszystkie elementy w nowym wierszu są None. |
| [`delete_row(self, row_index)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/delete_row/#int) | Usuwa określony wiersz |
| [`insert_column_before(self, column_index)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | Wstawia nową kolumnę przed określoną<br/>            Początkowo wszystkie elementy w nowej kolumnie są None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | Wstawia nową kolumnę po określonej<br/>            Początkowo wszystkie elementy w nowej kolumnie są None. |
| [`delete_column(self, column_index)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/delete_column/#int) | Usuwa określoną kolumnę |
| [`get_children(self)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### Zobacz także
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)