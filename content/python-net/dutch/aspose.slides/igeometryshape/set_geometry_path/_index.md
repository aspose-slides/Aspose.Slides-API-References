---
title: set_geometry_path method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/igeometryshape/set_geometry_path/
weight: 70
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Werkt de vormgeometrie bij van [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath) object. Coördinaten moeten relatief zijn ten opzichte van de linkerbovenhoek van de vorm. Wijzigt het type van de vorm ([`IGeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/igeometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath) | Geometriepad |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Geen pad gevonden |
| **RuntimeError(Proxy error(ArgumentException))** | Leeg pad gevonden |

### Zie ook
* klasse [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath)
* klasse [`IGeometryShape`](/slides/python-net/nl/aspose.slides/igeometryshape)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)