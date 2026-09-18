---
title: set_geometry_paths method
second_title: Aspose.Slides for Python via .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/audioframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Frissíti a alakzat geometriáját a [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) tömbből. A koordinátáknak az alakzat bal felső sarkához képest relatívnak kell lenniük. Megváltoztatja az alakzat ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) típusát [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM) értékre.


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
| **RuntimeError(Proxy error(ArgumentException))** | Útvonal nem található |
| **RuntimeError(Proxy error(ArgumentException))** | Üres útvonal |



### Lásd még
* osztály [`AudioFrame`](/slides/python-net/hu/aspose.slides/audioframe)
* osztály [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)