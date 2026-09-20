---
title: set_geometry_path method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/connector/set_geometry_path/
weight: 90
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Aktualizuje geometrii tvaru z objektu [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath). Souřadnice musí být relativní k levému hornímu rohu tvaru. Mění typ tvaru ([`GeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/geometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM).


```python
def set_geometry_path(self, geometry_path):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath) | Geometrická cesta |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nenalezena žádná cesta |
| **RuntimeError(Proxy error(ArgumentException))** | Nalezena prázdná cesta |



### Viz také
* třída [`Connector`](/slides/python-net/cs/aspose.slides/connector)
* třída [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)