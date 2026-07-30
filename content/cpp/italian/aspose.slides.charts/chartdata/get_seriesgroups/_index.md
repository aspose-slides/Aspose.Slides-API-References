---
title: get_SeriesGroups()
second_title: Riferimento API di Aspose.Slides per C++
description: Recupera i gruppi di serie. Solo lettura IChartSeriesGroupCollection.
type: docs
weight: 27
url: /it/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() metodo


Recupera i gruppi di serie. Solo lettura [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## Osservazioni


1) Ogni gruppo di serie contiene serie con tipi combinabili. I gruppi di tipi di serie combinabili sono definiti e descritti con l'enumerazione CombinableSeriesTypesGroup. Inoltre, ogni gruppo di serie contiene serie che vengono tracciate sia sugli assi primari sia sugli assi secondari (non entrambi i casi nello stesso gruppo). Pertanto, il principio del raggruppamento delle serie è un raggruppamento per i gruppi di tipo sopra menzionati e per il tipo di tracciamento primario/secondario.

2) Un gruppo di serie contiene alcune proprietà delle serie che sono comuni a ciascuna serie nel gruppo ("series group properties"). Le "series group properties" nella classe [ChartSeriesGroup](../../chartseriesgroup/) sono di lettura/scrittura. Ognuna delle "series group properties" può avere una proiezione solo lettura nella classe [ChartSeries](../../chartseries/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Classe [ChartData](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)