---
title: IMathBox class
second_title: Aspose.Slides для Python через .NET: справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/imathbox/
---
## IMathBox класс

Указывает логическую упаковку (компоновку) математического элемента.  
            Например, упакованный объект может выступать в роли эмулятора оператора с точкой выравнивания или без неё,  
            служить точкой разрыва строки, либо быть сгруппированным так, чтобы внутри него не допускались разрывы строк.  
            Например, оператор "==" следует упаковать, чтобы предотвратить разрывы строк.

The IMathBox type exposes the following members:

## Свойства

| Property | Description |
| :- | :- |
| [`base`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/base/) | Базовый аргумент |
| [`operator_emulator`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/operator_emulator/) | Эмулятор оператора.<br/>            Если значение true, коробка и её содержимое ведут себя как один оператор и наследуют свойства оператора. <br/>            Это означает, например, что символ может служить точкой разрыва строки и может быть выровнен с другими операторами.<br/>            Эмуляторы операторов часто используются, когда один или несколько глифов объединяются в оператор, например '=='.<br/>            Значение по умолчанию: false |
| [`no_break`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/no_break/) | Без разрыва.<br/>            Это свойство задаёт параметр «неразрывности» для коробки объекта. Если значение true, внутри коробки не может произойти разрыв строки.<br/>            Это может быть важно для эмуляторов операторов, состоящих более чем из одного бинарного оператора.<br/>            Когда этот элемент не указан, разрывы могут происходить внутри коробки.<br/>            Значение по умолчанию: true |
| [`differential`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/differential/) | Дифференциал.<br/>            Если значение true, коробка действует как дифференциал (например, 𝑑𝑥 в подинтеграле) и получает соответствующий <br/>            горизонтальный интервал для математического дифференциала.<br/>            Значение по умолчанию: false |
| [`alignment_point`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/alignment_point/) | Если значение true, этот эмулятор оператора служит точкой выравнивания; то есть, <br/>            назначенные точки выравнивания в других уравнениях могут быть выровнены с ним.<br/>            Значение по умолчанию: false |
| [`explicit_break`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/explicit_break/) | Явный разрыв указывает, есть ли разрыв строки в начале объекта Box, <br/>            так что строка будет перенесена в начале объекта коробки.<br/>            Указывает номер оператора в предыдущей строке математического текста, который <br/>            будет использован в качестве точки выравнивания для текущей строки математического текста.<br/>            Возможные значения: 1..255<br/>            Значение по умолчанию: 0 (нет явного разрыва) |

## Методы

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/ru/aspose.slides.mathtext/imathbox/to_box/#) |  |


### См. также
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)