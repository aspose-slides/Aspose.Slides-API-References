---
title: set_geometry_paths method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/audioframe/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Aggiorna la geometria della forma da un array di [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath). Le coordinate devono essere relative all'angolo superiore sinistro della forma. Cambia il tipo della forma ([`GeometryShape.shape_type`](/slides/python-net/it/aspose.slides/geometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM).

```python
def set_geometry_paths(self, geometry_paths):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geometry_paths | **List[IGeometryPath]** | Array di percorsi di geometria |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nessun percorso trovato |
| **RuntimeError(Proxy error(ArgumentException))** | Percorso vuoto |

### Vedi anche
* classe [`AudioFrame`](/slides/python-net/it/aspose.slides/audioframe)
* classe [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)