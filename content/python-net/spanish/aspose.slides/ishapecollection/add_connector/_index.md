---
title: add_connector method
second_title: Referencia de la API Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Crea una nueva forma de conector con el estilo de plantilla predeterminado y la agrega al final de la colección de formas.

### Devuelve

El [`IConnector`](/slides/python-net/es/aspose.slides/iconnector) recién creado.



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) | El [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) de la forma de conector a agregar. |
| x | **float** | La coordenada x del marco del conector, en puntos. |
| y | **float** | La coordenada y del marco del conector, en puntos. |
| width | **float** | El ancho del marco del conector, en puntos. |
| height | **float** | La altura del marco del conector, en puntos. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Crea una nueva forma de conector y la agrega al final de la colección de formas, opcionalmente aplicando el estilo de plantilla predeterminado.

### Devuelve

El [`IConnector`](/slides/python-net/es/aspose.slides/iconnector) recién creado.



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) | El [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) de la forma de conector a crear. |
| x | **float** | La coordenada x del marco del conector, en puntos. |
| y | **float** | La coordenada y del marco del conector, en puntos. |
| width | **float** | El ancho del marco del conector, en puntos. |
| height | **float** | La altura del marco del conector, en puntos. |
| create_from_template | **bool** | True para aplicar el estilo de plantilla predeterminado (nombre no vacío, estilo simple); <br/><br/>false para crear el conector con los valores predeterminados de sus propiedades. |



### Ver también
* clase [`IConnector`](/slides/python-net/es/aspose.slides/iconnector)
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* enumeración [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)