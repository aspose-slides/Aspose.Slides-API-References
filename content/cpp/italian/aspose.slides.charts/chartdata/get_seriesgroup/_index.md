---
title: get_SeriesGroup()
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 222
url: /it/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) metodo




```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) metodo


Restituisce il gruppo di serie all'indice specificato.

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## Osservazioni


1) Ogni gruppo di serie contiene serie con tipi combinabili. I gruppi di tipi di serie combinabili sono definiti e descritti con l'enumerazione CombinableSeriesTypesGroup. Inoltre ogni gruppo di serie contiene serie che vengono tracciate sia sugli assi primari sia sugli assi secondari (non entrambi i casi nello stesso gruppo). Quindi, il principio di raggruppamento delle serie è un raggruppamento per i gruppi di tipo menzionati sopra e per il tipo di tracciamento primario/secondario. 2) Il gruppo di serie contiene alcune proprietà delle serie comuni a tutte le serie del gruppo (\"series group properties\"). Le \"series group properties\" nella classe [ChartSeriesGroup](../../chartseriesgroup/) sono read/write. Ognuna delle \"series group properties\" può avere una proiezione read-only nella classe [ChartSeries](../../chartseries/). 

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartSeriesGroup](../../ichartseriesgroup/)
* Classe [IChartSeries](../../ichartseries/)
* Classe [ChartData](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)