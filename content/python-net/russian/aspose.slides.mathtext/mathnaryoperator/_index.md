---
title: MathNaryOperator class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator класс

Указывает N-арный математический объект, такой как суммирование и интеграл. Он состоит из оператора, базы (или операнда) и необязательных верхних и нижних пределов. Примеры N-арных операторов: суммирование, объединение, пересечение, интеграл

**Наследование:**[`MathNaryOperator`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)

Тип MathNaryOperator раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | Создаёт новый экземпляр класса MathNaryOperator. |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | Создаёт новый экземпляр класса MathNaryOperator. |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | Создаёт новый экземпляр класса MathNaryOperator. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`base`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/base/) | Базовый аргумент |
| [`subscript`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/subscript/) | Указывает аргумент нижнего индекса, который, например, в случае интеграла, задаёт нижний предел |
| [`superscript`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/superscript/) | Указывает аргумент верхнего индекса, который, например, в случае интеграла, задаёт верхний предел |
| [`operator`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/operator/) | Символ N-арного оператора<br/>            Например: '∑', '∫' |
| [`limit_location`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/limit_location/) | Расположение пределов (нижний и верхний индексы) |
| [`grow_to_match_operand_height`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | Символ оператора растёт вертикально, чтобы соответствовать высоте операнда |
| [`hide_subscript`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | Скрыть нижний индекс |
| [`hide_superscript`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | Скрыть верхний индекс |

## Методы

| Метод | Описание |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | Объединяет математический элемент и формирует математический блок |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/join/#str) | Объединяет математический текст и формирует математический блок |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | Создаёт дробь с этим числителем и заданным знаменателем |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/divide/#str) | Создаёт дробь с этим числителем и заданным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и заданным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и заданным знаменателем |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/enclose/#) | Ограничивает математический элемент скобками |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | Ограничивает математический элемент указанными символами, например скобками или другими символами-кадрами |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | Принимает функцию аргумента, используя этот экземпляр как имя функции |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/function/#str) | Принимает функцию аргумента, используя этот экземпляр как имя функции |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | Создаёт нижний индекс |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | Создаёт нижний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | Создаёт верхний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | Создаёт верхний индекс |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | Создаёт нижний и верхний индексы слева |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | Создаёт нижний и верхний индексы слева |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | Указывает математический корень указанной степени от заданного аргумента. |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/radical/#str) | Указывает математический корень указанной степени от заданного аргумента. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | Принимает верхний предел |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | Принимает верхний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | Принимает нижний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | Принимает нижний предел |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | Создаёт N-арный оператор |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | Создаёт N-арный оператор |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | Принимает интеграл |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | Принимает интеграл без пределов |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | Принимает интеграл |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/group/#) | Размещает этот элемент в группе, используя нижнюю фигурную скобку |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | Размещает этот элемент в группе, используя символ группировки, например нижнюю фигурную скобку или другой |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | Размещает этот элемент в рамке |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Размещает этот элемент в рамке |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | Размещает в вертикальном массиве |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/accent/#char) | Устанавливает акцент (символ над этим элементом) |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/overbar/#) | Устанавливает черту над этим элементом |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/underbar/#) | Устанавливает черту под этим элементом |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/to_box/#) | Размещает этот элемент в невизуальном контейнере (логическая группировка) <br/>            который используется для группировки компонентов уравнения или другого фрагмента математического текста.<br/>            Объект в контейнере может (например) выступать в роли эмулятора оператора с точкой выравнивания или без неё, <br/>            служить точкой разрыва строки или быть сгруппированным так, чтобы не допускать разрывы строк внутри. |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator/get_children/#) | Получить дочерние элементы |

### См. также
* класс [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)
* класс [`MathNaryOperator`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)