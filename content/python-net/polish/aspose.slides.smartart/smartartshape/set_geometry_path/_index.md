---
title: set_geometry_path method
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides.smartart/smartartshape/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Uaktualnia geometrię kształtu z obiektu [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath). Współrzędne muszą być względem lewego górnego rogu kształtu. Zmienia typ kształtu ([`GeometryShape.shape_type`](/slides/python-net/pl/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/pl/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath) | Geometry path |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | No path found |
| **RuntimeError(Proxy error(ArgumentException))** | Empty path found |

### See Also
* class [`IGeometryPath`](/slides/python-net/pl/aspose.slides/igeometrypath)
* class [`SmartArtShape`](/slides/python-net/pl/aspose.slides.smartart/smartartshape)
* module [`aspose.slides.smartart`](/slides/python-net/pl/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)