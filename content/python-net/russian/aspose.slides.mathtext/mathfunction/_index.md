---
title: MathFunction class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathfunction/
---
## MathFunction класс

Задаёт функцию аргумента.

Наследование:[`MathFunction`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction) → [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)

Тип MathFunction предоставляет следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/__init__/#imathelement-imathelement) | Инициализирует новый экземпляр класса MathFunction. |
| [`__init__(self, func_name, base_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/__init__/#str-imathelement) | Инициализирует новый экземпляр класса MathFunction. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`name`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/name/) | Имя функции<br/>            Например, имена функций: sin и cos |
| [`base`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/base/) | Аргумент функции |

## Методы

| Метод | Описание |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/join/#imathelement) | Объединяет математический элемент и формирует математический блок |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/join/#str) | Объединяет математический текст и формирует математический блок |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/divide/#imathelement) | Создаёт дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/divide/#str) | Создаёт дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/divide/#imathelement-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/divide/#str-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/enclose/#) | Обрамляет математический элемент скобками |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/enclose/#char-char) | Обрамляет математический элемент указанными символами, например скобками или другими символами |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/function/#imathelement) | Принимает функцию от аргумента, используя этот экземпляр в качестве имени функции |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/function/#str) | Принимает функцию от аргумента, используя этот экземпляр в качестве имени функции |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/as_argument_of_function/#imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/as_argument_of_function/#str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsofoneargument) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/set_subscript/#imathelement) | Создаёт нижний индекс |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/set_subscript/#str) | Создаёт нижний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/set_superscript/#imathelement) | Создаёт верхний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/set_superscript/#str) | Создаёт верхний индекс |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#imathelement-imathelement) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_right/#str-str) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#imathelement-imathelement) | Создаёт нижний и верхний индексы слева |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/set_sub_superscript_on_the_left/#str-str) | Создаёт нижний и верхний индексы слева |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/radical/#imathelement) | Указывает математический корень заданной степени из указанного аргумента. |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/radical/#str) | Указывает математический корень заданной степени из указанного аргумента. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/set_upper_limit/#imathelement) | Принимает верхний предел |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/set_upper_limit/#str) | Принимает верхний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/set_lower_limit/#imathelement) | Принимает нижний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/set_lower_limit/#str) | Принимает нижний предел |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-imathelement-imathelement) | Создаёт N-арный оператор |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/nary/#mathnaryoperatortypes-str-str) | Создаёт N-арный оператор |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-imathelement-imathelement) | Принимает интеграл |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes) | Принимает интеграл без пределов |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/integral/#mathintegraltypes-str-str) | Принимает интеграл |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/group/#) | Размещает этот элемент в группе с помощью нижней фигурной скобки |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/group/#char-mathtopbotpositions-mathtopbotpositions) | Размещает этот элемент в группе, используя символ группировки, например нижнюю фигурную скобку или другой |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/to_border_box/#) | Размещает этот элемент в рамке |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Размещает этот элемент в рамке |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/to_math_array/#) | Помещает в вертикальный массив |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/accent/#char) | Устанавливает ударный знак (символ над этим элементом) |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/overbar/#) | Устанавливает черту сверху этого элемента |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/underbar/#) | Устанавливает черту снизу этого элемента |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/to_box/#) | Размещает этот элемент в невидимом контейнере (логическая группировка) <br/>            который используется для группировки компонентов уравнения или другого математического текста.<br/>            Объект в контейнере может (например) выступать как эмулятор оператора с точкой выравнивания или без неё, <br/>            выступать как точка разрыва строки или группироваться так, чтобы не допускать разрывов строк внутри. |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction/get_children/#) | Получить дочерние элементы |

### См. также
* класс [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)
* класс [`MathFunction`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)