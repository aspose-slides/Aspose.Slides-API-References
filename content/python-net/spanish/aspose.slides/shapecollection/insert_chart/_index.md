---
title: insert_chart method
second_title: Referencia de la API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/shapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de ejemplo, y lo inserta en la colección de formas en el índice especificado.

### Devuelve

El [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart) recién creado.



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/es/aspose.slides.charts/charttype) | El tipo de gráfico a crear. |
| x | **float** | La coordenada x del nuevo gráfico, en puntos. |
| y | **float** | La coordenada y del nuevo gráfico, en puntos. |
| width | **float** | El ancho del nuevo gráfico, en puntos. |
| height | **float** | La altura del nuevo gráfico, en puntos. |
| index | **int** | El índice basado en cero en el que insertar el nuevo gráfico en la colección de formas. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de ejemplo, y lo inserta en la colección de formas en el índice especificado.

### Devuelve

El [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart) recién creado.



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/es/aspose.slides.charts/charttype) | El tipo de gráfico a crear. |
| x | **float** | La coordenada x del nuevo gráfico, en puntos. |
| y | **float** | La coordenada y del nuevo gráfico, en puntos. |
| width | **float** | El ancho del nuevo gráfico, en puntos. |
| height | **float** | La altura del nuevo gráfico, en puntos. |
| index | **int** | El índice basado en cero en el que insertar el nuevo gráfico en la colección de formas. |
| init_with_sample | **bool** | True para inicializar el nuevo gráfico con datos y configuraciones de series de ejemplo; <br/><br/> false para crear el gráfico sin series y solo con configuraciones mínimas, lo que hace que la creación sea más rápida. |



### Ver también
* enumeración [`ChartType`](/slides/python-net/es/aspose.slides.charts/charttype)
* clase [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart)
* clase [`ShapeCollection`](/slides/python-net/es/aspose.slides/shapecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)