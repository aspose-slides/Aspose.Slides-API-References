---
title: set_geometry_path method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/videoframe/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Aktualisiert die Formgeometrie aus dem [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath)-Objekt. Koordinaten müssen relativ zur linken
             oberen Ecke der Form.
             Ändert den Typ der Form ([`GeometryShape.shape_type`](/slides/python-net/de/aspose.slides/geometryshape/shape_type)) zu [`ShapeType.CUSTOM`](/slides/python-net/de/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath) | Geometriepfad |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kein Pfad gefunden |
| **RuntimeError(Proxy error(ArgumentException))** | Leerer Pfad gefunden |

### Siehe auch
* Klasse [`IGeometryPath`](/slides/python-net/de/aspose.slides/igeometrypath)
* Klasse [`VideoFrame`](/slides/python-net/de/aspose.slides/videoframe)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)