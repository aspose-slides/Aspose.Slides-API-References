---
title: MathRightSubSuperscriptElement class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElement класс

Определяет объект Sub-Superscript, который состоит из основания и нижнего и верхнего индексов, размещённых справа от основания.

**Inheritance:**[`MathRightSubSuperscriptElement`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement) → [`BaseScript`](/slides/python-net/ru/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)

Тип MathRightSubSuperscriptElement раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, base_arg, sub_script, super_script)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/__init__/#imathelement-imathelement-imathelement) | Инициализирует новый экземпляр класса MathRightSubSuperscriptElement. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`base`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/base/) | Базовый аргумент |
| [`subscript`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript/) | Аргумент нижнего индекса |
| [`superscript`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript/) | Аргумент верхнего индекса |
| [`align_scripts`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/align_scripts/) | Указывает выравнивание нижнего и верхнего индексов. <br/>            Когда значение true, нижний и верхний индексы выравниваются горизонтально друг относительно друга.<br/>            Когда значение false, они подгоняются к форме основания.<br/>            Значение по умолчанию — false. |

## Методы

| Метод | Описание |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/join/#imathelement) | Объединяет математический элемент и формирует математический блок |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/join/#str) | Объединяет математический текст и формирует математический блок |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#imathelement) | Создаёт дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#str) | Создаёт дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#imathelement-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/divide/#str-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/enclose/#) | Оборачивает математический элемент в скобки |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/enclose/#char-char) | Оборачивает математический элемент в указанные символы, такие как скобки или другие символы, в качестве рамки |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/function/#imathelement) | Создаёт функцию от аргумента, используя этот экземпляр в качестве имени функции |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/function/#str) | Создаёт функцию от аргумента, используя этот экземпляр в качестве имени функции |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#imathelement) | Вызывает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#str) | Вызывает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Вызывает указанную функцию, используя этот экземпляр в качестве аргумента |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Вызывает указанную функцию, используя этот экземпляр в качестве аргумента, и указанный дополнительный аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Вызывает указанную функцию, используя этот экземпляр в качестве аргумента, и указанный дополнительный аргумент |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_subscript/#imathelement) | Создаёт нижний индекс |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_subscript/#str) | Создаёт нижний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_superscript/#imathelement) | Создаёт верхний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_superscript/#str) | Создаёт верхний индекс |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_right/#str-str) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Создаёт нижний и верхний индексы слева |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_sub_superscript_on_the_left/#str-str) | Создаёт нижний и верхний индексы слева |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/radical/#imathelement) | Указывает математический корень заданной степени от указанного аргумента. |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/radical/#str) | Указывает математический корень заданной степени от указанного аргумента. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_upper_limit/#imathelement) | Устанавливает верхний предел |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_upper_limit/#str) | Устанавливает верхний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_lower_limit/#imathelement) | Устанавливает нижний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_lower_limit/#str) | Устанавливает нижний предел |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | Создаёт N-арный оператор |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/nary/#mathnaryoperatortypes-str-str) | Создаёт N-арный оператор |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Берёт интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | Берёт интеграл |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes) | Берёт интеграл без пределов |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | Берёт интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/integral/#mathintegraltypes-str-str) | Берёт интеграл |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/#) | Размещает этот элемент в группе, используя нижнюю фигурную скобку |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Размещает этот элемент в группе, используя группирующий символ, такой как нижняя фигурная скобка или иной |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_border_box/#) | Размещает этот элемент в рамочном контейнере |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Размещает этот элемент в рамочном контейнере |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_math_array/#) | Размещает в вертикальном массиве |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/accent/#char) | Устанавливает ударный знак (символ над этим элементом) |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/overbar/#) | Устанавливает черту над этим элементом |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/underbar/#) | Устанавливает черту под этим элементом |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/to_box/#) | Размещает этот элемент в невизуальном блоке (логическая группировка) <br/>            который используется для группировки компонентов уравнения или других фрагментов математического текста.<br/>            Такой блочный объект может (например) служить эмулятором оператора с точкой выравнивания или без неё, <br/>            служить точкой разрыва строки или быть сгруппирован так, чтобы не разрешать перенесы строки внутри. |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_children/#) | Получить дочерние элементы |

### См. также
* класс [`BaseScript`](/slides/python-net/ru/aspose.slides.mathtext/basescript)
* класс [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)
* класс [`MathRightSubSuperscriptElement`](/slides/python-net/ru/aspose.slides.mathtext/mathrightsubsuperscriptelement)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)