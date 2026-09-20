---
title: set_geometry_path method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/igeometryshape/set_geometry_path/
weight: 70
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Uppdaterar formens geometri från [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)-objekt. Koordinaterna måste vara relativt till formens vänstra övre hörn. Ändrar formens typ ([`IGeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/igeometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath) | Geometri-sökväg |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Ingen sökväg hittades |
| **RuntimeError(Proxy error(ArgumentException))** | Tom sökväg hittades |

### Se också
* klass [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)
* klass [`IGeometryShape`](/slides/python-net/sv/aspose.slides/igeometryshape)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)