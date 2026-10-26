---
title: MathArray class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/matharray/
---
## MathArray класс

Указывает вертикальный массив уравнений или любых математических объектов

**Наследование:**[`MathArray`](/slides/python-net/ru/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)

Тип MathArray раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/__init__/#imathelement) | Создает математический массив и помещает в него указанный элемент |
| [`__init__(self, elements)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`arguments`](/slides/python-net/ru/aspose.slides.mathtext/matharray/arguments/) | Набор элементов массива |
| [`base_justification`](/slides/python-net/ru/aspose.slides.mathtext/matharray/base_justification/) | Указывает выравнивание массива относительно окружающего текста<br/>            Текст за пределами массива может быть выровнен по нижнему, верхнему или центральному краю объекта массива.<br/>            Значение по умолчанию: Center |
| [`maximum_distribution`](/slides/python-net/ru/aspose.slides.mathtext/matharray/maximum_distribution/) | Максимальное распределение<br/>            Когда true, массив растягивается до максимальной ширины содержащего элемента (page, column, cell, etc.). |
| [`object_distribution`](/slides/python-net/ru/aspose.slides.mathtext/matharray/object_distribution/) | Распределение объекта<br/>            Когда true, содержимое массива растягивается до максимальной ширины объекта массива. |
| [`row_spacing_rule`](/slides/python-net/ru/aspose.slides.mathtext/matharray/row_spacing_rule/) | Тип вертикального интервала между элементами массива<br/>            По умолчанию: SingleLineGap |
| [`row_spacing`](/slides/python-net/ru/aspose.slides.mathtext/matharray/row_spacing/) | Интервал между строками массива<br/>            Используется только когда RowSpacingRule установлен в 3 Exactly, в этом случае единицей измерения являются пункты <br/>            или Multiple, в этом случае единицей измерения являются полустроки.<br/>            По умолчанию: 0 |

## Методы

| Метод | Описание |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/join/#imathelement) | Объединяет математический элемент и образует математический блок |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/join/#str) | Объединяет математический текст и образует математический блок |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/divide/#imathelement) | Создает дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/divide/#str) | Создает дробь с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/enclose/#) | Оборачивает математический элемент в скобки |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/enclose/#char-char) | Оборачивает математический элемент в указанные символы, такие как скобки или другие символы как рамку |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/function/#imathelement) | Принимает функцию аргумента, используя этот экземпляр как имя функции |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/function/#str) | Принимает функцию аргумента, используя этот экземпляр как имя функции |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | Принимает указанную функцию, используя этот экземпляр как аргумент |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | Принимает указанную функцию, используя этот экземпляр как аргумент |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | Принимает указанную функцию, используя этот экземпляр как аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Принимает указанную функцию, используя этот экземпляр как аргумент, и указанный дополнительный аргумент |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Принимает указанную функцию, используя этот экземпляр как аргумент, и указанный дополнительный аргумент |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | Создает нижний индекс |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/set_subscript/#str) | Создает нижний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | Создает верхний индекс |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/set_superscript/#str) | Создает верхний индекс |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | Создает нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | Создает нижний и верхний индексы справа |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | Создает нижний и верхний индексы слева |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | Создает нижний и верхний индексы слева |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/radical/#imathelement) | Указывает математический корень заданной степени из указанного аргумента. |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/radical/#str) | Указывает математический корень заданной степени из указанного аргумента. |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | Принимает верхний предел |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/set_upper_limit/#str) | Принимает верхний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | Принимает нижний предел |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/set_lower_limit/#str) | Принимает нижний предел |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | Создает N-арный оператор |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | Создает N-арный оператор |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | Принимает интеграл |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | Принимает интеграл без пределов |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | Принимает интеграл |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | Принимает интеграл |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/group/#) | Размещает этот элемент в группе, используя нижнюю фигурную скобку |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | Размещает этот элемент в группе, используя символ группировки, например нижнюю фигурную скобку или другой |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/to_border_box/#) | Размещает этот элемент в рамочной коробке |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Размещает этот элемент в рамочной коробке |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/to_math_array/#) | Размещает в вертикальном массиве |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/accent/#char) | Устанавливает акцент (символ над этим элементом) |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/overbar/#) | Устанавливает линию сверху этого элемента |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/underbar/#) | Устанавливает линию снизу этого элемента |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/to_box/#) | Размещает этот элемент в невизуальном контейнере (логическая группировка) <br/>            который используется для группировки компонентов уравнения или другого математического текста.<br/>            Объект в коробке может (например) выступать как эмулятор оператора с точкой выравнивания или без неё, <br/>            служить точкой разрыва строки, или быть сгруппирован так, чтобы не допускать разрывы строк внутри. |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/matharray/get_children/#) | Получить дочерние элементы |

### См. также
* класс [`MathArray`](/slides/python-net/ru/aspose.slides.mathtext/matharray)
* класс [`MathElementBase`](/slides/python-net/ru/aspose.slides.mathtext/mathelementbase)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)