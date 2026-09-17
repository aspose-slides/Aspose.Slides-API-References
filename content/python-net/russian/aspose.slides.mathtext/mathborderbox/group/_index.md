---
title: group method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathborderbox/group/
weight: 80
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
Размещает этот элемент в группе, используя символ группировки, такой как нижняя фигурная скобка или другой

### Возвращаемое значение

Новый экземпляр типа [`IMathGroupingCharacter`](/slides/python-net/ru/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| character | **char** | Символ группировки, такой как нижняя фигурная скобка (U+23DF) или любой другой |
| position | [`MathTopBotPositions`](/slides/python-net/ru/aspose.slides.mathtext/mathtopbotpositions) | Позиция символа группировки |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ru/aspose.slides.mathtext/mathtopbotpositions) | Вертикальное выравнивание символа группы.<br/><br/>            Задаёт выравнивание объекта относительно базовой линии.<br/><br/>            Например, когда символ группы расположен над объектом, <br/><br/>            VerticalJustification со значением Top означает, что верхняя часть объекта находится на базовой линии;<br/><br/>            когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии |



### См. также
* класс [`IMathGroupingCharacter`](/slides/python-net/ru/aspose.slides.mathtext/imathgroupingcharacter)
* класс [`MathBorderBox`](/slides/python-net/ru/aspose.slides.mathtext/mathborderbox)
* перечисление [`MathTopBotPositions`](/slides/python-net/ru/aspose.slides.mathtext/mathtopbotpositions)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)