---
title: insert_clone method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/shapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. La forma clonada conserva la posición y el tamaño del original.

### Devuelve

El [`IShape`](/slides/python-net/es/aspose.slides/ishape) recién creado.



```python
def insert_clone(self, index, source_shape):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que se insertará la forma clonada. |
| source_shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | La [`IShape`](/slides/python-net/es/aspose.slides/ishape) a clonar. |


## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. La nueva forma conserva el ancho y la altura de la `source_shape`.

### Devuelve

El [`IShape`](/slides/python-net/es/aspose.slides/ishape) recién creado.



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que se insertará la forma clonada. |
| source_shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | La [`IShape`](/slides/python-net/es/aspose.slides/ishape) a clonar. |
| x | **float** | La coordenada x del marco de la forma clonada, en puntos. |
| y | **float** | La coordenada y del marco de la forma clonada, en puntos. |


## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado.

### Devuelve

El [`IShape`](/slides/python-net/es/aspose.slides/ishape) recién creado.



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que se insertará la forma clonada. |
| source_shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | La [`IShape`](/slides/python-net/es/aspose.slides/ishape) a clonar. |
| x | **float** | La coordenada x del marco de la forma clonada, en puntos. |
| y | **float** | La coordenada y del marco de la forma clonada, en puntos. |
| width | **float** | El ancho del marco de la forma clonada, en puntos. |
| height | **float** | La altura del marco de la forma clonada, en puntos. |



### Ver también
* clase [`IShape`](/slides/python-net/es/aspose.slides/ishape)
* clase [`ShapeCollection`](/slides/python-net/es/aspose.slides/shapecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)