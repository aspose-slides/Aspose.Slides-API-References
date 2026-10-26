---
title: set_geometry_path method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/audioframe/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Werk de vormgeometrie bij vanaf het [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath) object. Coördinaten moeten relatief zijn ten opzichte van de linker
             bovenhoek van de vorm.
             Wijzigt het type van de vorm ([`GeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM).


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
* klasse [`AudioFrame`](/slides/python-net/nl/aspose.slides/audioframe)
* klasse [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)