---
title: set_geometry_path method
second_title: Aspose.Slides a .NET-en keresztül elérhető Python API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/igeometryshape/set_geometry_path/
weight: 70
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Frissíti a forma geometriáját a [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) objektumból. A koordinátáknak a forma bal felső sarkához képest relatívaknak kell lenniük.  
Megváltoztatja a forma típusát ([`IGeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/igeometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM)-ra.


```python
def set_geometry_path(self, geometry_path):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) | Geometriai útvonal |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nem található útvonal |
| **RuntimeError(Proxy error(ArgumentException))** | Üres útvonal található |



### Lásd még
* osztály [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath)
* osztály [`IGeometryShape`](/slides/python-net/hu/aspose.slides/igeometryshape)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)