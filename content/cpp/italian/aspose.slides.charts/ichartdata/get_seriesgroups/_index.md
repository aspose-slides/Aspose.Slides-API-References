---
title: get_SeriesGroups()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene i gruppi di serie. Solo lettura IChartSeriesGroupCollection.
type: docs
weight: 27
url: /it/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() metodo

Ottiene i gruppi di serie. Solo lettura [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## Osservazioni

1) Ogni gruppo di serie contiene serie con tipi combinabili. I gruppi di tipi di serie combinabili sono definiti e descritti con l'enum CombinableSeriesTypesGroup. Inoltre ogni gruppo di serie contiene serie che vengono tracciate sull'asse primario o sull'asse secondario (non entrambi i casi nello stesso gruppo). Quindi, il principio del raggruppamento delle serie è un raggruppamento per i gruppi di tipo menzionati sopra e per il tipo di tracciamento primario/secondario.

2) Il gruppo di serie contiene alcune proprietà della serie che sono comuni a ogni serie nel gruppo (\"proprietà del gruppo di serie\"). \"Proprietà del gruppo di serie\" nella classe [ChartSeriesGroup](../../chartseriesgroup/) è lettura/scrittura. Ognuna delle \"proprietà del gruppo di serie\" può avere una proiezione sola lettura nella classe [ChartSeries](../../chartseries/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Classe [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)