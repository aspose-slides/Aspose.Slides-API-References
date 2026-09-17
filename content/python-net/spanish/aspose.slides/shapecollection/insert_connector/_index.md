---
title: insert_connector method
second_title: Referencia de la API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Crea una nueva forma de conector y la inserta en la colección de formas en el índice especificado,
            aplicando el estilo de plantilla predeterminado.

### Devuelve

El [`IConnector`](/slides/python-net/es/aspose.slides/iconnector) recién creado.



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que se inserta la forma de conector. |
| shape_type | [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) | El [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) de la forma de conector a insertar. |
| x | **float** | La coordenada x del marco del conector, en puntos. |
| y | **float** | La coordenada y del marco del conector, en puntos. |
| width | **float** | El ancho del marco del conector, en puntos. |
| height | **float** | La altura del marco del conector, en puntos. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Crea una nueva forma de conector y la inserta en la colección de formas en el índice especificado,
            aplicando opcionalmente el estilo de plantilla predeterminado.
### Devoluciones

El [`IConnector`](/slides/python-net/es/aspose.slides/iconnector) recién creado.

```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | El índice basado en cero en el que insertar la forma del conector. |
| shape_type | [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) | El [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype) de la forma del conector a insertar. |
| x | **float** | La coordenada x del marco del conector, en puntos. |
| y | **float** | La coordenada y del marco del conector, en puntos. |
| width | **float** | El ancho del marco del conector, en puntos. |
| height | **float** | La altura del marco del conector, en puntos. |
| create_from_template | **bool** | True para aplicar el estilo de plantilla predeterminado (nombre no vacío, estilo sencillo);<br/><br/> false para crear el conector con valores de propiedad predeterminados. |

### Ver también
* clase [`IConnector`](/slides/python-net/es/aspose.slides/iconnector)
* clase [`ShapeCollection`](/slides/python-net/es/aspose.slides/shapecollection)
* enumeración [`ShapeType`](/slides/python-net/es/aspose.slides/shapetype)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)