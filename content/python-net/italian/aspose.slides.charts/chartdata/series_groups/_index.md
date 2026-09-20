---
title: series_groups property
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups property
Ottiene i gruppi di serie.
            Solo lettura [`IChartSeriesGroupCollection`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroupcollection).


### Osservazioni

1) Ogni gruppo di serie contiene serie con tipi combinabili. I gruppi di tipi di serie combinabili sono definiti e descritti con l'enumerazione CombinableSeriesTypesGroup enum.
            Inoltre, ogni gruppo di serie contiene serie che vengono tracciate su assi primari o su assi secondari (non entrambi i casi nello stesso gruppo).
            Pertanto, il principio del raggruppamento delle serie è un raggruppamento per i gruppi di tipi menzionati sopra e per il tipo di tracciamento primario/secondario.
            
            2) Il gruppo di serie contiene alcune proprietà delle serie che sono comuni a ogni serie nel gruppo ("properties del gruppo di serie").
            "Series group properties" nella classe ChartSeriesGroup è lettura/scrittura.
            Ognuna delle "series group properties" può avere una proiezione di sola lettura nella classe ChartSeries.

### Definizione:
```python
@property
def series_groups(self):
    ...
```


### Vedi anche
* classe [`ChartData`](/slides/python-net/it/aspose.slides.charts/chartdata)
* classe [`IChartSeriesGroupCollection`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroupcollection)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)