---
title: add_group_shape method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Создаёт новую пустую групповую форму и добавляет её в конец коллекции фигур.  
Рамка группы автоматически подгоняется под любые добавленные в неё формы.

### Возвращаемое значение

Созданный [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape).



```python
def add_group_shape(self):
    ...
```



## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Создаёт новую групповую форму, преобразует указанный SVG-изображение в отдельные формы и добавляет полученную группу в конец коллекции фигур.

### Возвращаемое значение

Созданный [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape).



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/ru/aspose.slides/isvgimage) | [`ISvgImage`](/slides/python-net/ru/aspose.slides/isvgimage), содержащий векторный контент для преобразования в формы. |
| x | **float** | Координата x рамки группы, в пунктах. |
| y | **float** | Координата y рамки группы, в пунктах. |
| width | **float** | Ширина рамки группы, в пунктах. |
| height | **float** | Высота рамки группы, в пунктах. |



### См. также
* класс [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* класс [`ISvgImage`](/slides/python-net/ru/aspose.slides/isvgimage)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)