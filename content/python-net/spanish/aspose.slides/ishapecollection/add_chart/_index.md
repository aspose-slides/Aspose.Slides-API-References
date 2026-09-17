---
title: add_chart method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/ishapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
Crea un nuevo gráfico, lo inicializa con datos de serie de muestra y configuraciones, y lo agrega al final de la colección de formas.

### Devuelve

El [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart) recién creado.



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/es/aspose.slides.charts/charttype) | El tipo de gráfico a añadir. |
| x | **float** | La coordenada x del nuevo gráfico, en puntos. |
| y | **float** | La coordenada y del nuevo gráfico, en puntos. |
| width | **float** | El ancho del gráfico, en puntos. |
| height | **float** | La altura del gráfico, en puntos. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
Crea un nuevo gráfico, lo inicializa con datos de serie de muestra y configuraciones, y lo agrega al final de la colección de formas.

### Devuelve

El [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart) recién creado.



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/es/aspose.slides.charts/charttype) | El tipo de gráfico a añadir. |
| x | **float** | La coordenada x del nuevo gráfico, en puntos. |
| y | **float** | La coordenada y del nuevo gráfico, en puntos. |
| width | **float** | El ancho del gráfico, en puntos. |
| height | **float** | La altura del gráfico, en puntos. |
| init_with_sample | **bool** | True para inicializar el nuevo gráfico con datos y configuraciones de serie de muestra; <br/><br/>            false para crear el gráfico sin series y solo con configuraciones mínimas, lo que acelera la creación. |



### Ver también
* enumeración [`ChartType`](/slides/python-net/es/aspose.slides.charts/charttype)
* clase [`IChart`](/slides/python-net/es/aspose.slides.charts/ichart)
* clase [`IShapeCollection`](/slides/python-net/es/aspose.slides/ishapecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)