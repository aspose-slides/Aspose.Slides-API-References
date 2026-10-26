---
title: insert_clone method
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ishapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Crea una copia de la shape especificada y la inserta en la colección de shapes en el índice especificado.
            La shape clonada conserva la posición y el tamaño originales.

### Devuelve

El [`IShape`](/slides/python-net/es/aspose.slides/ishape) recién creado.



```python
def insert_clone(self, index, source_shape):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que se inserta la shape clonada. |
| source_shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | El [`IShape`](/slides/python-net/es/aspose.slides/ishape) a clonar. |


## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Crea una copia de la shape especificada y la inserta en la colección de shapes en el índice especificado.
            La nueva shape conserva el ancho y la altura de `source_shape`.

### Devuelve

El [`IShape`](/slides/python-net/es/aspose.slides/ishape) recién creado.



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que se inserta la shape clonada. |
| source_shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | El [`IShape`](/slides/python-net/es/aspose.slides/ishape) a clonar. |
| x | **float** | La coordenada x del marco de la shape clonada, en puntos. |
| y | **float** | La coordenada y del marco de la shape clonada, en puntos. |


## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Crea una copia de la shape especificada y la inserta en la colección de shapes en el índice especificado.

### Devuelve

El [`IShape`](/slides/python-net/es/aspose.slides/ishape) recién creado.



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que se inserta la shape clonada. |
| source_shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | El [`IShape`](/slides/python-net/es/aspose.slides/ishape) a clonar. |
| x | **float** | La coordenada x del marco de la shape clonada, en puntos. |
| y | **float** | La coordenada y del marco de la shape clonada, en puntos. |
| width | **float** | El ancho del marco de la shape clonada, en puntos. |
| height | **float** | La altura del marco de la shape clonada, en puntos. |



### Ver también
* clase [`IShape`](/slides/python-net/es/aspose.slides/ishape)
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)