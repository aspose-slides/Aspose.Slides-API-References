---
title: group method
second_title: Справка API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathmatrix/group/
weight: 110
---
## group(self) {#}
Размещает этот элемент в группе, используя нижнюю фигурную скобку

### Возвращаемое значение

Новый экземпляр типа [`IMathGroupingCharacter`](/slides/python-net/ru/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Размещает этот элемент в группе, используя символ группировки, например нижнюю фигурную скобку или другой

### Возвращаемое значение

Новый экземпляр типа [`IMathGroupingCharacter`](/slides/python-net/ru/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| character | **char** | Символ группировки, например НИЖНЯЯ ФИГУРНАЯ СКОБКА (U+23DF) или любой другой |
| position | [`MathTopBotPositions`](/slides/python-net/ru/aspose.slides.mathtext/mathtopbotpositions) | Позиция символа группировки |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ru/aspose.slides.mathtext/mathtopbotpositions) | Вертикальное выравнивание символа группировки.<br/><br/>            Указывает выравнивание объекта относительно базовой линии.<br/><br/>            Например, когда символ группировки находится над объектом, <br/><br/>            VerticalJustification со значением Top указывает, что верхняя часть объекта находится на базовой линии;<br/><br/>            когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии |



### Смотрите также
* класс [`IMathGroupingCharacter`](/slides/python-net/ru/aspose.slides.mathtext/imathgroupingcharacter)
* класс [`MathMatrix`](/slides/python-net/ru/aspose.slides.mathtext/mathmatrix)
* перечисление [`MathTopBotPositions`](/slides/python-net/ru/aspose.slides.mathtext/mathtopbotpositions)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)