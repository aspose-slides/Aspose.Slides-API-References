---
title: set_geometry_path method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/igeometryshape/set_geometry_path/
weight: 70
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Aktualizuje geometrii tvaru z [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath) objektu. Souřadnice musí být relativní k levému
             hornímu rohu tvaru.
             Změní typ tvaru ([`IGeometryShape.shape_type`](/slides/python-net/cs/aspose.slides/igeometryshape/shape_type)) na [`ShapeType.CUSTOM`](/slides/python-net/cs/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath) | Cesta geometrie |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nenalezena žádná cesta |
| **RuntimeError(Proxy error(ArgumentException))** | Nalezena prázdná cesta |

### Viz také
* třída [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath)
* třída [`IGeometryShape`](/slides/python-net/cs/aspose.slides/igeometryshape)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)