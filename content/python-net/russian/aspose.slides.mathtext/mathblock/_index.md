---
title: MathBlock class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathblock/
---
## MathBlock класс

Указывает экземпляр математического текста, содержащийся в MathParagraph и начинающийся с новой строки.  
Все математические зоны, включая уравнения, выражения, массивы уравнений или выражений и формулы, представлены как math block.

**Наследование:**[`MathBlock`](/slides/python-net/ru/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)

Тип MathBlock предоставляет следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/__init__/#) | Инициирует новый экземпляр класса MathBlock. |
| [`__init__(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Создает новый математический блок и помещает в него указанный элемент. |
| [`__init__(self, math_elements)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`count`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/count/) | Возвращает количество дочерних математических элементов, реально содержащихся в коллекции.<br/>            Только для чтения **int**. |
| [`is_read_only`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/is_read_only/) | Возвращает false, потому что коллекцию дочерних элементов можно изменять. |

Получает или задает IMathElement по указанному индексу.

## Индексатор

| Имя | Описание |
| :- | :- |
| [`[index]`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/__getitem__/) | Нулевой индекс элемента |

## Методы

| Метод | Описание |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/join/#imathelement) | Объединяет математический элемент с этим математическим блоком. |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/join/#str) | Объединяет математический текст с этим математическим блоком. |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/divide/#imathelement) | Создает дробь с этим числителем и указанным знаменателем. |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/divide/#str) | Создает дробь с этим числителем и указанным знаменателем. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем. |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/enclose/#char-char) | Обрамляет дочерние элементы этого блока указанными символами, такими как скобки или другими символами. |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | Обрамляет дочерние элементы этого блока указанными символами, такими как скобки или другими, и разделяет их символом-разделителем.<br/>            |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/enclose/#) | Обрамляет математический элемент скобками. |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/function/#imathelement) | Создаёт функцию аргумента, используя данный экземпляр как имя функции. |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/function/#str) | Создаёт функцию аргумента, используя данный экземпляр как имя функции. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Создаёт указанную функцию, используя данный экземпляр как аргумент. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Создаёт указанную функцию, используя данный экземпляр как аргумент. |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Создаёт указанную функцию, используя данный экземпляр как аргумент. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Создаёт указанную функцию, используя данный экземпляр как аргумент и указанный дополнительный аргумент. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Создаёт указанную функцию, используя данный экземпляр как аргумент и указанный дополнительный аргумент. |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Создаёт нижний индекс. |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_subscript/#str) | Создаёт нижний индекс. |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Создаёт верхний индекс. |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_superscript/#str) | Создаёт верхний индекс. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Создаёт нижний и верхний индексы справа. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Создаёт нижний и верхний индексы справа. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Создаёт нижний и верхний индексы слева. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Создаёт нижний и верхний индексы слева. |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/radical/#imathelement) | Указывает математический корень заданной степени от указанного аргумента. |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/radical/#str) | Указывает математический корень заданной степени от указанного аргумента. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Создаёт верхний предел. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Создаёт верхний предел. |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Создаёт нижний предел. |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Создаёт нижний предел. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | Создаёт N-арный оператор. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | Создаёт N-арный оператор. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Создаёт интеграл. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | Создаёт интеграл. |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Создаёт интеграл без пределов. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Создаёт интеграл. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Создаёт интеграл. |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/group/#) | Размещает этот элемент в группе, используя нижнюю фигурную скобку. |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Размещает этот элемент в группе, используя символ группировки, такой как нижняя фигурная скобка или другой. |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/to_border_box/#) | Размещает этот элемент в рамочной коробке. |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Размещает этот элемент в рамочной коробке. |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/to_math_array/#) | Размещает дочерние элементы в вертикальном массиве. |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/accent/#char) | Устанавливает ударный знак (символ над этим элементом). |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/overbar/#) | Устанавливает черту сверху этого элемента. |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/underbar/#) | Устанавливает черту снизу этого элемента. |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/to_box/#) | Помещает этот элемент в невизуальный контейнер (логическую группу) <br/>            который используется для группировки компонентов уравнения или другого экземпляра математического текста.<br/>            Упакованный объект может (например) служить эмулятором оператора с точкой выравнивания или без неё, <br/>            служить точкой разрыва строки или быть сгруппирован так, чтобы не допускать разрыва строк внутри. |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/get_children/#) | Получает дочерние элементы. |
| [`add(self, item)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/add/#imathelement) | Добавляет математический элемент в конец коллекции. |
| [`clear(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/clear/#) | Удаляет все элементы из коллекции. |
| [`contains(self, item)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/contains/#imathelement) | Определяет, содержит ли коллекция определённое значение. |
| [`copy_to(self, array, array_index)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Копирует в указанный массив. |
| [`remove(self, item)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/remove/#imathelement) | Удаляет первое вхождение конкретного объекта из коллекции. |
| [`index_of(self, item)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Определяет индекс конкретного математического элемента в коллекции. |
| [`insert(self, index, item)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Вставляет MathElement в коллекцию по указанному индексу. |
| [`remove_at(self, index)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/remove_at/#int) | Удаляет элемент по указанному индексу в коллекции. |
| [`join_block(self, other)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Объединяет другой математический блок с этим. |
| [`delimit(self, separator_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/delimit/#char) | Разделяет дочерние элементы символом-разделителем (без скобок). |
| [`write_as_math_ml(self, stream)`](/slides/python-net/ru/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Сохраняет содержимое этого [`MathBlock`](/slides/python-net/ru/aspose.slides.mathtext/mathblock) в формате MathML. |

### См. также
* класс [`MathBlock`](/slides/python-net/ru/aspose.slides.mathtext/mathblock)
* класс [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)