---
title: get_SeriesGroups()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene los grupos de series. Solo de lectura IChartSeriesGroupCollection.
type: docs
weight: 27
url: /es/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() método


Obtiene los grupos de series. Solo de lectura [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## Observaciones


1) Cada grupo de series contiene series con tipos combinables. Los grupos de tipos de series combinables se definen y describen con el enum CombinableSeriesTypesGroup. Además, cada grupo de series contiene series que se trazan ya sea en los ejes primarios o en los ejes secundarios (no ambos casos en un mismo grupo). Por lo tanto, el principio de agrupación de series es un agrupamiento por los grupos de tipos mencionados anteriormente y por el tipo de trazado primario/secundario.

2) Un grupo de series contiene algunas propiedades de series que son comunes para cada serie en el grupo ("propiedades del grupo de series"). Las "propiedades del grupo de series" en la clase [ChartSeriesGroup](../../chartseriesgroup/) son de lectura/escritura. Cada una de las "propiedades del grupo de series" puede tener una proyección de solo lectura en la clase [ChartSeries](../../chartseries/). 
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Clase [ChartData](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)