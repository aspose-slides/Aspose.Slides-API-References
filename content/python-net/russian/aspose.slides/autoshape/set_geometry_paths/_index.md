---
title: set_geometry_paths method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/autoshape/set_geometry_paths/
weight: 100
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Обновляет геометрию фигуры из массива [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath). Координаты должны быть относительными к левому верхнему углу фигуры.
Изменяет тип фигуры ([`GeometryShape.shape_type`](/slides/python-net/ru/aspose.slides/geometryshape/shape_type)) на [`ShapeType.CUSTOM`](/slides/python-net/ru/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Массив путей геометрии |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Путь не найден |
| **RuntimeError(Proxy error(ArgumentException))** | Пустой путь |

### Смотрите также
* класс [`AutoShape`](/slides/python-net/ru/aspose.slides/autoshape)
* класс [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)