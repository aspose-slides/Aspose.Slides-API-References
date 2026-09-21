---
title: set_geometry_paths method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/igeometryshape/set_geometry_paths/
weight: 80
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Werk de vormgeometrie bij vanuit een array van [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath). Coördinaten moeten relatief zijn ten opzichte van de linker bovenhoek van de vorm. Wijzigt het type van de vorm ([`IGeometryShape.shape_type`](/slides/python-net/nl/aspose.slides/igeometryshape/shape_type)) naar [`ShapeType.CUSTOM`](/slides/python-net/nl/aspose.slides/shapetype/CUSTOM).


```python
def set_geometry_paths(self, geometry_paths):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Array van geometriepaden |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Pad niet gevonden |
| **RuntimeError(Proxy error(ArgumentException))** | Leeg pad |



### Zie ook
* klasse [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath)
* klasse [`IGeometryShape`](/slides/python-net/nl/aspose.slides/igeometryshape)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)