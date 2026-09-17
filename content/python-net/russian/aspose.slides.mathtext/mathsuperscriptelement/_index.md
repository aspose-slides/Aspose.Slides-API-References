---
title: MathSuperscriptElement class
second_title: Aspose.Slides для Python через .NET API Справка
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathsuperscriptelement/
---
## MathSuperscriptElement класс

Определяет объект надстрочного знака, который состоит из основы и надстрочного знака уменьшенного размера, расположенного выше и справа

**Наследование:**[`MathSuperscriptElement`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement) → [`BaseScript`](/slides/python-net/ru/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)

Тип MathSuperscriptElement раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, base_arg, super_script)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/__init__/#imathelement-imathelement) | Инициализирует новый экземпляр класса MathSuperscriptElement. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`base`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/base/) | Базовый аргумент |
| [`superscript`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/superscript/) | Надстрочный |

## Методы

| Метод | Описание |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/join/#imathelement) | Объединяет математический элемент и формирует математический блок |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/join/#str) | Объединяет математический текст и формирует математический блок |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/divide/#imathelement) | Создает дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/divide/#str) | Создает дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/divide/#imathelement-mathfractiontypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/divide/#str-mathfractiontypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/enclose/#) | Обрамляет математический элемент в скобки |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/enclose/#char-char) | Обрамляет математический элемент в указанные символы, такие как скобки или другие символы в качестве обрамления |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/function/#imathelement) | Создает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/function/#str) | Создает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента, и указанный дополнительный аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента, и указанный дополнительный аргумент |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/set_subscript/#imathelement) | Создает нижний индекс |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/set_subscript/#str) | Создает нижний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/set_superscript/#imathelement) | Создает надстрочный |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/set_superscript/#str) | Создает надстрочный |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Создает нижний и надстрочный индекс справа |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | Создает нижний и надстрочный индекс справа |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Создает нижний и надстрочный индекс слева |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | Creates нижний и надстрочный индекс слева |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/radical/#imathelement) | Задает математический корень указанной степени из заданного аргумента. |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/radical/#str) | Задает математический корень указанной степени из заданного аргумента. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/set_upper_limit/#imathelement) | Принимает верхний предел |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/set_upper_limit/#str) | Принимает верхний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/set_lower_limit/#imathelement) | Принимает нижний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/set_lower_limit/#str) | Принимает нижний предел |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Создает N-арный оператор |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | Создает N-арный оператор |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | Принимает интеграл |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes) | Принимает интеграл без пределов |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/integral/#mathintegraltypes-str-str) | Принимает интеграл |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/group/#) | Размещает этот элемент в группе, используя нижнюю фигурную скобку |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Размещает этот элемент в группе, используя символ группировки, такой как нижняя фигурная скобка или другой |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/to_border_box/#) | Размещает этот элемент в рамке |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Размещает этот элемент в рамке |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/to_math_array/#) | Размещает в вертикальном массиве |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/accent/#char) | Устанавливает акцент (символ над этим элементом) |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/overbar/#) | Устанавливает черту над этим элементом |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/underbar/#) | Устанавливает черту под этим элементом |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/to_box/#) | Размещает этот элемент в невизуальном блоке (логическое группирование) <br/>            который используется для объединения компонентов уравнения или другого экземпляра математического текста.<br/>            Такой упакованный объект может (например) служить эмулятором оператора с точкой выравнивания или без неё, <br/>            служить точкой разрыва строки, или быть сгруппированным так, чтобы не допускать разрывов строк внутри. |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement/get_children/#) | Получить дочерние элементы |


### См. также
* класс [`BaseScript`](/slides/python-net/ru/aspose.slides.mathtext/basescript)
* класс [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)
* класс [`MathSuperscriptElement`](/slides/python-net/ru/aspose.slides.mathtext/mathsuperscriptelement)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)