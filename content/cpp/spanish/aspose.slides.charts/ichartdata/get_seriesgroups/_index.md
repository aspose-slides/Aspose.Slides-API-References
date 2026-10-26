---
title: get_SeriesGroups()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene los grupos de series. Solo lectura IChartSeriesGroupCollection.
type: docs
weight: 27
url: /es/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() método

Obtiene los grupos de series. Sólo lectura [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## Observaciones

1) Cada grupo de series contiene series con tipos combinables. Los grupos de tipos de series combinables están definidos y descritos con el enum CombinableSeriesTypesGroup. Además, cada grupo de series contiene series que se trazan ya sea en los ejes primarios o en los ejes secundarios (no ambos casos en un mismo grupo). Por lo tanto, el principio de agrupación de series es una agrupación por los grupos de tipos mencionados arriba y por el tipo de trazado primario/secundario.

2) El grupo de series contiene algunas propiedades de series que son comunes a cada serie del grupo ("series group properties"). "Series group properties" en la clase [ChartSeriesGroup](../../chartseriesgroup/) es de lectura/escritura. Cada una de las "series group properties" puede tener una proyección de solo lectura en la clase [ChartSeries](../../chartseries/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Clase [IChartData](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)