---
title: set_geometry_paths method
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.smartart/smartartshape/set_geometry_paths/
weight: 90
---
## set_geometry_paths(self, geometry_paths) {#listigeometrypath}
Aggiorna la geometria della forma da un array di [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath). Le coordinate devono essere relative al lato sinistro
             angolo superiore della forma.
             Cambia il tipo della forma ([`GeometryShape.shape_type`](/slides/python-net/it/aspose.slides/geometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM).


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
| **RuntimeError(Proxy error(ArgumentException))** | Percorso non trovato |
| **RuntimeError(Proxy error(ArgumentException))** | Percorso vuoto |



### Vedi anche
* classe [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath)
* classe [`SmartArtShape`](/slides/python-net/it/aspose.slides.smartart/smartartshape)
* modulo [`aspose.slides.smartart`](/slides/python-net/it/aspose.slides.smartart)
* libreria [`Aspose.Slides`](/slides/python-net)