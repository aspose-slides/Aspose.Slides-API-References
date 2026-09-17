---
title: IMathMatrix class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix класс

Указывает объект Matrix, состоящий из дочерних элементов, расположенных в одной или нескольких строках и столбцах. 
            Важно отметить, что у матриц нет встроенных разделителей. 
            Чтобы поместить матрицу в скобки, следует использовать объект разделителя (IMathDelimiter).
            Null-аргументы можно использовать для создания пустот в матрицах.

Тип IMathMatrix раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`row_count`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/row_count/) | Количество строк в матрице |
| [`column_count`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/column_count/) | Количество столбцов в матрице |
| [`hide_placeholders`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Скрыть заполнители для пустых элементов матрицы<br/>            Default: false |
| [`base_justification`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/base_justification/) | Указывает вертикальное выравнивание относительно окружающего текста.<br/>            Возможные значения: top, bottom, и center.<br/>            Default: Center |
| [`min_column_width`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/min_column_width/) | Минимальная ширина столбца в твипсах (1/20 пункта)<br/>            Промежуток между столбцами (также называемый “Column Gap” или “Gap Width”) добавляется к <br/>            MinColumnWidth для определения общего расстояния между столбцами матрицы<br/>            (расстояние между одинаковыми краями разных столбцов).<br/>            Default: 0. |
| [`column_gap_rule`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | Тип горизонтального промежутка между столбцами матрицы;<br/>            Единицы горизонтального промежутка могут быть ems или points (хранятся как твипсы).<br/>            Default: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/column_gap/) | Значение горизонтального промежутка между столбцами матрицы;<br/>            Если ColumnGapRule установлено в 3 ("Exactly"), то единица интерпретируется как твипсы (1/20 пункта)<br/>            Если ColumnGapRule установлено в 4 ("Multiple"), то единица интерпретируется как количество шагов 0.5 em.<br/>            В остальных случаях игнорируется.<br/>            Default: 0 |
| [`row_gap_rule`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | Тип вертикального промежутка между строками матрицы;<br/>            Единицы вертикального промежутка могут быть lines или points (хранятся как твипсы).<br/>            Default: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/row_gap/) | Значение вертикального промежутка между строками матрицы;<br/>            Если RowGapRule установлено в 3 ("Exactly"), то единица интерпретируется как твипсы (1/20 пункта)<br/>            Если RowGapRule установлено в 4 ("Multiple"), то единица интерпретируется как половинные строки.<br/>            Default: 0 |

## Методы

| Метод | Описание |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | Получить горизонтальное выравнивание указанного столбца |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Задать горизонтальное выравнивание указанного столбца |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Задать горизонтальное выравнивание указанных столбцов |
| [`insert_row_before(self, row_index)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | Вставить новую строку перед указанной<br/>            Изначально все элементы в новой строке имеют значение None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | Вставить новую строку после указанной<br/>            Изначально все элементы в новой строке имеют значение None. |
| [`delete_row(self, row_index)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/delete_row/#int) | Удалить указанную строку |
| [`insert_column_before(self, column_index)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | Вставить новый столбец перед указанным<br/>            Изначально все элементы в новом столбце имеют значение None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | Вставить новый столбец после указанного<br/>            Изначально все элементы в новом столбце имеют значение None. |
| [`delete_column(self, column_index)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/delete_column/#int) | Удалить указанный столбец |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### См. также
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)