---
title: set_geometry_paths method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.smartart/smartartshape/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Werkt de vormgeometrie bij vanuit een array van [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath). Coördinaten moeten relatief zijn aan de linkerbovenhoek van de vorm.
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
* klasse [`SmartArtShape`](/slides/python-net/nl/aspose.slides.smartart/smartartshape)
* module [`aspose.slides.smartart`](/slides/python-net/nl/aspose.slides.smartart)
* bibliotheek [`Aspose.Slides`](/slides/python-net)