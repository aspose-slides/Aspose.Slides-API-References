---
title: get_SeriesGroup()
second_title: Referencia de API de Aspose.Slides para C++
description: 
type: docs
weight: 222
url: /es/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) método




```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) método


Devuelve el grupo de series en el índice especificado.

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## Observaciones


1) Cada grupo de series contiene series con tipos combinables. Los grupos de tipos de series combinables están definidos y descritos con el enum CombinableSeriesTypesGroup. Además, cada grupo de series contiene series que se trazan en los ejes primarios o en los ejes secundarios (no ambos casos en un mismo grupo). Por lo tanto, el principio de agrupamiento de series es agrupar por los grupos de tipo mencionados anteriormente y por el tipo de trazado primario/secundario. 2) El grupo de series contiene algunas propiedades de series que son comunes a cada serie del grupo (\"series group properties\"). \"Series group properties\" en la clase [ChartSeriesGroup](../../chartseriesgroup/) es read/write. Cada una de las \"series group properties\" puede tener una proyección read-only en la clase [ChartSeries](../../chartseries/). 

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeriesGroup](../../ichartseriesgroup/)
* Class [IChartSeries](../../ichartseries/)
* Class [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)