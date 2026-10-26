---
title: insert_auto_shape method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado,
            aplicando el formato de plantilla predeterminado.

### Devuelve

La [`IAutoShape`](/slides/python-net/es/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que se inserta la nueva forma automática. |
| shape_type | [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) | La [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) de la forma automática a insertar. |
| x | **float** | La coordenada x del marco de la forma, en puntos. |
| y | **float** | La coordenada y del marco de la forma, en puntos. |
| width | **float** | El ancho del marco de la forma, en puntos. |
| height | **float** | El alto del marco de la forma, en puntos. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado,
            opcionalmente inicializándola con el estilo de plantilla predeterminado.

### Devuelve

La [`IAutoShape`](/slides/python-net/es/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que se inserta la forma automática. |
| shape_type | [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) | La [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) de la forma automática a insertar. |
| x | **float** | La coordenada x del marco de la forma, en puntos. |
| y | **float** | La coordenada y del marco de la forma, en puntos. |
| width | **float** | El ancho del marco de la forma, en puntos. |
| height | **float** | El alto del marco de la forma, en puntos. |
| create_from_template | **bool** | True para aplicar el estilo de plantilla predeterminado (incluyendo un nombre no vacío, estilo simple y texto centrado); false para crear la forma con todas las propiedades establecidas en sus valores predeterminados. |



### Ver también
* clase [`IAutoShape`](/slides/python-net/es/aspose.slides/iautoshape)
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* enumeración [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)