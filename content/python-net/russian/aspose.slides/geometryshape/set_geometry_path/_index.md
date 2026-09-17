---
title: set_geometry_path method
second_title: Aspose.Slides для Python через .NET – справочник API
description: 
type: docs
url: /ru/aspose.slides/geometryshape/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Обновляет геометрию фигуры из объекта [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть относительно левого верхнего угла фигуры. Меняет тип фигуры ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath) | Геометрический путь |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Путь не найден |
| **RuntimeError(Proxy error(ArgumentException))** | Путь пуст |

### См. также
* класс [`GeometryShape`](/slides/python-net/ru/aspose.slides/geometryshape)
* класс [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)