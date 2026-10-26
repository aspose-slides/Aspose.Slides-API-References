---
title: MathMatrix class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix класс

Определяет объект Matrix, состоящий из дочерних элементов, размещённых в одной или нескольких строках и столбцах. 
            Важно отметить, что у матриц нет встроенных разделителей. 
            Чтобы разместить матрицу в скобках, следует использовать объект разделителя (IMathDelimiter).
            Нулевые аргументы можно использовать для создания пробелов в матрицах.

**Наследование:**[`MathMatrix`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)

Тип MathMatrix раскрывает следующие члены:

## Конструкторы

| Constructor | Description |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | Инициализирует новый экземпляр класса MathMatrix. |

## Свойства

| Property | Description |
| :- | :- |
| [`row_count`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/row_count/) | Количество строк в матрице |
| [`column_count`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/column_count/) | Количество столбцов в матрице |
| [`hide_placeholders`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | Скрывать заполнители для пустых элементов матрицы<br/>            По умолчанию: false |
| [`base_justification`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/base_justification/) | Определяет вертикальное выравнивание относительно окружающего текста.<br/>            Возможные значения: top, bottom и center.<br/>            По умолчанию: Center |
| [`min_column_width`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/min_column_width/) | Минимальная ширина столбца в twips (1/20 пункта)<br/>            Расстояние между столбцами (также называемое “Column Gap” или “Gap Width”) добавляется к <br/>            MinColumnWidth для определения общего расстояния между столбцами матрицы<br/>            (расстояние между одинаковыми краями разных столбцов).<br/>            По умолчанию: 0. |
| [`column_gap_rule`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | Тип горизонтального интервала между столбцами матрицы;<br/>            Единицы горизонтального интервала могут быть ems или points (хранятся как twips).<br/>            По умолчанию: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/column_gap/) | Значение горизонтального интервала между столбцами матрицы;<br/>            Если ColumnGapRule установлен в 3 ("Exactly"), то единица интерпретируется как twips (1/20 пункта)<br/>            Если ColumnGapRule установлен в 4 ("Multiple"), то единица интерпретируется как количество шагов по 0.5 em.<br/>            В остальных случаях игнорируется.<br/>            По умолчанию: 0 |
| [`row_gap_rule`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | Тип вертикального интервала между строками матрицы;<br/>            Единицы вертикального интервала могут быть lines или points (хранятся как twips).<br/>            По умолчанию: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/row_gap/) | Значение вертикального интервала между строками матрицы;<br/>            Если RowGapRule установлен в 3 ("Exactly"), то единица интерпретируется как twips (1/20 пункта)<br/>            Если RowGapRule установлен в 4 ("Multiple"), то единица интерпретируется как половины линий.<br/>            По умолчанию: 0 |

## Методы

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/join/#imathelement) | Объединяет математический элемент и формирует математический блок |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/join/#str) | Объединяет математический текст и формирует математический блок |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | Создаёт дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/divide/#str) | Создаёт дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/enclose/#) | Окружает математический элемент скобками |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | Окружает математический элемент заданными символами, такими как скобки или другими символами для оформления |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/function/#imathelement) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/function/#str) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | Создаёт нижний индекс |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | Создаёт нижний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | Создаёт верхний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | Создаёт верхний индекс |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | Создаёт нижний и верхний индексы слева |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | Создаёт нижний и верхний индексы слева |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | Указывает математический корень заданной степени от указанного аргумента. |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/radical/#str) | Указывает математический корень заданной степени от указанного аргумента. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | Принимает верхний предел |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | Принимает верхний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | Принимает нижний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | Принимает нижний предел |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | Создаёт N-арный оператор |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | Создаёт N-арный оператор |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Берёт интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | Берёт интеграл |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | Берёт интеграл без пределов |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | Берёт интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | Берёт интеграл |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/group/#) | Размещает этот элемент в группе, используя нижнюю фигурную скобку |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | Размещает этот элемент в группе, используя символ группировки, например нижнюю фигурную скобку или другой |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/to_border_box/#) | Размещает этот элемент в рамках (border-box) |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Размещает этот элемент в рамках (border-box) |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/to_math_array/#) | Размещает в вертикальном массиве |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/accent/#char) | Устанавливает знак акцента (символ над этим элементом) |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/overbar/#) | Устанавливает черту сверху этого элемента |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/underbar/#) | Устанавливает черту снизу этого элемента |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/to_box/#) | Размещает этот элемент в невидимом боксе (логическая группировка)<br/>            который используется для группировки компонентов уравнения или другого фрагмента математического текста.<br/>            Объект в боксе может (например) служить эмулятором оператора с точкой выравнивания или без неё,<br/>            служить точкой разрыва строки или быть сгруппированным так, чтобы не допускать разрывы строк внутри. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | Получить горизонтальное выравнивание указанного столбца |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Установить горизонтальное выравнивание указанного столбца |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Установить горизонтальное выравнивание указанных столбцов |
| [`insert_row_before(self, row_index)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | Вставить новую строку перед указанной<br/>            Изначально все элементы в новой строке имеют значение None. |
| [`insert_row_after(self, row_index)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | Вставить новую строку после указанной<br/>            Изначально все элементы в новой строке имеют значение None. |
| [`delete_row(self, row_index)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/delete_row/#int) | Удаляет указанную строку |
| [`insert_column_before(self, column_index)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | Вставить новый столбец перед указанным<br/>            Изначально все элементы в новом столбце имеют значение None. |
| [`insert_column_after(self, column_index)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | Вставить новый столбец после указанного<br/>            Изначально все элементы в новом столбце имеют значение None. |
| [`delete_column(self, column_index)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/delete_column/#int) | Удаляет указанный столбец |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix/get_children/#) | Получить дочерние элементы |


### См. также
* класс [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)
* класс [`MathMatrix`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)