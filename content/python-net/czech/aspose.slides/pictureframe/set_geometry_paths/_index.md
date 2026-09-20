---
title: set_geometry_paths method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/pictureframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Aktualizuje geometrii tvaru z pole [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému hornímu rohu tvaru.
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
| **RuntimeError(Proxy error(ArgumentException))** | Nebyla nalezena cesta |
| **RuntimeError(Proxy error(ArgumentException))** | Prázdná cesta |



### Viz také
* třída [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath)
* třída [`PictureFrame`](/slides/python-net/cs/aspose.slides/pictureframe)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)