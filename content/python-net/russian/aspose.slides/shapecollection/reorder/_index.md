---
title: reorder method
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/shapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
Перемещает указанную shape в новое положение в коллекции shape.


```python
def reorder(self, index, shape):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому будет размещена shape. |
| shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | Объект [`IShape`](/slides/python-net/ru/aspose.slides/ishape) для перемещения в коллекцию. |


## reorder(self, index, shapes) {#int-listishape}
Перемещает указанные shapes в коллекцию shape, размещая их, начиная с указанного индекса.


```python
def reorder(self, index, shapes):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому будет размещена первая указанная shape; <br/><br/>            последующие shapes располагаются в указанном порядке. |
| shapes | **List[IShape]** | Один или несколько экземпляров [`IShape`](/slides/python-net/ru/aspose.slides/ishape) для перемещения в коллекцию. |



### См. также
* класс [`IShape`](/slides/python-net/ru/aspose.slides/ishape)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)