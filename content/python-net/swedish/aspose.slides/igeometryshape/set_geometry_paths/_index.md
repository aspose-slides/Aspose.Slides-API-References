---
title: set_geometry_paths method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/igeometryshape/set_geometry_paths/
weight: 80
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Uppdaterar formens geometri från en array av [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath). Koordinaterna måste vara relativt till formens vänstra övre hörn. Ändrar formens typ ([`IGeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/igeometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Array med geometrivägar |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Ingen bana hittades |
| **RuntimeError(Proxy error(ArgumentException))** | Tom bana |

### Se även
* klass [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)
* klass [`IGeometryShape`](/slides/python-net/sv/aspose.slides/igeometryshape)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)