---
title: set_geometry_path method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/videoframe/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Werk de vormgeometrie bij vanuit [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath) object. Coördinaten moeten relatief zijn aan de linkerbovenhoek van de vorm.
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
* klasse [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath)
* klasse [`VideoFrame`](/slides/python-net/nl/aspose.slides/videoframe)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)