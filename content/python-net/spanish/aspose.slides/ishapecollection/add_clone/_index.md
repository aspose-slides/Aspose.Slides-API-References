---
title: add_clone method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ishapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Crea una copia de la forma especificada y la agrega al final de la colección de formas.
La forma clonada mantiene la posición y el tamaño del original.

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
La nueva forma mantiene el ancho y la altura del `source_shape`.

### Devuelve

El [`IShape`](/slides/python-net/es/aspose.slides/ishape) recién creado.



```python
def add_clone(self, source_shape, x, y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/es/aspose.slides/ishape) | El [`IShape`](/slides/python-net/es/aspose.slides/ishape) a clonar. |
| x | **float** | La coordenada x del marco de la forma clonada, en puntos. |
| y | **float** | La coordenada y del marco de la forma clonada, en puntos. |


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
| x | **float** | La coordenada x del marco de la forma clonada, en puntos. |
| y | **float** | La coordenada y del marco de la forma clonada, en puntos. |
| width | **float** | El ancho del marco de la forma clonada, en puntos. |
| height | **float** | La altura del marco de la forma clonada, en puntos. |



### Ver también
* clase [`IShape`](/slides/python-net/es/aspose.slides/ishape)
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)