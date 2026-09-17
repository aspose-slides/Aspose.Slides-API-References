---
title: group method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathnaryoperator/group/
weight: 80
---
## group(self) {#}
Помещает этот элемент в группу, используя закрывающую фигурную скобку снизу

### Возвращаемое значение

Новый экземпляр типа [`IMathGroupingCharacter`](/slides/python-net/ru/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self):
    ...
```



## group(self, character, position, vertical_justification) {#char-mathtopbotpositions-mathtopbotpositions}
Помещает этот элемент в группу, используя символ группировки, такой как закрывающая фигурная скобка снизу или иной

### Возвращаемое значение

Новый экземпляр типа [`IMathGroupingCharacter`](/slides/python-net/ru/aspose.slides.mathtext/imathgroupingcharacter)



```python
def group(self, character, position, vertical_justification):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| character | **char** | Символ группировки, такой как BOTTOM CURLY BRACKET (U+23DF) или любой другой |
| position | [`MathTopBotPositions`](/slides/python-net/ru/aspose.slides.mathtext/mathtopbotpositions) | Позиция символа группировки |
| vertical_justification | [`MathTopBotPositions`](/slides/python-net/ru/aspose.slides.mathtext/mathtopbotpositions) | Вертикальное выравнивание символа группировки.<br/><br/>            Указывает выравнивание объекта относительно базовой линии.<br/><br/>            Например, когда символ группировки находится над объектом, <br/><br/>            VerticalJustification of Top обозначает, что верхняя часть объекта находится на базовой линии;<br/><br/>            когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии |



### См. также
* класс [`IMathGroupingCharacter`](/slides/python-net/ru/aspose.slides.mathtext/imathgroupingcharacter)
* класс [`MathNaryOperator`](/slides/python-net/ru/aspose.slides.mathtext/mathnaryoperator)
* перечисление [`MathTopBotPositions`](/slides/python-net/ru/aspose.slides.mathtext/mathtopbotpositions)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)