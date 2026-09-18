---
title: set_geometry_paths method
second_title: Aspose.Slides a Python számára a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/autoshape/set_geometry_paths/
weight: 100
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Frissíti a forma geometriáját a(z) [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) tömbből. A koordinátáknak a forma bal felső sarkához relatívnak kell lenniük. A forma típusát ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM)-ra változtatja.

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Array geometry paths |

### Kikételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | No path found |
| **RuntimeError(Proxy error(ArgumentException))** | Empty path |

### Lásd még
* osztály [`AutoShape`](/slides/python-net/hu/aspose.slides/autoshape)
* osztály [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)