---
title: MathSubscriptElement class
second_title: Справка API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathsubscriptelement/
---
## MathSubscriptElement класс

Specifies the subscript object, which consists of a base 
            and a reduced-size subscript placed below and to the right.

**Inheritance:**[`MathSubscriptElement`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement) → [`BaseScript`](/slides/python-net/ru/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)

Тип MathSubscriptElement раскрывает следующие члены:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self, base_arg, sub_script)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/__init__/#imathelement-imathelement) | Инициализирует новый экземпляр класса MathSubscriptElement. |

## Properties

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/base/) | Базовый аргумент |
| [`subscript`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/subscript/) | Подстрочный |

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/join/#imathelement) | Объединяет математический элемент и формирует математический блок |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/join/#str) | Объединяет математический текст и формирует математический блок |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/divide/#imathelement) | Создает дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/divide/#str) | Создает дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/divide/#imathelement-mathfractiontypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/divide/#str-mathfractiontypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/enclose/#) | Обрамляет математический элемент в круглые скобки |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/enclose/#char-char) | Обрамляет математический элемент в указанных символах, таких как скобки или другие символы в качестве рамки |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/function/#imathelement) | Создает функцию аргумента, используя данный экземпляр как имя функции |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/function/#str) | Создает функцию аргумента, используя данный экземпляр как имя функции |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#imathelement) | Принимает указанную функцию, используя данный экземпляр как аргумент |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#str) | Принимает указанную функцию, используя данный экземпляр как аргумент |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Принимает указанную функцию, используя данный экземпляр как аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Принимает указанную функцию, используя данный экземпляр как аргумент и указанный дополнительный аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Принимает указанную функцию, используя данный экземпляр как аргумент и указанный дополнительный аргумент |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/set_subscript/#imathelement) | Создает подстрочный индекс |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/set_subscript/#str) | Создает подстрочный индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/set_superscript/#imathelement) | Создает надстрочный индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/set_superscript/#str) | Создает надстрочный индекс |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Создает подстрочный и надстрочный индексы справа |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_right/#str-str) | Создает подстрочный и надстрочный индексы справа |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Создает подстрочный и надстрочный индексы слева |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_left/#str-str) | Создает подстрочный и надстрочный индексы слева |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/radical/#imathelement) | Указывает математический корень заданной степени из указанного аргумента. |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/radical/#str) | Указывает математический корень заданной степени из указанного аргумента. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/set_upper_limit/#imathelement) | Берет верхний предел |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/set_upper_limit/#str) | Берет верхний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/set_lower_limit/#imathelement) | Берет нижний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/set_lower_limit/#str) | Берет нижний предел |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Создает N-арный оператор |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/nary/#mathnaryoperatortypes-str-str) | Создает N-арный оператор |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Берет интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | Берет интеграл |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes) | Берет интеграл без пределов |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Берет интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-str-str) | Берет интеграл |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/group/#) | Размещает этот элемент в группе, используя нижнюю фигурную скобку |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Размещает этот элемент в группе, используя группирующий символ, такой как нижняя фигурная скобка или другой |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/to_border_box/#) | Размещает этот элемент в рамке |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Размещает этот элемент в рамке |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/to_math_array/#) | Размещает в вертикальном массиве |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/accent/#char) | Устанавливает акцент (символ над этим элементом) |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/overbar/#) | Устанавливает черту над этим элементом |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/underbar/#) | Устанавливает черту под этим элементом |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/to_box/#) | Размещает этот элемент в невидимом блоке (логическая группировка) <br/>            который используется для группировки компонентов уравнения или другого фрагмента математического текста.<br/>            Объект в рамке может (например) служить в качестве эмулятора оператора с точкой выравнивания или без неё, <br/>            служить в качестве точки разрыва строки, либо быть сгруппированным так, чтобы не позволять разрывы строк внутри. |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement/get_children/#) | Получает дочерние элементы |


### См. также
* класс [`BaseScript`](/slides/python-net/ru/aspose.slides.mathtext/basescript)
* класс [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)
* класс [`MathSubscriptElement`](/slides/python-net/ru/aspose.slides.mathtext/mathsubscriptelement)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)