---
title: add_group_shape method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/shapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Создаёт новую пустую группу фигур и добавляет её в конец коллекции фигур.
            Рамка группы автоматически подстраивается, чтобы вместить любые добавленные в неё фигуры.

### Возвращаемое значение

Новосозданный [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape).



```python
def add_group_shape(self):
    ...
```



## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Создаёт новую группу фигур, преобразует указанное SVG-изображение в отдельные фигуры, и добавляет получившуюся группу в конец коллекции фигур.

### Возвращаемое значение

Новосозданный [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape).



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/ru/aspose.slides/isvgimage) | [`ISvgImage`](/slides/python-net/ru/aspose.slides/isvgimage) содержащий векторный контент для преобразования в фигуры. |
| x | **float** | Координата x рамки группы, в пунктах. |
| y | **float** | Координата y рамки группы, в пунктах. |
| width | **float** | Ширина рамки группы, в пунктах. |
| height | **float** | Высота рамки группы, в пунктах. |



### См. также
* класс [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape)
* класс [`ISvgImage`](/slides/python-net/ru/aspose.slides/isvgimage)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)