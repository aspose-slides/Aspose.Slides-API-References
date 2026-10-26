---
title: series_groups property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups proprietà
Restituisce i gruppi di serie.
            Sola lettura [`IChartSeriesGroupCollection`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroupcollection).


### Osservazioni

1) Ogni gruppo di serie contiene serie con tipi combinabili. I gruppi di tipi di serie combinabili sono definiti e descritti con l'enumerazione CombinableSeriesTypesGroup enum. Inoltre, ogni gruppo di serie contiene serie che vengono tracciate sia sull'asse primario sia sull'asse secondario (non entrambi i casi nello stesso gruppo). Pertanto, il principio del raggruppamento delle serie è un raggruppamento per i gruppi di tipo sopra menzionati e per il tipo di tracciamento primario/secondario.

2) Un gruppo di serie contiene alcune proprietà della serie che sono comuni a ogni serie nel gruppo ("proprietà del gruppo di serie"). "Proprietà del gruppo di serie" nella classe ChartSeriesGroup è read/write. Ciascuna delle "proprietà del gruppo di serie" può avere una proiezione a sola lettura nella classe ChartSeries.


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