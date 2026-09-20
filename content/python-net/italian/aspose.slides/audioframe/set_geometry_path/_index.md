---
title: set_geometry_path method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/audioframe/set_geometry_path/
weight: 80
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Aggiorna la geometria della forma dall'oggetto [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath). Le coordinate devono essere relative all'angolo superiore sinistro della forma.
             Cambia il tipo della forma ([`GeometryShape.shape_type`](/slides/python-net/it/aspose.slides/geometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM).


```python
def set_geometry_path(self, geometry_path):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath) | Percorso della geometria |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nessun percorso trovato |
| **RuntimeError(Proxy error(ArgumentException))** | Percorso vuoto trovato |



### Vedi anche
* classe [`AudioFrame`](/slides/python-net/it/aspose.slides/audioframe)
* classe [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)