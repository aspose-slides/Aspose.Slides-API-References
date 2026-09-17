---
title: add_auto_shape method
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Crea una nueva forma automática con formato predeterminado y la agrega al final de la colección de formas.

### Returns
El [`IAutoShape`](/slides/python-net/es/aspose.slides/iautoshape) recién creado.

```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) | El [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) de la forma automática a agregar. |
| x | **float** | La coordenada x del marco de la forma, en puntos. |
| y | **float** | La coordenada y del marco de la forma, en puntos. |
| width | **float** | El ancho del marco de la forma, en puntos. |
| height | **float** | La altura del marco de la forma, en puntos. |

## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Crea una nueva forma automática y la agrega al final de la colección de formas, opcionalmente inicializándola con el formato de plantilla predeterminado.

### Returns
El [`IAutoShape`](/slides/python-net/es/aspose.slides/iautoshape) recién creado.

```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) | El [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) de la forma automática a agregar. |
| x | **float** | La coordenada x del marco de la forma, en puntos. |
| y | **float** | La coordenada y del marco de la forma, en puntos. |
| width | **float** | El ancho del marco de la forma, en puntos. |
| height | **float** | La altura del marco de la forma, en puntos. |
| create_from_template | **bool** | True para aplicar el estilo de plantilla predeterminado (estilo simple, texto centrado y nombre no vacío)<br/><br/>            a la nueva forma; false para crear la forma con todas las propiedades establecidas a sus valores predeterminados. |

### Ver también
* clase [`IAutoShape`](/slides/python-net/es/aspose.slides/iautoshape)
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* enumeración [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)