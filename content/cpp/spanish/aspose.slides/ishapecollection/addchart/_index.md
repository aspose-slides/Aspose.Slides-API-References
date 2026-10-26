---
title: AddChart()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un nuevo gráfico, lo inicializa con datos de series de muestra y configuraciones, y lo agrega al final de la colección de formas.
type: docs
weight: 27
url: /es/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) method

Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de muestra, y lo agrega al final de la colección de formas.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | El tipo de gráfico a agregar. |
| x | **float** | La coordenada x del nuevo gráfico, en puntos. |
| y | **float** | La coordenada y del nuevo gráfico, en puntos. |
| width | **float** | El ancho del gráfico, en puntos. |
| height | **float** | La altura del gráfico, en puntos. |

### Valor de retorno

El [Charts::IChart](../../../aspose.slides.charts/ichart/) recién creado.

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) method

Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de muestra, y lo agrega al final de la colección de formas.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | El tipo de gráfico a agregar. |
| x | **float** | La coordenada x del nuevo gráfico, en puntos. |
| y | **float** | La coordenada y del nuevo gráfico, en puntos. |
| width | **float** | El ancho del gráfico, en puntos. |
| height | **float** | La altura del gráfico, en puntos. |
| initWithSample | **bool** | True para inicializar el nuevo gráfico con datos y configuraciones de series de muestra; false para crear el gráfico sin series y solo con configuraciones mínimas, lo que hace que la creación sea más rápida. |

### Valor de retorno

El [Charts::IChart](../../../aspose.slides.charts/ichart/) recién creado.

## Ver también

* Enumeración [ChartType](../../../aspose.slides.charts/charttype/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IChart](../../../aspose.slides.charts/ichart/)
* Clase [IShapeCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)