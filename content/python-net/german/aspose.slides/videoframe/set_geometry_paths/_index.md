---
title: set_geometry_paths method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/videoframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Aktualisiert die Geometrie der Form anhand eines Arrays von [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath). Die Koordinaten müssen relativ zur linken oberen Ecke der Form sein. Ändert den Typ der Form ([`GeometryShape.shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Array von Geometriepfaden |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kein Pfad gefunden |
| **RuntimeError(Proxy error(ArgumentException))** | Leerer Pfad |

### Siehe auch
* Klasse [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath)
* Klasse [`VideoFrame`](/slides/python-net/de/aspose.slides/videoframe)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)