---
title: set_geometry_path method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/connector/set_geometry_path/
weight: 90
---
## set_geometry_path(self, geometry_path) {#igeometrypath}
Aggiorna la geometria della forma da oggetto [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath). Le coordinate devono essere relative al sinistro
             angolo superiore della forma.
             Cambia il tipo della forma ([`GeometryShape.shape_type`](/slides/python-net/it/aspose.slides/geometryshape/shape_type)) in [`ShapeType.CUSTOM`](/slides/python-net/it/aspose.slides/shapetype/CUSTOM).


```python
def set_geometry_path(self, geometry_path):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geometry_path | [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath) | Percorso geometria |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nessun percorso trovato |
| **RuntimeError(Proxy error(ArgumentException))** | Percorso vuoto trovato |



### Vedi anche
* classe [`Connector`](/slides/python-net/it/aspose.slides/connector)
* classe [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)