---
title: add_connector method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Crea una nuova forma di connettore con lo stile predefinito del modello e la aggiunge alla fine della
            collezione di forme.

### Restituisce

Il nuovo [`IConnector`](/slides/python-net/it/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) | Il [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) della forma di connettore da aggiungere. |
| x | **float** | La coordinata x del frame del connettore, in punti. |
| y | **float** | La coordinata y del frame del connettore, in punti. |
| width | **float** | La larghezza del frame del connettore, in punti. |
| height | **float** | L'altezza del frame del connettore, in punti. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Crea una nuova forma di connettore e la aggiunge alla fine della collezione di forme,
            applicando facoltativamente lo stile predefinito del modello.

### Restituisce

Il nuovo [`IConnector`](/slides/python-net/it/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) | Il [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) della forma di connettore da creare. |
| x | **float** | La coordinata x del frame del connettore, in punti. |
| y | **float** | La coordinata y del frame del connettore, in punti. |
| width | **float** | La larghezza del frame del connettore, in punti. |
| height | **float** | L'altezza del frame del connettore, in punti. |
| create_from_template | **bool** | True per applicare lo stile predefinito del modello (nome non vuoto, stile semplice); <br/><br/>            false per creare il connettore con i valori predefiniti delle proprietà. |



### Vedi anche
* classe [`IConnector`](/slides/python-net/it/aspose.slides/iconnector)
* classe [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection)
* enumerazione [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)