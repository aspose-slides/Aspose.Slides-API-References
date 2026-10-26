---
title: add_auto_shape method
second_title: Riferimento API di Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/shapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Crea una nuova forma automatica con formattazione predefinita e la aggiunge alla fine della collezione di forme.

### Returns

Il nuovo [`IAutoShape`](/slides/python-net/it/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) | Il [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) della forma automatica da aggiungere. |
| x | **float** | La coordinata x del riquadro della forma, in punti. |
| y | **float** | La coordinata y del riquadro della forma, in punti. |
| width | **float** | La larghezza del riquadro della forma, in punti. |
| height | **float** | L'altezza del riquadro della forma, in punti. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Crea una nuova forma automatica e la aggiunge alla fine della collezione di forme, opzionalmente inizializzandola con la formattazione predefinita del modello.

### Returns

Il nuovo [`IAutoShape`](/slides/python-net/it/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) | Il [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype) della forma automatica da aggiungere. |
| x | **float** | La coordinata x del riquadro della forma, in punti. |
| y | **float** | La coordinata y del riquadro della forma, in punti. |
| width | **float** | La larghezza del riquadro della forma, in punti. |
| height | **float** | L'altezza del riquadro della forma, in punti. |
| create_from_template | **bool** | True per applicare lo stile predefinito del modello (stile semplice, testo centrato e nome non vuoto)<br/><br/>            alla nuova forma; false per creare la forma con tutte le proprietà impostate ai valori predefiniti. |



### Vedi anche
* classe [`IAutoShape`](/slides/python-net/it/aspose.slides/iautoshape)
* classe [`ShapeCollection`](/slides/python-net/it/aspose.slides/shapecollection)
* enumerazione [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)