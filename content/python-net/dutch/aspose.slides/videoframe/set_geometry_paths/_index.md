---
title: set_geometry_paths method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/videoframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Werkt de geometrie van de vorm bij vanuit een array van [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath). Coördinaten moeten relatief zijn aan de linker
             bovenhoek van de vorm.
             Wijzigt het type van de vorm ([`GeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/geometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM).


```python
def set_geometry_paths(self, geometry_paths):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Array geometriepaden |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Geen pad gevonden |
| **RuntimeError(Proxy error(ArgumentException))** | Leeg pad |



### Zie ook
* klasse [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath)
* klasse [`VideoFrame`](/slides/python-net/nl/aspose.slides/videoframe)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)