---
title: insert_connector method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Crea una nuova forma connettore e la inserisce nella raccolta di forme all'indice specificato,
            applicando lo stile predefinito del modello.

### Restituisce

Il nuovo [`IConnector`](/slides/python-net/it/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire la forma connettore. |
| shape_type | [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) | Il [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) della forma connettore da inserire. |
| x | **float** | La coordinata x del riquadro del connettore, in punti. |
| y | **float** | La coordinata y del riquadro del connettore, in punti. |
| width | **float** | La larghezza del riquadro del connettore, in punti. |
| height | **float** | L'altezza del riquadro del connettore, in punti. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Crea una nuova forma connettore e la inserisce nella raccolta di forme all'indice specificato,
            applicando facoltativamente lo stile predefinito del modello.

### Restituisce

Il nuovo [`IConnector`](/slides/python-net/it/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire la forma connettore. |
| shape_type | [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) | Il [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) della forma connettore da inserire. |
| x | **float** | La coordinata x del riquadro del connettore, in punti. |
| y | **float** | La coordinata y del riquadro del connettore, in punti. |
| width | **float** | La larghezza del riquadro del connettore, in punti. |
| height | **float** | L'altezza del riquadro del connettore, in punti. |
| create_from_template | **bool** | True per applicare lo stile predefinito del modello (nome non vuoto, stile semplice);<br/><br/>            false per creare il connettore con i valori predefiniti delle proprietà. |



### Vedi anche
* classe [`IConnector`](/slides/python-net/it/aspose.slides/iconnector)
* classe [`ShapeCollection`](/slides/python-net/it/aspose.slides/shapecollection)
* enumerazione [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)