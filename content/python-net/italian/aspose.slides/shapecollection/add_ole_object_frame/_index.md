---
title: add_ole_object_frame method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/shapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Crea un nuovo frame OLE e lo aggiunge alla fine della raccolta di forme.

### Restituisce

Il nuovo [`IOleObjectFrame`](/slides/python-net/it/aspose.slides/ioleobjectframe) creato.



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | **float** | La coordinata x del nuovo frame OLE, in punti. |
| y | **float** | La coordinata y del nuovo frame OLE, in punti. |
| width | **float** | La larghezza del nuovo frame OLE, in punti. |
| height | **float** | L'altezza del nuovo frame OLE, in punti. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/it/aspose.slides/ioleembeddeddatainfo) | Le informazioni sui dati OLE incorporati ([`IOleEmbeddedDataInfo`](/slides/python-net/it/aspose.slides/ioleembeddeddatainfo)). |

## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Crea un nuovo frame OLE e lo aggiunge alla fine della raccolta di forme.

### Restituisce

Il nuovo [`IOleObjectFrame`](/slides/python-net/it/aspose.slides/ioleobjectframe) creato.



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | **float** | La coordinata x del nuovo frame OLE, in punti. |
| y | **float** | La coordinata y del nuovo frame OLE, in punti. |
| width | **float** | La larghezza del nuovo frame OLE, in punti. |
| height | **float** | L'altezza del nuovo frame OLE, in punti. |
| class_name | **str** | Il nome della classe dell'oggetto OLE. |
| path | **str** | Il percorso al file collegato.<br/><br/>Questo percorso è memorizzato così com'è nella presentazione.<br/><br/>Se viene specificato un percorso relativo, il file sarà inaccessibile quando si apre la presentazione da una directory diversa. |

### Vedi anche
* classe [`IOleEmbeddedDataInfo`](/slides/python-net/it/aspose.slides/ioleembeddeddatainfo)
* classe [`IOleObjectFrame`](/slides/python-net/it/aspose.slides/ioleobjectframe)
* classe [`ShapeCollection`](/slides/python-net/it/aspose.slides/shapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)