---
title: MathMatrix class
second_title: Aspose.Slides dla Pythona przez API .NET
description: 
type: docs
url: /pl/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix klasa

Określa obiekt Matrix, składający się z elementów podrzędnych ułożonych w jednym lub kilku wierszach i kolumnach. 
            Należy zauważyć, że macierze nie mają wbudowanych delimiterów. 
            Aby umieścić macierz w nawiasach, należy użyć obiektu delimiter (IMathDelimiter).
            Argumenty null można używać do tworzenia przerw w macierzach.

**Dziedziczenie:**[`MathMatrix`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)

Typ MathMatrix udostępnia następujące członków:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | Inicjalizuje nową instancję klasy MathMatrix. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`row_count`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/row_count/) | Liczba wierszy w macierzy |
| [`column_count`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/column_count/) | Liczba kolumn w macierzy |
| [`hide_placeholders`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | Ukryj symbole zastępcze dla pustych elementów macierzy<br/>            Domyślnie: false |
| [`base_justification`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/base_justification/) | Określa pionowe wyrównanie względem otaczającego tekstu. <br/>            Dostępne wartości: top, bottom, i center.<br/>            Domyślnie: Center |
| [`min_column_width`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/min_column_width/) | Minimalna szerokość kolumny w twipsach (1/20 punktu)<br/>            Odstęp przerwy (nazywany również „Column Gap” lub „Gap Width”) jest dodawany do <br/>            MinColumnWidth, aby określić całkowity odstęp kolumn macierzy<br/>            (odległość między tymi samymi krawędziami różnych kolumn).<br/>            Domyślnie: 0. |
| [`column_gap_rule`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | Typ odstępu poziomego między kolumnami macierzy; <br/>            Jednostki odstępu poziomego mogą być em lub punkty (przechowywane jako twips).<br/>            Domyślnie: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/column_gap/) | Wartość odstępu poziomego między kolumnami macierzy;<br/>            Jeśli ColumnGapRule ma wartość 3 ("Exactly"), jednostka jest interpretowana jako twips (1/20 punktu)<br/>            Jeśli ColumnGapRule ma wartość 4 ("Multiple"), jednostka jest interpretowana jako liczba przyrostów 0,5 em.<br/>            W innych przypadkach ignorowane.<br/>            Domyślnie: 0 |
| [`row_gap_rule`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | Typ odstępu pionowego między wierszami macierzy; <br/>            Jednostki odstępu pionowego mogą być linie lub punkty (przechowywane jako twips).<br/>            Domyślnie: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/row_gap/) | Wartość odstępu pionowego między wierszami macierzy;<br/>            Jeśli RowGapRule ma wartość 3 ("Exactly"), jednostka jest interpretowana jako twips (1/20 punktu)<br/>            Jeśli RowGapRule ma wartość 4 ("Multiple"), jednostka jest interpretowana jako pół-linie.<br/>            Domyślnie: 0 |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/join/#imathelement) | Łączy element matematyczny i tworzy blok matematyczny |
| [`join(self, math_text)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/join/#str) | Łączy tekst matematyczny i tworzy blok matematyczny |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [`divide(self, denominator)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/divide/#str) | Tworzy ułamek z tym licznikiem i określonym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | Tworzy ułamek określonego typu z tym licznikiem i określonym mianownikiem |
| [`enclose(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/enclose/#) | Otwiera element matematyczny nawiasami |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | Otwiera element matematyczny określonymi znakami, takimi jak nawiasy lub innymi znakami jako ramka |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/function/#imathelement) | Przyjmuje funkcję argumentu używając tej instancji jako nazwy funkcji |
| [`function(self, function_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/function/#str) | Przyjmuje funkcję argumentu używając tej instancji jako nazwy funkcji |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | Przyjmuje określoną funkcję używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | Przyjmuje określoną funkcję używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | Przyjmuje określoną funkcję używając tej instancji jako argumentu |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Przyjmuje określoną funkcję używając tej instancji jako argumentu oraz określony dodatkowy argument |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Przyjmuje określoną funkcję używając tej instancji jako argumentu oraz określony dodatkowy argument |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | Tworzy indeks dolny |
| [`set_subscript(self, subscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | Tworzy indeks dolny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | Tworzy indeks górny |
| [`set_superscript(self, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | Tworzy indeks górny |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | Tworzy indeks dolny i górny po prawej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | Tworzy indeks dolny i górny po lewej stronie |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | Tworzy indeks dolny i górny po lewej stronie |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [`radical(self, degree)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/radical/#str) | Określa pierwiastek matematyczny o podanym stopniu z określonego argumentu. |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | Przyjmuje górny limit |
| [`set_upper_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | Przyjmuje górny limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | Przyjmuje dolny limit |
| [`set_lower_limit(self, limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | Przyjmuje dolny limit |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | Tworzy operator N-arny |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | Tworzy operator N-arny |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Przyjmuje całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | Przyjmuje całkę |
| [`integral(self, integral_type)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | Przyjmuje całkę bez limitów |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | Przyjmuje całkę |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | Przyjmuje całkę |
| [`group(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/group/#) | Umieszcza ten element w grupie używając dolnego nawiasu klamrowego |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | Umieszcza ten element w grupie używając znaku grupującego, takiego jak dolny nawias klamrowy lub inny |
| [`to_border_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/to_border_box/#) | Umieszcza ten element w ramce |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Umieszcza ten element w ramce |
| [`to_math_array(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/to_math_array/#) | Umieszcza w pionowej tablicy |
| [`accent(self, accent_character)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/accent/#char) | Ustawia znak akcentu (znak nad tym elementem) |
| [`overbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/overbar/#) | Ustawia kreskę na górze tego elementu |
| [`underbar(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/underbar/#) | Ustawia kreskę na dole tego elementu |
| [`to_box(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/to_box/#) | Umieszcza ten element w niewizualnym pudełku (grupowanie logiczne) <br/>            które służy do grupowania komponentów równania lub innego fragmentu tekstu matematycznego.<br/>            Obiekt w pudełku może (na przykład) pełnić rolę emulatora operatora z punktem wyrównania lub bez niego, <br/>            służyć jako punkt podziału linii lub być grupowany tak, aby nie zezwalał na podziały linii wewnątrz. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | Pobiera wyrównanie poziome określonej kolumny |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Ustawia wyrównanie poziome określonej kolumny |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Ustawia wyrównanie poziome określonych kolumn |
| [`insert_row_before(self, row_index)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | Wstawia nowy wiersz przed określonym<br/>            Początkowo wszystkie elementy w nowym wierszu są None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | Wstawia nowy wiersz po określonym<br/>            Początkowo wszystkie elementy w nowym wierszu są None. |
| [`delete_row(self, row_index)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/delete_row/#int) | Usuwa określony wiersz |
| [`insert_column_before(self, column_index)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | Wstawia nową kolumnę przed określoną<br/>            Początkowo wszystkie elementy w nowej kolumnie są None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | Wstawia nową kolumnę po określonej<br/>            Początkowo wszystkie elementy w nowej kolumnie są None. |
| [`delete_column(self, column_index)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/delete_column/#int) | Usuwa określoną kolumnę |
| [`get_children(self)`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix/get_children/#) | Pobiera elementy potomne |


### Zobacz także
* klasa [`MathElementBase`](/slides/python-net/pl/aspose.slides.mathtext/mathelementbase)
* klasa [`MathMatrix`](/slides/python-net/pl/aspose.slides.mathtext/mathmatrix)
* moduł [`aspose.slides.mathtext`](/slides/python-net/pl/aspose.slides.mathtext)
* biblioteka [`Aspose.Slides`](/slides/python-net)