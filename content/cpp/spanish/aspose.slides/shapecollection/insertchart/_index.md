---
title: InsertChart()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de ejemplo, y lo inserta en la colección de formas en el índice especificado.
type: docs
weight: 92
url: /es/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) método


Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de ejemplo, y lo inserta en la colección de formas en el índice especificado.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | El tipo de gráfico a crear. |
| x | **float** | La coordenada x del nuevo gráfico, en puntos. |
| y | **float** | La coordenada y del nuevo gráfico, en puntos. |
| width | **float** | El ancho del nuevo gráfico, en puntos. |
| height | **float** | La altura del nuevo gráfico, en puntos. |
| index | **int32_t** | El índice basado en cero en el que insertar el nuevo gráfico en la colección de formas. |

### Valor devuelto

El [Charts::IChart](../../../aspose.slides.charts/ichart/) recién creado.

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) método


Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de ejemplo, y lo inserta en la colección de formas en el índice especificado.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | El tipo de gráfico a crear. |
| x | **float** | La coordenada x del nuevo gráfico, en puntos. |
| y | **float** | La coordenada y del nuevo gráfico, en puntos. |
| width | **float** | El ancho del nuevo gráfico, en puntos. |
| height | **float** | La altura del nuevo gráfico, en puntos. |
| index | **int32_t** | El índice basado en cero en el que insertar el nuevo gráfico en la colección de formas. |
| initWithSample | **bool** | True para inicializar el nuevo gráfico con datos y configuraciones de series de ejemplo; false para crear el gráfico sin series y sólo con configuraciones mínimas, lo que hace que la creación sea más rápida. |

### Valor devuelto

El [Charts::IChart](../../../aspose.slides.charts/ichart/) recién creado.

## Ver también

* Enumeración [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IChart](../../../aspose.slides.charts/ichart/)
* Clase [ShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)