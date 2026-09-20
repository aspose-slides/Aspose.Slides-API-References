---
title: set_geometry_path method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.smartart/smartartshape/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Uppdaterar formens geometri från [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)-objekt. Koordinaterna måste vara relativa till den vänstra
             övre hörnet av formen.
             Ändrar typ av formen ([`GeometryShape.shape_type`](/slides/python-net/sv/aspose.slides/geometryshape/shape_type)) till [`ShapeType.CUSTOM`](/slides/python-net/sv/aspose.slides/shapetype/CUSTOM).

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

### Se även
* klass [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)
* klass [`SmartArtShape`](/slides/python-net/sv/aspose.slides.smartart/smartartshape)
* modul [`aspose.slides.smartart`](/slides/python-net/sv/aspose.slides.smartart)
* bibliotek [`Aspose.Slides`](/slides/python-net)