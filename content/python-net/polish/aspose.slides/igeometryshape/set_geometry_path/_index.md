---
title: set_geometry_path method
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/igeometryshape/set_geometry_path/
weight: 70
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Aktualizuje geometrię kształtu z obiektu [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath).
Współrzędne muszą być względem lewego
             górnego rogu kształtu.
             Zmienia typ kształtu ([`IGeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/igeometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath) | Geometry path |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nie znaleziono ścieżki |
| **RuntimeError(Proxy error(ArgumentException))** | Znaleziono pustą ścieżkę |

### Zobacz także
* klasa [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath)
* klasa [`IGeometryShape`](/slides/python-net/pl/aspose.slides/igeometryshape)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)