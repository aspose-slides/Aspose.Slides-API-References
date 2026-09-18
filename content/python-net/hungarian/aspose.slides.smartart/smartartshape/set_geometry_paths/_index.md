---
title: set_geometry_paths method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides.smartart/smartartshape/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Frissíti az alakzat geometriáját a [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath) tömbből. A koordinátáknak az alakzat bal felső sarkához kell viszonyulniuk. Megváltoztatja az alakzat típusát ([`GeometryShape.shape_type`](/slides/python-net/hu/aspose.slides/geometryshape/shape_type)) [`ShapeType.CUSTOM`](/slides/python-net/hu/aspose.slides/shapetype/CUSTOM)-ra.

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
* osztály [`IGeometryPath`](/slides/python-net/hu/aspose.slides/igeometrypath)
* osztály [`SmartArtShape`](/slides/python-net/hu/aspose.slides.smartart/smartartshape)
* modul [`aspose.slides.smartart`](/slides/python-net/hu/aspose.slides.smartart)
* könyvtár [`Aspose.Slides`](/slides/python-net)