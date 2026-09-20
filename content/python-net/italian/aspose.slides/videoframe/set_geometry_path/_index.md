---
title: set_geometry_path method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/videoframe/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Aggiorna la geometria della forma dall'oggetto [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath).  
Le coordinate devono essere relative all'angolo superiore sinistro della forma.  
Cambia il tipo della forma ([`GeometryShape.shape_type`](/slides/python-net/it/aspose.slides/geometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_path(self, geometry_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath) | Geometry path |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | No path found |
| **RuntimeError(Proxy error(ArgumentException))** | Empty path found |

### Vedi anche
* classe [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath)
* classe [`VideoFrame`](/slides/python-net/it/aspose.slides/videoframe)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)