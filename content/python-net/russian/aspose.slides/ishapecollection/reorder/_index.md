---
title: reorder method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
Перемещает указанную фигуру в новое положение внутри коллекции фигур.

```python
def reorder(self, index, shape):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой базовый целевой индекс, по которому будет размещена фигура. |
| shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | Объект [`IShape`](/slides/python-net/ru/aspose.slides/ishape), который перемещается внутри коллекции. |

## reorder(self, index, shapes) {#int-listishape}
Перемещает указанные фигуры внутри коллекции фигур, размещая их, начиная с указанного индекса.

```python
def reorder(self, index, shapes):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой базовый целевой индекс, по которому будет размещена первая указанная фигура; <br/><br/>            последующие фигуры располагаются в порядке, заданном в списке. |
| shapes | **List[IShape]** | Один или несколько экземпляров [`IShape`](/slides/python-net/ru/aspose.slides/ishape), перемещаемых внутри коллекции. |

### См. также
* класс [`IShape`](/slides/python-net/ru/aspose.slides/ishape)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)