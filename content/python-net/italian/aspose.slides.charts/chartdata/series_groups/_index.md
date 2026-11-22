---
title: series_groups property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups proprietà
Ottiene i gruppi di serie.
Solo lettura [`IChartSeriesGroupCollection`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroupcollection).

### Osservazioni

1) Ogni gruppo di serie contiene serie con tipi combinabili. I gruppi di tipi di serie combinabili sono definiti e descritti con l'enum CombinableSeriesTypesGroup. Inoltre, ogni gruppo di serie contiene serie che vengono tracciate sia sugli assi primari sia sugli assi secondari (non entrambi i casi nello stesso gruppo). Quindi, il principio del raggruppamento delle serie è un raggruppamento per i gruppi di tipo menzionati sopra e per il tipo di tracciamento primario/secondario.

2) Un gruppo di serie contiene alcune proprietà delle serie che sono comuni a ciascuna serie nel gruppo "proprietà del gruppo di serie". "Proprietà del gruppo di serie" nella classe ChartSeriesGroup è lettura/scrittura. Ognuna delle "proprietà del gruppo di serie" può avere una proiezione solo lettura nella classe ChartSeries.

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