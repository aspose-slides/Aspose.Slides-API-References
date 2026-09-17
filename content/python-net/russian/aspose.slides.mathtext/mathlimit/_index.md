---
title: MathLimit class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathlimit/
---
## MathLimit класс

Определяет объект Limit, состоящий из текста на базовой линии и уменьшенного текста непосредственно над ней или под ней.

**Наследование:**[`MathLimit`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit) → [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)

Тип MathLimit предоставляет следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, base_arg, limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement-bool) | Инициализирует новый экземпляр класса MathLimit. |
| [`__init__(self, base_arg, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement) | Инициализирует новый экземпляр класса MathLimit с нижним пределом. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`base`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/base/) | Базовый аргумент |
| [`limit`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/limit/) | Аргумент предела |
| [`upper_limit`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/upper_limit/) | Указывает верхний или нижний предел |

## Методы

| Метод | Описание |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/join/#imathelement) | Объединяет математический элемент и формирует математический блок |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/join/#str) | Объединяет математический текст и формирует математический блок |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/divide/#imathelement) | Создаёт дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/divide/#str) | Создаёт дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/divide/#imathelement-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/divide/#str-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/enclose/#) | Обрамляет математический элемент скобками |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/enclose/#char-char) | Обрамляет математический элемент указанными символами, например скобками или другими символами |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/function/#imathelement) | Создаёт функцию аргумента, используя этот объект в качестве имени функции |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/function/#str) | Создаёт функцию аргумента, используя этот объект в качестве имени функции |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/as_argument_of_function/#imathelement) | Создаёт указанную функцию, используя этот объект в качестве аргумента |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/as_argument_of_function/#str) | Создаёт указанную функцию, используя этот объект в качестве аргумента |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsofoneargument) | Создаёт указанную функцию, используя этот объект в качестве аргумента |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Создаёт указанную функцию, используя этот объект в качестве аргумента и указанный дополнительный аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Создаёт указанную функцию, используя этот объект в качестве аргумента и указанный дополнительный аргумент |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/set_subscript/#imathelement) | Создаёт нижний индекс |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/set_subscript/#str) | Создаёт нижний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/set_superscript/#imathelement) | Создаёт верхний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/set_superscript/#str) | Создаёт верхний индекс |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#imathelement-imathelement) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#str-str) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#imathelement-imathelement) | Создаёт нижний и верхний индексы слева |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#str-str) | Создаёт нижний и верхний индексы слева |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/radical/#imathelement) | Указывает математический корень заданной степени из указанного аргумента |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/radical/#str) | Указывает математический корень заданной степени из указанного аргумента |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/set_upper_limit/#imathelement) | Принимает верхний предел |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/set_upper_limit/#str) | Принимает верхний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/set_lower_limit/#imathelement) | Принимает нижний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/set_lower_limit/#str) | Принимает нижний предел |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-imathelement-imathelement) | Создаёт N-арный оператор |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-str-str) | Создаёт N-арный оператор |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Создаёт интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement) | Создаёт интеграл |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes) | Создаёт интеграл без пределов |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str-mathlimitlocations) | Создаёт интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str) | Создаёт интеграл |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/group/#) | Размещает этот элемент в группе, используя нижнюю фигурную скобку |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/group/#char-mathtopbotpositions-mathtopbotpositions) | Размещает этот элемент в группе, используя символ группировки, например нижнюю фигурную скобку или другой |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/to_border_box/#) | Размещает этот элемент в рамке |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Размещает этот элемент в рамке |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/to_math_array/#) | Размещает в вертикальном массиве |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/accent/#char) | Устанавливает надстрочный знак (символ над этим элементом) |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/overbar/#) | Устанавливает черту над этим элементом |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/underbar/#) | Устанавливает черту под этим элементом |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/to_box/#) | Размещает этот элемент в невизуальном блоке (логическая группировка) <br/>            который используется для группировки компонентов уравнения или другого фрагмента математического текста.<br/>            Такой блок может (например) служить эмулятором оператора с точкой выравнивания или без неё, <br/>            служить точкой разрыва строки или группироваться таким образом, чтобы не допускать разрывов строк внутри. |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit/get_children/#) | Получает дочерние элементы |

### См. также
* класс [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)
* класс [`MathLimit`](/slides/python-net/ru/aspose.slides.mathtext/mathlimit)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)