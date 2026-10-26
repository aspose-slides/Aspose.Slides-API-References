---
title: set_geometry_path method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET API
description: 
type: docs
url: /pl/aspose.slides/autoshape/set_geometry_path/
weight: 90
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Aktualizuje geometrię kształtu z obiektu [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath). Współrzędne muszą być względne względem lewego górnego rogu kształtu.
             Zmienia typ kształtu ([`GeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath) | Ścieżka geometryczna |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nie znaleziono ścieżki |
| **RuntimeError(Proxy error(ArgumentException))** | Znaleziono pustą ścieżkę |

### Zobacz także
* klasa [`AutoShape`](/slides/python-net/pl/aspose.slides/autoshape)
* klasa [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)