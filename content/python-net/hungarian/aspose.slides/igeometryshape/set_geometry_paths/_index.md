---
title: set_geometry_paths method
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/igeometryshape/set_geometry_paths/
weight: 80
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Frissíti az alakzat geometriáját a [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) tömbből. A koordinátáknak az alakzat bal
             felső sarkához képest relatívnek kell lenniük.
             Az alakzat típusát ([`IGeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/igeometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM) típusra változtatja.

```python
def set_geometry_paths(self, geometry_paths):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Geometriai útvonalak tömbje |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nem található útvonal |
| **RuntimeError(Proxy error(ArgumentException))** | Üres útvonal |



### Lásd még
* osztály [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath)
* osztály [`IGeometryShape`](/slides/python-net/hu/aspose.slides/igeometryshape)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)