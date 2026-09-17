---
title: MathBorderBox class
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox класс

Draws a rectangular or some other border around the IMathElement.

**Inheritance:**[`MathBorderBox`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox) → [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)

The MathBorderBox type exposes the following members:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/__init__/#imathelement) | Creates MathBorderBox element with rectangular border |
| [`__init__(self, element, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/__init__/#imathelement-bool-bool-bool-bool-bool-bool-bool-bool) | Creates MathBorderBox element |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`base`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/base/) | Базовый аргумент |
| [`hide_top`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/hide_top/) | Hide Top Edge (по умолчанию false) — указывает скрытое или отображённое состояние верхнего края рамки. |
| [`hide_bottom`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/hide_bottom/) | Hide Bottom Edge (по умолчанию false) — указывает скрытое или отображённое состояние нижнего края рамки. |
| [`hide_left`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/hide_left/) | Hide Left Edge (по умолчанию false) — указывает скрытое или отображённое состояние левого края рамки. |
| [`hide_right`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/hide_right/) | Hide Right Edge (по умолчанию false) — указывает скрытое или отображённое состояние правого края рамки. |
| [`strikethrough_horizontal`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/strikethrough_horizontal/) | Strikethrough Horizontal (по умолчанию false) — указывает скрытое или отображённое состояние горизонтальной линии перечёркивания. |
| [`strikethrough_vertical`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/strikethrough_vertical/) | Strikethrough Vertical (по умолчанию false) — указывает скрытое или отображённое состояние вертикальной линии перечёркивания. |
| [`strikethrough_bottom_left_to_top_right`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/strikethrough_bottom_left_to_top_right/) | Strikethrough Bottom-Left to Top-Right (по умолчанию false).<br/>            Указывает скрытое или отображённое состояние диагональной линии перечёркивания от нижнего левого угла к верхнему правому углу рамки. |
| [`strikethrough_top_left_to_bottom_right`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/strikethrough_top_left_to_bottom_right/) | Strikethrough Top-Left to Bottom-Right (по умолчанию false).<br/>            Указывает скрытое или отображённое состояние диагональной линии перечёркивания от верхнего левого угла к нижнему правому углу рамки. |

## Методы

| Метод | Описание |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/join/#imathelement) | Объединяет математический элемент и формирует математический блок |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/join/#str) | Объединяет математический текст и формирует математический блок |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/divide/#imathelement) | Создаёт дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/divide/#str) | Создаёт дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/divide/#imathelement-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/divide/#str-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/enclose/#) | Обрамляет математический элемент в скобки |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/enclose/#char-char) | Обрамляет математический элемент в указанные символы, такие как скобки или другие символы, в качестве рамки |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/function/#imathelement) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/function/#str) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsofoneargument) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/set_subscript/#imathelement) | Создаёт нижний индекс |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/set_subscript/#str) | Создаёт нижний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/set_superscript/#imathelement) | Создаёт верхний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/set_superscript/#str) | Создаёт верхний индекс |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#str-str) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Создаёт нижний и верхний индексы слева |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#str-str) | Создаёт нижний и верхний индексы слева |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/radical/#imathelement) | Указывает математический корень заданной степени от указанного аргумента. |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/radical/#str) | Указывает математический корень заданной степени от указанного аргумента. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/set_upper_limit/#imathelement) | Берёт верхний предел |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/set_upper_limit/#str) | Берёт верхний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/set_lower_limit/#imathelement) | Берёт нижний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/set_lower_limit/#str) | Берёт нижний предел |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | Создаёт N-арный оператор |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-str-str) | Создаёт N-арный оператор |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Берёт интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement) | Берёт интеграл |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes) | Берёт интеграл без пределов |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Берёт интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str) | Берёт интеграл |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/group/#) | Помещает этот элемент в группу, используя нижнюю фигурную скобку |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Помещает этот элемент в группу, используя символ группировки, такой как нижняя фигурная скобка или другой |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/to_border_box/#) | Помещает этот элемент в рамку |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Помещает этот элемент в рамку |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/to_math_array/#) | Размещает в вертикальном массиве |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/accent/#char) | Устанавливает ударный знак (символ над этим элементом) |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/overbar/#) | Устанавливает черту над этим элементом |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/underbar/#) | Устанавливает черту под этим элементом |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/to_box/#) | Помещает этот элемент в невизуальную коробку (логическая группировка) <br/>            которая используется для группировки компонентов уравнения или другого экземпляра математического текста.<br/>            Объект в коробке может (например) служить эмулятором оператора с точкой выравнивания или без неё, <br/>            служить точкой разрыва строки или быть сгруппированным так, чтобы не допускать разрывов строк внутри. |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox/get_children/#) | Получает дочерние элементы |

### Смотрите также
* класс [`MathBorderBox`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox)
* класс [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)