---
title: set_geometry_path method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.smartart/smartartshape/set_geometry_path/
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
| geometry_path | [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath) | Geometry path |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Путь не найден |
| **RuntimeError(Proxy error(ArgumentException))** | Найден пустой путь |



### См. также
* класс [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath)
* класс [`SmartArtShape`](/slides/python-net/ru/aspose.slides.smartart/smartartshape)
* модуль [`aspose.slides.smartart`](/slides/python-net/ru/aspose.slides.smartart)
* библиотека [`Aspose.Slides`](/slides/python-net)