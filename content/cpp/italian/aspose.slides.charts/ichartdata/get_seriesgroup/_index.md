---
title: get_SeriesGroup()
second_title: Riferimento API Aspose.Slides per C++
description: 
type: docs
weight: 222
url: /it/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) metodo




```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) metodo


Restituisce il gruppo di serie all&#39;indice specificato.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## Osservazioni


1) Ogni gruppo di serie contiene serie con tipi combinabili. I gruppi di tipi di serie combinabili sono definiti e descritti con l&#39;enum CombinableSeriesTypesGroup. Inoltre ogni gruppo di serie contiene serie che sono tracciate sia sugli assi primari sia sugli assi secondari (non entrambi i casi in un unico gruppo). Quindi, il principio di raggruppamento delle serie è un raggruppamento per i gruppi di tipo menzionati sopra e per il tipo di tracciamento primario/secondario. 2) Il gruppo di serie contiene alcune proprietà di serie che sono comuni a ciascuna serie nel gruppo (\"proprietà del gruppo di serie\"). \"Proprietà del gruppo di serie\" nella classe [ChartSeriesGroup](../../chartseriesgroup/) è lettura/scrittura. Ognuna delle \"proprietà del gruppo di serie\" può avere una proiezione di sola lettura nella classe [ChartSeries](../../chartseries/). 

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartSeriesGroup](../../ichartseriesgroup/)
* Classe [IChartSeries](../../ichartseries/)
* Classe [IChartData](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)