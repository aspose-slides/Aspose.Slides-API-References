---
title: insert_clone method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ishapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Crea una copia della forma specificata e la inserisce nella collezione di forme all'indice specificato.
            La forma clonata mantiene la posizione e le dimensioni originali.

### Restituisce

Il [`IShape`](/slides/python-net/it/aspose.slides/ishape) appena creato.



```python
def insert_clone(self, index, source_shape):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire la forma clonata. |
| source_shape | [`IShape`](/slides/python-net/it/aspose.slides/ishape) | Il [`IShape`](/slides/python-net/it/aspose.slides/ishape) da clonare. |


## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Crea una copia della forma specificata e la inserisce nella collezione di forme all'indice specificato.
            La nuova forma mantiene la larghezza e l'altezza della `source_shape`.

### Restituisce

Il [`IShape`](/slides/python-net/it/aspose.slides/ishape) appena creato.



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire la forma clonata. |
| source_shape | [`IShape`](/slides/python-net/it/aspose.slides/ishape) | Il [`IShape`](/slides/python-net/it/aspose.slides/ishape) da clonare. |
| x | **float** | La coordinata x del riquadro della forma clonata, in punti. |
| y | **float** | La coordinata y del riquadro della forma clonata, in punti. |


## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Crea una copia della forma specificata e la inserisce nella collezione di forme all'indice specificato.

### Restituisce

Il [`IShape`](/slides/python-net/it/aspose.slides/ishape) appena creato.



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire la forma clonata. |
| source_shape | [`IShape`](/slides/python-net/it/aspose.slides/ishape) | Il [`IShape`](/slides/python-net/it/aspose.slides/ishape) da clonare. |
| x | **float** | La coordinata x del riquadro della forma clonata, in punti. |
| y | **float** | La coordinata y del riquadro della forma clonata, in punti. |
| width | **float** | La larghezza del riquadro della forma clonata, in punti. |
| height | **float** | L'altezza del riquadro della forma clonata, in punti. |



### Vedi anche
* classe [`IShape`](/slides/python-net/it/aspose.slides/ishape)
* classe [`IShapeCollection`](/slides/python-net/it/aspose.slides/ishapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)