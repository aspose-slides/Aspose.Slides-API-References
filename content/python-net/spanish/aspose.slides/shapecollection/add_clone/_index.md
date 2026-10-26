---
title: add_clone method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/shapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Crea una copia de la forma especificada y la agrega al final de la colección de formas.
            La forma clonada conserva la posición y el tamaño del original.

### Devuelve

El [`IShape`](/slides/python-net/es/aspose.slides/ishape) recién creado.



```python
def add_clone(self, source_shape):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | El [`IShape`](/slides/python-net/es/aspose.slides/ishape) a clonar. |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
Crea una copia de la forma especificada y la agrega al final de la colección de formas.
            La nueva forma conserva el ancho y la altura del `source_shape`.

### Devuelve

El [`IShape`](/slides/python-net/es/aspose.slides/ishape) recién creado.



```python
def add_clone(self, source_shape, x, y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | La forma a clonar. |
| x | **float** | La coordenada x del marco de la nueva forma, en puntos. |
| y | **float** | La coordenada y del marco de la nueva forma, en puntos. |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Crea una copia de la forma especificada y la agrega al final de la colección de formas.

### Devuelve

El [`IShape`](/slides/python-net/es/aspose.slides/ishape) recién creado.



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | La forma a clonar. |
| x | **float** | La coordenada x del marco de la nueva forma, en puntos. |
| y | **float** | La coordenada y del marco de la nueva forma, en puntos. |
| width | **float** | El ancho del marco de la nueva forma, en puntos. |
| height | **float** | La altura del marco de la nueva forma, en puntos. |



### Ver también
* class [`IShape`](/slides/python-net/es/aspose.slides/ishape)
* class [`ShapeCollection`](/slides/python-net/es/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)