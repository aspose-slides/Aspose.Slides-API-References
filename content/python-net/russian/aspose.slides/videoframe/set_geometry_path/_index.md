---
title: set_geometry_path method
second_title: Aspose.Slides для Python через .NET справка API
description: 
type: docs
url: /ru/aspose.slides/videoframe/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Обновляет геометрию фигуры из объекта [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть относительно левого верхнего угла фигуры.
Изменяет тип фигуры ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM).


```python
def set_geometry_path(self, geometry_path):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath) | Путь геометрии |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Путь не найден |
| **RuntimeError(Proxy error(ArgumentException))** | Найден пустой путь |



### См. также
* класс [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath)
* класс [`VideoFrame`](/slides/python-net/ru/aspose.slides/videoframe)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)