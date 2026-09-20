---
title: set_geometry_path method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/connector/set_geometry_path/
weight: 90
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Uppdaterar formens geometri från [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)-objekt. Koordinater måste vara relativa till formens vänstra övre hörn. Ändrar typ av formen ([`GeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/geometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath) | Geometri sökväg |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Ingen sökväg hittades |
| **RuntimeError(Proxy error(ArgumentException))** | Tom sökväg hittades |

### Se även
* klass [`Connector`](/slides/python-net/sv/aspose.slides/connector)
* klass [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)