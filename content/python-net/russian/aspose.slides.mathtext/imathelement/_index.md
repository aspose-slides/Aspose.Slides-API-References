---
title: IMathElement class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/imathelement/
---
## IMathElement класс

Базовый интерфейс любого математического элемента: дробь, математический текст, функция, выражение с несколькими элементами и т.д.

Тип IMathElement предоставляет следующие члены:

## Методы

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/join/#imathelement) | Соединяет математический элемент и формирует математический блок |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/join/#str) | Соединяет математический текст и формирует математический блок |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/divide/#imathelement) | Создает дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/divide/#str) | Создает дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/divide/#imathelement-mathfractiontypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/divide/#str-mathfractiontypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/enclose/#) | Заключает математический элемент в скобки |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/enclose/#char-char) | Заключает этот элемент в указанные символы, такие как скобки или другие символы, в качестве рамки |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/function/#imathelement) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/function/#str) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/as_argument_of_function/#imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/as_argument_of_function/#str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsofoneargument) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента, и указанный дополнительный аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента, и указанный дополнительный аргумент |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/set_subscript/#imathelement) | Создает нижний индекс |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/set_subscript/#str) | Создает нижний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/set_superscript/#imathelement) | Создает верхний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/set_superscript/#str) | Создает верхний индекс |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Создает нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_right/#str-str) | Создает нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Создает нижний и верхний индексы слева |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/set_sub_superscript_on_the_left/#str-str) | Создает нижний и верхний индексы слева |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/radical/#imathelement) | Указывает математический корень заданной степени из указанного аргумента. |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/radical/#str) | Указывает математический корень заданной степени из указанного аргумента. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/set_upper_limit/#imathelement) | Принимает верхний предел |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/set_upper_limit/#str) | Принимает верхний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/set_lower_limit/#imathelement) | Принимает нижний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/set_lower_limit/#str) | Принимает нижний предел |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Создает N-арный оператор |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/nary/#mathnaryoperatortypes-str-str) | Создает N-арный оператор |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-imathelement-imathelement) | Принимает интеграл |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes) | Принимает интеграл без пределов |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/integral/#mathintegraltypes-str-str) | Принимает интеграл |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/group/#) | Размещает этот элемент в группе, используя нижнюю фигурную скобку |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Размещает этот элемент в группе, используя символ группировки, такой как нижняя фигурная скобка или другой |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/to_border_box/#) | Размещает этот элемент в рамке |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Размещает этот элемент в рамке |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/get_children/#) | Получает дочерние элементы |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/to_math_array/#) | Помещает в вертикальный массив |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/accent/#char) | Устанавливает надстрочный знак (символ над этим элементом) |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/overbar/#) | Устанавливает черту над этим элементом |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/underbar/#) | Устанавливает черту под этим элементом |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathelement/to_box/#) | Размещает этот элемент в невизуальном контейнере (логическая группировка) <br/>            который используется для группировки компонентов уравнения или другого фрагмента математического текста.<br/>            Такой контейнер может (например) выступать в качестве эмулятора оператора с точкой выравнивания или без неё, <br/>            служить точкой разрыва строки или быть сгруппирован так, чтобы не допускать разрывы строк внутри. |

### Смотрите также
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)