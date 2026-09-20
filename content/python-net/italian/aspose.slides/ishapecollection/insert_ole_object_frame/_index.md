---
title: insert_ole_object_frame method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Crea un nuovo frame OLE object e lo inserisce nella collezione di forme all'indice specificato.

### Restituisce

Il nuovo [`IOleObjectFrame`](/slides/python-net/it/aspose.slides/ioleobjectframe) appena creato.



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire il frame OLE object. |
| x | **float** | La coordinata x del nuovo frame OLE, in punti. |
| y | **float** | La coordinata y del nuovo frame OLE, in punti. |
| width | **float** | La larghezza del nuovo frame OLE, in punti. |
| height | **float** | L'altezza del nuovo frame OLE, in punti. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/it/aspose.slides/ioleembeddeddatainfo) | Le informazioni sui dati OLE incorporati ([`IOleEmbeddedDataInfo`](/slides/python-net/it/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Crea un nuovo frame OLE object e lo inserisce nella collezione di forme all'indice specificato.

### Restituisce

Il nuovo [`IOleObjectFrame`](/slides/python-net/it/aspose.slides/ioleobjectframe) appena creato.



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire il frame OLE object. |
| x | **float** | La coordinata x del nuovo frame OLE, in punti. |
| y | **float** | La coordinata y del nuovo frame OLE, in punti. |
| width | **float** | La larghezza del nuovo frame OLE, in punti. |
| height | **float** | L'altezza del nuovo frame OLE, in punti. |
| class_name | **str** | Il nome della classe dell'oggetto OLE. |
| path | **str** | Il percorso al file collegato. <br/><br/>Questo percorso viene memorizzato così com'è nella presentazione.<br/><br/>            Se viene specificato un percorso relativo, il file non sarà accessibile aprendo<br/><br/>            la presentazione da una directory diversa. |



### Vedi anche
* classe [`IOleEmbeddedDataInfo`](/slides/python-net/it/aspose.slides/ioleembeddeddatainfo)
* classe [`IOleObjectFrame`](/slides/python-net/it/aspose.slides/ioleobjectframe)
* classe [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)