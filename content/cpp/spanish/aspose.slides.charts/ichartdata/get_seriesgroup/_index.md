---
title: get_SeriesGroup()
second_title: Referencia API de Aspose.Slides para C++
description: 
type: docs
weight: 222
url: /es/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) método


```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) método

Devuelve el grupo de series en el índice especificado.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## Observaciones

1) Cada grupo de series contiene series con tipos combinables. Los grupos de tipos de series combinables se definen y describen con el enum CombinableSeriesTypesGroup. Además, cada grupo de series contiene series que se trazan ya sea en ejes primarios o en ejes secundarios (no ambos casos en un mismo grupo). Así, el principio de agrupación de series es agrupar por los grupos de tipo mencionados anteriormente y por el tipo de trazado primario/secundario. 2) El grupo de series contiene algunas propiedades de series que son comunes a cada serie del grupo (\"propiedades del grupo de series\"). \"Propiedades del grupo de series\" en la clase [ChartSeriesGroup](../../chartseriesgroup/) es lectura/escritura. Cada una de las \"propiedades del grupo de series\" puede tener una proyección de solo lectura en la clase [ChartSeries](../../chartseries/).

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IChartSeriesGroup](../../ichartseriesgroup/)
* Clase [IChartSeries](../../ichartseries/)
* Clase [IChartData](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)