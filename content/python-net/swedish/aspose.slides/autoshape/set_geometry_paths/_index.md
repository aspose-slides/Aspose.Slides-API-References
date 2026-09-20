---
title: set_geometry_paths method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/autoshape/set_geometry_paths/
weight: 100
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Uppdaterar formens geometri från en matris av [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath). Koordinaterna måste vara relativt till den vänstra
             övre hörnet av formen.
             Ändrar formens typ ([`GeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/geometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Matris med geometri-vägar |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Ingen sökväg hittades |
| **RuntimeError(Proxy error(ArgumentException))** | Tom sökväg |

### Se även
* klass [`AutoShape`](/slides/python-net/sv/aspose.slides/autoshape)
* klass [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)