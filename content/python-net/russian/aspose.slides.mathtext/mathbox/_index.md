---
title: MathBox class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathbox/
---
## Класс MathBox

Указывает логическое упаковывание (коробку) математического элемента.
            Например, упакованный объект может служить эмулятором оператора с точкой выравнивания или без неё,
            служить точкой разрыва строки, или быть сгруппированным так, чтобы не допускать разрывов внутри.
            Например, оператор "==" должен быть упакован, чтобы предотвратить разрывы строки.

**Наследование:**[`MathBox`](/slides/python-net/ru/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)

Тип MathBox раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/__init__/#imathelement) | Инициализирует MathBox указанным элементом в качестве аргумента |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`base`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/base/) | Базовый аргумент |
| [`operator_emulator`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/operator_emulator/) | Эмулятор оператора.<br/>            Если true, коробка и её содержимое ведут себя как один оператор и наследуют свойства оператора. <br/>            Это означает, например, что символ может служить точкой разрыва строки и может быть выровнен с другими операторами.<br/>            Эмуляторы операторов часто используются, когда один или несколько глифов комбинируются в оператор, например '=='.<br/>            Значение по умолчанию: false |
| [`no_break`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/no_break/) | Без разрыва<br/>            Это свойство задает свойство "неразрывности" у коробки объекта. Если true, внутри коробки не может происходить разрывов строки.<br/>            Это может быть важно для эмуляторов операторов, состоящих более чем из одного бинарного оператора. <br/>            Если этот элемент не указан, разрывы могут происходить внутри коробки.<br/>            По умолчанию: true |
| [`differential`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/differential/) | Дифференциал<br/>            Если true, коробка действует как дифференциал (например, 𝑑𝑥 в подынтеграле) и получает соответствующее <br/>            горизонтальное пространство для математического дифференциала.<br/>            По умолчанию: false |
| [`alignment_point`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/alignment_point/) | Если true, этот эмулятор оператора служит точкой выравнивания; то есть, <br/>            назначенные точки выравнивания в других уравнениях могут быть выровнены с ним.<br/>            По умолчанию: false |
| [`explicit_break`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/explicit_break/) | Явный разрыв указывает, есть ли разрыв строки в начале объекта Box, <br/>            чтобы строка перенеслась в начале объекта Box.<br/>            Указывает номер оператора в предыдущей строке математического текста, который<br/>            будет использован как точка выравнивания для текущей строки математического текста<br/>            возможные значения: 1..255<br/>            По умолчанию: 0 (нет явного разрыва) |

## Методы

| Метод | Описание |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/join/#imathelement) | Объединяет математический элемент и создаёт математический блок |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/join/#str) | Объединяет математический текст и создаёт математический блок |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/divide/#imathelement) | Создаёт дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/divide/#str) | Создаёт дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/enclose/#) | Обрамляет математический элемент в круглых скобках |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/enclose/#char-char) | Обрамляет математический элемент указанными символами, такими как скобки или другими символами |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/function/#imathelement) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/function/#str) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | Создаёт нижний индекс |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/set_subscript/#str) | Создаёт нижний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | Создаёт верхний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/set_superscript/#str) | Создаёт верхний индекс |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Создаёт нижний и верхний индексы слева |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | Создаёт нижний и верхний индексы слева |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/radical/#imathelement) | Указывает математический корень указанной степени из заданного аргумента. |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/radical/#str) | Указывает математический корень указанной степени из заданного аргумента. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | Принимает верхний предел |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | Принимает верхний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | Принимает нижний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | Принимает нижний предел |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Создаёт N-арный оператор |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | Создаёт N-арный оператор |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | Принимает интеграл |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | Принимает интеграл без пределов |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | Принимает интеграл |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/group/#) | Размещает этот элемент в группе, используя нижнюю фигурную скобку |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Размещает этот элемент в группе, используя символ группировки, такой как нижняя фигурная скобка или другой |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/to_border_box/#) | Размещает этот элемент в рамке |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Размещает этот элемент в рамке |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/to_math_array/#) | Размещает в вертикальном массиве |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/accent/#char) | Устанавливает ударный знак (символ над этим элементом) |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/overbar/#) | Устанавливает черту над этим элементом |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/underbar/#) | Устанавливает черту под этим элементом |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/to_box/#) | Размещает этот элемент в невизуальной коробке (логическая группировка) <br/>            которая используется для группировки компонентов уравнения или другого фрагмента математического текста.<br/>            Упакованный объект может, например, служить эмулятором оператора с точкой выравнивания или без неё, <br/>            служить точкой разрыва строки, или быть сгруппированным так, чтобы не допускать разрывы внутри. |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathbox/get_children/#) | Получить дочерние элементы |

### См. также
* класс [`MathBox`](/slides/python-net/ru/aspose.slides.mathtext/mathbox)
* класс [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)