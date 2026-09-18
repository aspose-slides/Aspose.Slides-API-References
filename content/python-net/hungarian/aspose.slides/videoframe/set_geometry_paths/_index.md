---
title: set_geometry_paths method
second_title: Aspose.Slides Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/videoframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Frissíti az alakzat geometriáját a [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) tömbből. A koordinátáknak a forma bal
             felső sarkához relatívnak kell lenniük.
             Megváltoztatja a forma típusát ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM) típusra.

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Geometriai útvonalak tömbje |

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nem található útvonal |
| **RuntimeError(Proxy error(ArgumentException))** | Üres útvonal |

### Lásd még
* osztály [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath)
* osztály [`VideoFrame`](/slides/python-net/hu/aspose.slides/videoframe)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)