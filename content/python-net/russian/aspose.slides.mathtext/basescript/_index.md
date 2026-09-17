---
title: BaseScript class
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.mathtext/basescript/
---
## BaseScript класс

Math script

**Наследование:**[`BaseScript`](/slides/python-net/ru/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)

Тип BaseScript раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`base`](/slides/python-net/ru/aspose.slides.mathtext/basescript/base/) | Базовый аргумент |

## Методы

| Метод | Описание |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/join/#imathelement) | Объединяет математический элемент и формирует математический блок |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/join/#str) | Объединяет математический текст и формирует математический блок |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/divide/#imathelement) | Создает дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/divide/#str) | Создает дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/divide/#imathelement-mathfractiontypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/divide/#str-mathfractiontypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/enclose/#) | Помещает математический элемент в скобки |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/enclose/#char-char) | Помещает математический элемент в указанные символы, такие как скобки или другие символы, в качестве рамки |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/function/#imathelement) | Принимает функцию аргумента, используя этот экземпляр как имя функции |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/function/#str) | Принимает функцию аргумента, используя этот экземпляр как имя функции |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/as_argument_of_function/#imathelement) | Принимает указанную функцию, используя этот экземпляр как аргумент |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/as_argument_of_function/#str) | Принимает указанную функцию, используя этот экземпляр как аргумент |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/as_argument_of_function/#mathfunctionsofoneargument) | Принимает указанную функцию, используя этот экземпляр как аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Принимает указанную функцию, используя этот экземпляр как аргумент и указанный дополнительный аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Принимает указанную функцию, используя этот экземпляр как аргумент и указанный дополнительный аргумент |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/set_subscript/#imathelement) | Создает нижний индекс |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/set_subscript/#str) | Создает нижний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/set_superscript/#imathelement) | Создает верхний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/set_superscript/#str) | Создает верхний индекс |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/set_sub_superscript_on_the_right/#imathelement-imathelement) | Создает нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/set_sub_superscript_on_the_right/#str-str) | Создает нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/set_sub_superscript_on_the_left/#imathelement-imathelement) | Создает нижний и верхний индексы слева |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/set_sub_superscript_on_the_left/#str-str) | Создает нижний и верхний индексы слева |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/radical/#imathelement) | Задает математический корень заданной степени из указанного аргумента |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/radical/#str) | Задает математический корень заданной степени из указанного аргумента |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/set_upper_limit/#imathelement) | Принимает верхний предел |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/set_upper_limit/#str) | Принимает верхний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/set_lower_limit/#imathelement) | Принимает нижний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/set_lower_limit/#str) | Принимает нижний предел |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/nary/#mathnaryoperatortypes-imathelement-imathelement) | Создает N-арный оператор |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/nary/#mathnaryoperatortypes-str-str) | Создает N-арный оператор |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/integral/#mathintegraltypes-imathelement-imathelement) | Принимает интеграл |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/integral/#mathintegraltypes) | Принимает интеграл без пределов |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/integral/#mathintegraltypes-str-str-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/integral/#mathintegraltypes-str-str) | Принимает интеграл |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/group/#) | Размещает этот элемент в группе, используя нижнюю фигурную скобку |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/group/#char-mathtopbotpositions-mathtopbotpositions) | Размещает этот элемент в группе, используя группирующий символ, например нижнюю фигурную скобку или иной |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/to_border_box/#) | Размещает этот элемент в рамке-коробке |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Размещает этот элемент в рамке-коробке |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/to_math_array/#) | Размещает в вертикальном массиве |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/accent/#char) | Устанавливает знак надстрочника (символ над этим элементом) |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/overbar/#) | Устанавливает черту над этим элементом |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/underbar/#) | Устанавливает черту под этим элементом |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/to_box/#) | Размещает этот элемент в невизуальном контейнере (логическая группировка), который используется для группировки компонентов уравнения или другого экземпляра математического текста.<br/>            Объект в контейнере может (например) служить эмулятором оператора с точкой выравнивания или без неё, служить точкой разрыва строки или быть сгруппированным так, чтобы не допускать разрывов строки внутри. |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/basescript/get_children/#) |  |

### См. также
* класс [`BaseScript`](/slides/python-net/ru/aspose.slides.mathtext/basescript)
* класс [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)