---
title: set_geometry_paths method
second_title: Aspose.Slides dla Pythona poprzez .NET - Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/audioframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Aktualizuje geometrię kształtu na podstawie tablicy [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath). Współrzędne muszą być względem lewego górnego rogu kształtu.
Zmienia typ kształtu ([`GeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Tablica ścieżek geometrycznych |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nie znaleziono ścieżki |
| **RuntimeError(Proxy error(ArgumentException))** | Pusta ścieżka |

### Zobacz również
* klasa [`AudioFrame`](/slides/python-net/pl/aspose.slides/audioframe)
* klasa [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)