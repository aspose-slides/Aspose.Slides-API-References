---
title: insert_auto_shape method
second_title: Aspose.Slides per Python tramite .NET API Reference
description: 
type: docs
url: /it/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Crea una nuova forma automatica e la inserisce nella collezione di forme all'indice specificato, applicando la formattazione predefinita del modello.

### Restituisce

The newly created [`IAutoShape`](/slides/python-net/it/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire la nuova forma automatica. |
| shape_type | [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) | Il [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) della forma automatica da inserire. |
| x | **float** | La coordinata x del riquadro della forma, in punti. |
| y | **float** | La coordinata y del riquadro della forma, in punti. |
| width | **float** | La larghezza del riquadro della forma, in punti. |
| height | **float** | L'altezza del riquadro della forma, in punti. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Crea una nuova forma automatica e la inserisce nella collezione di forme all'indice specificato, opzionalmente inizializzandola con lo stile predefinito del modello.

### Restituisce

The newly created [`IAutoShape`](/slides/python-net/it/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire la forma automatica. |
| shape_type | [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) | Il [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) della forma automatica da inserire. |
| x | **float** | La coordinata x del riquadro della forma, in punti. |
| y | **float** | La coordinata y del riquadro della forma, in punti. |
| width | **float** | La larghezza del riquadro della forma, in punti. |
| height | **float** | L'altezza del riquadro della forma, in punti. |
| create_from_template | **bool** | True per applicare lo stile predefinito del modello (incluso un nome non vuoto, stile semplice e testo centrato); <br/><br/>            false per creare la forma con tutte le proprietà impostate sui valori predefiniti. |



### Vedi anche
* classe [`IAutoShape`](/slides/python-net/it/aspose.slides/iautoshape)
* classe [`ShapeCollection`](/slides/python-net/it/aspose.slides/shapecollection)
* enumerazione [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)