---
title: IChartSeriesGroupCollection class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartseriesgroupcollection/
---
## IChartSeriesGroupCollection classe

Rappresenta la collezione di gruppi di serie combinabili.

Il tipo IChartSeriesGroupCollection espone i seguenti membri:

Ottiene il gruppo di serie per indice.

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides.charts/ichartseriesgroupcollection/__getitem__/) |  |


### Osservazioni

1) Ogni gruppo di serie contiene serie con tipi combinabili. I gruppi di tipi di serie combinabili sono definiti e descritti con l'enumerazione CombinableSeriesTypesGroup. Inoltre ogni gruppo di serie contiene serie che vengono tracciate o sugli assi primari o sugli assi secondari (non entrambi i casi nello stesso gruppo). Quindi, il principio del raggruppamento delle serie è un raggruppamento per i gruppi di tipo menzionati sopra e per il tipo di tracciamento primario/secondario.

2) Il gruppo di serie contiene alcune proprietà delle serie che sono comuni a ogni serie nel gruppo ("series group properties"). "Series group properties" nella classe ChartSeriesGroup è read/write. Ciascuna delle "series group properties" può avere una proiezione read-only nella classe ChartSeries.

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)