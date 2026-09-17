---
title: set_geometry_paths method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/igeometryshape/set_geometry_paths/
weight: 80
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Aktualisiert die Formgeometrie aus einem Array von [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath). Die Koordinaten müssen relativ zur linken oberen Ecke der Form sein.
Ändert den Typ der Form ([`IGeometryShape.shape_type`](/slides/python-net/de/aspose.slides/igeometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Array-Geometriepfade |

### Exceptions

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kein Pfad gefunden |
| **RuntimeError(Proxy error(ArgumentException))** | Leerer Pfad |

### See Also
* class [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath)
* class [`IGeometryShape`](/slides/python-net/de/aspose.slides/igeometryshape)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)