---
title: set_geometry_path method
second_title: Aspose.Slides dla Pythona poprzez .NET Referencję API
description: 
type: docs
url: /pl/aspose.slides/connector/set_geometry_path/
weight: 90
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Aktualizuje geometrię kształtu z obiektu [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath). Współrzędne muszą być podane względem lewego górnego narożnika kształtu. Zmienia typ kształtu ([`GeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM).


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
| **RuntimeError(Proxy error(ArgumentException))** | No path found |
| **RuntimeError(Proxy error(ArgumentException))** | Empty path found |



### Zobacz także
* klasa [`Connector`](/slides/python-net/pl/aspose.slides/connector)
* klasa [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)