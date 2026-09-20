---
title: set_geometry_paths method
second_title: Aspose.Slides pro Python přes .NET referenční příručku API
description: 
type: docs
url: /cs/aspose.slides/audioframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Aktualizuje geometrii tvaru z pole [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému
hornímu rohu tvaru.
Změní typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Pole geometrických cest |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nebyla nalezena žádná cesta |
| **RuntimeError(Proxy error(ArgumentException))** | Prázdná cesta |

### Viz také
* třída [`AudioFrame`](/slides/python-net/cs/aspose.slides/audioframe)
* třída [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)