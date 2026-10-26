---
title: MathDelimiter class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter класс

Определяет объект разделителя, состоящий из открывающих и закрывающих символов (например, круглые скобки, фигурные скобки, квадратные скобки и вертикальные черты), а также одного или нескольких математических элементов внутри, разделённых указанным символом. Примеры: (𝑥2); [𝑥2|𝑦2]

**Наследование:**[`MathDelimiter`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)

Тип MathDelimiter предоставляет следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Инициализирует MathDelimiter указанным элементом в качестве единственного базового аргумента |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`arguments`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/arguments/) | Один или несколько математических элементов, разделённых символами разделителя |
| [`beginning_character`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Символ начала разделителя указывает начальный, то есть открывающий, символ разделителя. <br/>            Математические разделители — это охватывающие символы, такие как круглые скобки, квадратные скобки и фигурные скобки.<br/>            По умолчанию: '(' |
| [`separator_character`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/separator_character/) | Символ-разделитель разделителя определяет символ, который разделяет аргументы в объекте разделителя. <br/>            По умолчанию: '\|'. |
| [`ending_character`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/ending_character/) | Символ окончания разделителя указывает конечный, то есть закрывающий, символ разделителя. <br/>            Математические разделители — это охватывающие символы, такие как круглые скобки, квадратные скобки и фигурные скобки.<br/>            По умолчанию: ')' |
| [`grow_to_match_operand_height`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter<br/>            Когда значение true, разделители растут вертикально, чтобы соответствовать высоте своего операнда.<br/>            Значение по умолчанию — true |
| [`delimiter_shape`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Указывает форму разделителей в объекте разделителя. <br/>            Когда значение MathDelimiterShape.Centered, разделители центрируются относительно математической оси текста <br/>            и при этом подгоняются под полную высоту их содержимого.<br/>            Когда значение MathDelimiterShape.Match, их высота и форма изменяются так, чтобы точно соответствовать содержимому. |

## Методы

| Метод | Описание |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Объединяет математический элемент и формирует математический блок |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/join/#str) | Объединяет математический текст и формирует математический блок |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Создаёт дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/divide/#str) | Создаёт дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Охватывает математический элемент указанными символами, например скобками или другими символами в качестве рамки |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/enclose/#) | Охватывает математический элемент в скобках |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/function/#str) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента, и указанный дополнительный аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента, и указанный дополнительный аргумент |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Создаёт нижний индекс |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Создаёт нижний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Создаёт верхний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Создаёт верхний индекс |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Создаёт нижний и верхний индексы слева |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Создаёт нижний и верхний индексы слева |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Указывает математический корень заданной степени из указанного аргумента. |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/radical/#str) | Указывает математический корень заданной степени из указанного аргумента. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Принимает верхний предел |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Принимает верхний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Принимает нижний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Принимает нижний предел |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | Создаёт N-арный оператор |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | Создаёт N-арный оператор |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | Принимает интеграл |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Принимает интеграл без пределов |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | Принимает интеграл |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/group/#) | Размещает этот элемент в группе, используя нижнюю фигурную скобку |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Размещает этот элемент в группе, используя символ группировки, такой как нижняя фигурная скобка или другой |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Размещает этот элемент в рамочном блоке |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Размещает этот элемент в рамочном блоке |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Размещает в вертикальном массиве |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/accent/#char) | Устанавливает знак ударения (символ над этим элементом) |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/overbar/#) | Устанавливает черту над этим элементом |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/underbar/#) | Устанавливает черту под этим элементом |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/to_box/#) | Размещает этот элемент в невизуальном блоке (логическая группировка) <br/>            который используется для группировки компонентов уравнения или другого экземпляра математического текста.<br/>            Объект в блоке может (например) выступать в качестве эмулятора оператора с точкой выравнивания или без неё, <br/>            служить точкой разрыва строки или группироваться так, чтобы не допускать разрывов строк внутри. |
| [`delimit(self, separator_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Разделяет аргументы, используя указанный символ разделителя |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter/get_children/#) | Получает дочерние элементы |


### Смотрите также
* класс [`MathDelimiter`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter)
* класс [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)