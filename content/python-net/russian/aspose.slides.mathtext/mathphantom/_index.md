---
title: MathPhantom class
second_title: Aspose.Slides для Python через .NET: справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathphantom/
---
## MathPhantom класс

Представляет скрытый (phantom) математический объект (<m:phant>), который влияет на расположение дочернего элемента, не обязательно отображая его. Фантом может скрыть базовое выражение, сохраняя его ширину, высоту или глубину для выравнивания формул или резервирования пространства. Видимость и геометрическое поведение управляются свойствами, такими как Show, ZeroWid, ZeroAsc, ZeroDesc и Transp.

**Inheritance:**[`MathPhantom`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)

The MathPhantom type exposes the following members:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | Создаёт новый экземпляр класса [`MathPhantom`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom) <br/> используя указанный базовый математический элемент. |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`base`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/base/) | Базовый аргумент |
| [`show`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/show/) | Получает или задаёт значение, указывающее, отображается ли базовый элемент. |
| [`zero_width`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/zero_width/) | Получает или задаёт значение, указывающее, следует ли считать ширину базового элемента <br/> нулём. |
| [`zero_asc`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/zero_asc/) | Получает или задаёт значение, указывающее, следует ли считать подъём (высоту над базовой линией) <br/> базового элемента нулём. |
| [`zero_desc`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/zero_desc/) | Получает или задаёт значение, указывающее, следует ли считать спуск (глубину ниже базовой линии)<br/> базового элемента нулём. |
| [`transp`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/transp/) | Получает или задаёт значение, указывающее, является ли фантом прозрачным <br/> для правил расстояний, основанных на классах. |

## Методы

| Метод | Описание |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/join/#imathelement) | Объединяет математический элемент и образует математический блок |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/join/#str) | Объединяет математический текст и образует математический блок |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/divide/#imathelement) | Создаёт дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/divide/#str) | Создаёт дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/enclose/#) | Ограничивает математический элемент скобками |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/enclose/#char-char) | Ограничивает математический элемент указанными символами, например скобками или другими символами, в качестве рамки |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/function/#imathelement) | Создаёт функцию аргумента, используя этот экземпляр как имя функции |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/function/#str) | Создаёт функцию аргумента, используя этот экземпляр как имя функции |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | Создаёт указанную функцию, используя этот экземпляр как аргумент |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | Создаёт указанную функцию, используя этот экземпляр как аргумент |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | Создаёт указанную функцию, используя этот экземпляр как аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Создаёт указанную функцию, используя этот экземпляр как аргумент и указанный дополнительный аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Создаёт указанную функцию, используя этот экземпляр как аргумент и указанный дополнительный аргумент |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | Создаёт нижний индекс |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/set_subscript/#str) | Создаёт нижний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | Создаёт верхний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/set_superscript/#str) | Создаёт верхний индекс |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | Создаёт нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | Создаёт нижний и верхний индексы слева |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | Создаёт нижний и верхний индексы слева |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/radical/#imathelement) | Указывает математический корень заданной степени из указанного аргумента. |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/radical/#str) | Указывает математический корень заданной степени из указанного аргумента. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | Создаёт верхний предел |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | Создаёт верхний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | Создаёт нижний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | Создаёт нижний предел |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | Создаёт N-арный оператор |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | Создаёт N-арный оператор |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Создаёт интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | Создаёт интеграл |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | Создаёт интеграл без пределов |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | Создаёт интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | Создаёт интеграл |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/group/#) | Размещает этот элемент в группе, используя нижнюю фигурную скобку |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | Размещает этот элемент в группе, используя символ группировки, например нижнюю фигурную скобку или иной |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/to_border_box/#) | Размещает этот элемент в рамке |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Размещает этот элемент в рамке |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/to_math_array/#) | Размещает в вертикальном массиве |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/accent/#char) | Устанавливает знак ударения (символ над этим элементом) |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/overbar/#) | Устанавливает черту над этим элементом |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/underbar/#) | Устанавливает черту под этим элементом |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/to_box/#) | Размещает этот элемент в невизуальном блоке (логическая группировка) <br/> который используется для группировки компонентов уравнения или другого математического текста.<br/> Объект в коробке может (например) выступать в роли эмулятора оператора с точкой выравнивания или без неё, <br/> служить точкой разрыва строки или быть сгруппированным так, чтобы не допускать разрывов строки внутри. |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom/get_children/#) | Получить дочерние элементы |

### См. также
* класс [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)
* класс [`MathPhantom`](/slides/python-net/ru/aspose.slides.mathtext/mathphantom)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)