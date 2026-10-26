---
title: insert_auto_shape method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Crea una nuova forma automatica e la inserisce nella raccolta di forme all'indice specificato, applicando la formattazione predefinita del modello.

### Returns

Il nuovo [`IAutoShape`](/slides/python-net/it/aspose.slides/iautoshape) creato.



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
Crea una nuova forma automatica e la inserisce nella raccolta di forme all'indice specificato, opzionalmente inizializzandola con lo stile predefinito del modello.

### Returns

Il nuovo [`IAutoShape`](/slides/python-net/it/aspose.slides/iautoshape) creato.



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
| create_from_template | **bool** | True per applicare lo stile predefinito del modello (inclusi un nome non vuoto, uno stile semplice e testo centrato); <br/><br/>false per creare la forma con tutte le proprietà impostate ai valori predefiniti. |



### See Also
* classe [`IAutoShape`](/slides/python-net/it/aspose.slides/iautoshape)
* classe [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection)
* enumerazione [`ShapeType`](/slides/python-net/it/aspose.slides/shapetype)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)