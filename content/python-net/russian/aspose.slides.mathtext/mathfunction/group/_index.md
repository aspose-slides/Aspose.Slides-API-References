---
title: group method
second_title: Aspose.Slides для Python через .NET API
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathfunction/group/
weight: 80
---
## group(self) {#}
Размещает этот элемент в группе, используя нижнюю фигурную скобку

### Возвращаемое значение

New instance of type [`IMathGroupingCharacter`](/slides/python-net/ru/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self):
    ...
```

## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Размещает этот элемент в группе, используя символ группировки, такой как нижняя фигурная скобка или другой

### Возвращаемое значение

New instance of type [`IMathGroupingCharacter`](/slides/python-net/ru/aspose.slides.mathtext/imathgroupingcharacter)

```python
def group(self, character, position, vertical_justification):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| character | **char** | Символ группировки, такой как НИЖНЯЯ ФИГУРНАЯ СКОБКА (U+23DF) или любой другой |
| position | [`MathTopBotPositions`](/slides/python-net/ru/aspose.slides.mathtext/mathtopbotpositions) | Позиция символа группировки |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ru/aspose.slides.mathtext/mathtopbotpositions) | Вертикальное выравнивание символа группы.<br/><br/>            Указывает выравнивание объекта относительно базовой линии.<br/><br/>            Например, когда символ группы находится над объектом, <br/><br/>            VerticalJustification of Top означает, что верхняя часть объекта находится на базовой линии;<br/><br/>            когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии |

### См. также
* класс [`IMathGroupingCharacter`](/slides/python-net/ru/aspose.slides.mathtext/imathgroupingcharacter)
* класс [`MathFunction`](/slides/python-net/ru/aspose.slides.mathtext/mathfunction)
* перечисление [`MathTopBotPositions`](/slides/python-net/ru/aspose.slides.mathtext/mathtopbotpositions)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)