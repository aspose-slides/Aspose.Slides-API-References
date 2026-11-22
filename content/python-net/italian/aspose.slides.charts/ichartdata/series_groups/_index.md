---
title: series_groups property
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups proprietà
Restituisce i gruppi di serie.
Sola lettura [`IChartSeriesGroupCollection`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroupcollection).

### Osservazioni

1) Ogni gruppo di serie contiene serie con tipi combinabili. I gruppi di tipi di serie combinabili sono definiti e descritti con l'enumerazione CombinableSeriesTypesGroup. Inoltre ogni gruppo di serie contiene serie che vengono tracciate sia sugli assi primari sia sugli assi secondari (non entrambi i casi nello stesso gruppo). Quindi, il principio del raggruppamento delle serie è un raggruppamento per i gruppi di tipo menzionati sopra e per il tipo di tracciamento primario/secondario.

2) Un gruppo di serie contiene alcune proprietà delle serie che sono comuni a tutte le serie del gruppo ("proprietà del gruppo di serie"). Le "proprietà del gruppo di serie" nella classe ChartSeriesGroup sono di lettura/scrittura. Ognuna delle "proprietà del gruppo di serie" può avere una proiezione sola lettura nella classe ChartSeries.

### Definizione:
```python
@property
def series_groups(self):
    ...
```

### Vedi anche
* classe [`IChartData`](/slides/python-net/it/aspose.slides.charts/ichartdata)
* classe [`IChartSeriesGroupCollection`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroupcollection)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)