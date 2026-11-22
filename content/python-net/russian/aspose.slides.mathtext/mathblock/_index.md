---
title: MathBlock class
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathblock/
---
## MathBlock класс

Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line.
            All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.

**Inheritance:**[`MathBlock`](/slides/python-net/ru/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)

The MathBlock type exposes the following members:

## Конструкторы

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/__init__/#) | Инициализирует новый экземпляр класса MathBlock. |
| [`__init__(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Создает новый математический блок и помещает в него указанный элемент |
| [`__init__(self, math_elements)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Свойства

| Property | Description |
| :- | :- |
| [`count`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/count/) | Получает количество дочерних математических элементов, фактически содержащихся в коллекции.<br/>            Только для чтения **int**. |
| [`is_read_only`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/is_read_only/) | Возвращает false, потому что коллекцию дочерних элементов можно изменять. |

Gets or sets IMathElement at the specified index.

## Индексатор

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/__getitem__/) | Нулевой индекс элемента |

## Методы

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/join/#imathelement) | Объединяет математический элемент с этим математическим блоком |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/join/#str) | Объединяет математический текст с этим математическим блоком |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/divide/#imathelement) | Создает дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/divide/#str) | Создает дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/enclose/#) | Оборачивает математический элемент в круглые скобки |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/enclose/#char-char) | Оборачивает дочерние элементы этого блока в указанные символы, такие как скобки или другие символы в качестве рамки |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | Оборачивает дочерние элементы этого блока в указанные символы, такие как скобки или другие в качестве рамки<br/>            и разделяет их символом-разделителем |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/function/#imathelement) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/function/#str) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Создает нижний индекс |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_subscript/#str) | Создает нижний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Создает верхний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_superscript/#str) | Создает верхний индекс |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Создает нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Создает нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Создает нижний и верхний индексы слева |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Создает нижний и верхний индексы слева |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/radical/#imathelement) | Указывает математический корень заданной степени от указанного аргумента. |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/radical/#str) | Указывает математический корень заданной степени от указанного аргумента. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Принимает верхний предел |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Принимает верхний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Принимает нижний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Принимает нижний предел |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Создает N-арный оператор |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Создает N-арный оператор |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Принимает интеграл |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Принимает интеграл без пределов |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Принимает интеграл |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/group/#) | Помещает этот элемент в группу с использованием нижней фигурной скобки |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Помещает этот элемент в группу с использованием символа группировки, например нижней фигурной скобки или другого |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/to_border_box/#) | Помещает этот элемент в рамку-коробку |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Помещает этот элемент в рамку-коробку |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/to_math_array/#) | Располагет дочерние элементы в вертикальном массиве |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/accent/#char) | Устанавливает надстрочный акцент (символ над этим элементом) |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/overbar/#) | Устанавливает черту над этим элементом |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/underbar/#) | Устанавливает черту под этим элементом |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/to_box/#) | Помещает этот элемент в невизуальную коробку (логическая группировка) <br/>            которая используется для группировки компонентов уравнения или другого экземпляра математического текста.<br/>            Объект в коробке может (например) служить имитацией оператора с точкой выравнивания или без неё, <br/>            служить точкой разрыва строки или быть сгруппированным так, чтобы не допускать разрывов строки внутри. |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/get_children/#) | Получить дочерние элементы |
| [`add(self, item)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/add/#imathelement) | Добавляет математический элемент в конец коллекции. |
| [`clear(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/clear/#) | Удаляет все элементы из коллекции. |
| [`contains(self, item)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/contains/#imathelement) | Определяет, содержит ли коллекция конкретное значение. |
| [`copy_to(self, array, array_index)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Копировать в указанный массив. |
| [`remove(self, item)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/remove/#imathelement) | Удаляет первое вхождение конкретного объекта из коллекции. |
| [`index_of(self, item)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Определяет индекс конкретного математического элемента в коллекции. |
| [`insert(self, index, item)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Вставляет MathElement в коллекцию по указанному индексу. |
| [`remove_at(self, index)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/remove_at/#int) | Удаляет элемент по указанному индексу из коллекции. |
| [`join_block(self, other)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Объединяет другой математический блок с этим |
| [`delimit(self, separator_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/delimit/#char) | Разделяет дочерние элементы символом-разделителем (без скобок) |
| [`write_as_math_ml(self, stream)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Сохраняет содержимое этого [`MathBlock`](/slides/python-net/ru/aspose.slides.mathtext/mathblock) как MathML |

### См. также
* class [`MathBlock`](/slides/python-net/ru/aspose.slides.mathtext/mathblock)
* class [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)
* module [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)