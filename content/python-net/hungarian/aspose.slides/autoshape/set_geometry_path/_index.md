---
title: set_geometry_path method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/autoshape/set_geometry_path/
weight: 90
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Frissíti a forma geometriáját a(z) [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) objektumból. A koordinátáknak a forma bal felső sarkához képest relatívnek kell lenniük.
Megváltoztatja a forma típusát ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM) típusra.


```python
def set_geometry_path(self, geometry_path):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) | Geometria útvonal |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Útvonal nem található |
| **RuntimeError(Proxy error(ArgumentException))** | Üres útvonal található |



### Lásd még
* osztály [`AutoShape`](/slides/python-net/hu/aspose.slides/autoshape)
* osztály [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)