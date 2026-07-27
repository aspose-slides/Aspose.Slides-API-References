---
title: InsertChart()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de ejemplo, y lo inserta en la colección de formas en el índice especificado.
type: docs
weight: 53
url: /es/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) método


Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de ejemplo, y lo inserta en la colección de formas en el índice especificado.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | El tipo de gráfico a crear. |
| x | **float** | La coordenada x del nuevo gráfico, en puntos. |
| y | **float** | La coordenada y del nuevo gráfico, en puntos. |
| width | **float** | El ancho del nuevo gráfico, en puntos. |
| height | **float** | La altura del nuevo gráfico, en puntos. |
| index | **int32_t** | El índice basado en cero en el que insertar el nuevo gráfico en la colección de formas. |

### Valor de retorno

El [Charts::IChart](../../../aspose.slides.charts/ichart/) recién creado.

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) método


Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de ejemplo, y lo inserta en la colección de formas en el índice especificado.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | El tipo de gráfico a crear. |
| x | **float** | La coordenada x del nuevo gráfico, en puntos. |
| y | **float** | La coordenada y del nuevo gráfico, en puntos. |
| width | **float** | El ancho del nuevo gráfico, en puntos. |
| height | **float** | La altura del nuevo gráfico, en puntos. |
| index | **int32_t** | El índice basado en cero en el que insertar el nuevo gráfico en la colección de formas. |
| initWithSample | **bool** | True para inicializar el nuevo gráfico con datos y configuraciones de series de ejemplo; false para crear el gráfico sin series y solo con configuraciones mínimas, lo que hace la creación más rápida. |

### Valor de retorno

El [Charts::IChart](../../../aspose.slides.charts/ichart/) recién creado.

## Ver también

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)