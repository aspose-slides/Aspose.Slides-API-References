---
title: insert_clone method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/shapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato.  
La forma clonata mantiene la posizione e le dimensioni dell'originale.

### Restituisce

L'oggetto appena creato [`IShape`](/slides/python-net/it/aspose.slides/ishape).

```python
def insert_clone(self, index, source_shape):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire la forma clonata. |
| source_shape | [`IShape`](/slides/python-net/it/aspose.slides/ishape) | La [`IShape`](/slides/python-net/it/aspose.slides/ishape) da clonare. |

## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato.  
La nuova forma mantiene la larghezza e l'altezza della `source_shape`.

### Restituisce

L'oggetto appena creato [`IShape`](/slides/python-net/it/aspose.slides/ishape).

```python
def insert_clone(self, index, source_shape, x, y):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire la forma clonata. |
| source_shape | [`IShape`](/slides/python-net/it/aspose.slides/ishape) | La [`IShape`](/slides/python-net/it/aspose.slides/ishape) da clonare. |
| x | **float** | La coordinata x del riquadro della forma clonata, in punti. |
| y | **float** | La coordinata y del riquadro della forma clonata, in punti. |

## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato.

### Restituisce

L'oggetto appena creato [`IShape`](/slides/python-net/it/aspose.slides/ishape).

```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | **int** | L'indice basato su zero al quale inserire la forma clonata. |
| source_shape | [`IShape`](/slides/python-net/it/aspose.slides/ishape) | La [`IShape`](/slides/python-net/it/aspose.slides/ishape) da clonare. |
| x | **float** | La coordinata x del riquadro della forma clonata, in punti. |
| y | **float** | La coordinata y del riquadro della forma clonata, in punti. |
| width | **float** | La larghezza del riquadro della forma clonata, in punti. |
| height | **float** | L'altezza del riquadro della forma clonata, in punti. |

### Vedi anche
* classe [`IShape`](/slides/python-net/it/aspose.slides/ishape)
* classe [`ShapeCollection`](/slides/python-net/it/aspose.slides/shapecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)