---
title: add_clone method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/shapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme.
            La forma clonata mantiene la posizione e le dimensioni dell'originale.

### Restituisce

Il nuovo [`IShape`](/slides/python-net/it/aspose.slides/ishape) creato.



```python
def add_clone(self, source_shape):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/it/aspose.slides/ishape) | Il [`IShape`](/slides/python-net/it/aspose.slides/ishape) da clonare. |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme.
            La nuova forma mantiene la larghezza e l'altezza di `source_shape`.

### Restituisce

Il nuovo [`IShape`](/slides/python-net/it/aspose.slides/ishape) creato.



```python
def add_clone(self, source_shape, x, y):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/it/aspose.slides/ishape) | La forma da clonare. |
| x | **float** | La coordinata x del frame della nuova forma, in punti. |
| y | **float** | La coordinata y del frame della nuova forma, in punti. |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme.

### Restituisce

Il nuovo [`IShape`](/slides/python-net/it/aspose.slides/ishape) creato.



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/it/aspose.slides/ishape) | La forma da clonare. |
| x | **float** | La coordinata x del frame della nuova forma, in punti. |
| y | **float** | La coordinata y del frame della nuova forma, in punti. |
| width | **float** | La larghezza del frame della nuova forma, in punti. |
| height | **float** | L'altezza del frame della nuova forma, in punti. |



### Vedi anche
* classe [`IShape`](/slides/python-net/it/aspose.slides/ishape)
* classe [`ShapeCollection`](/slides/python-net/it/aspose.slides/shapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)