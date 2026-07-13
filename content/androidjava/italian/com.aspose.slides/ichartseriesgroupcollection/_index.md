---
title: IChartSeriesGroupCollection
second_title: Riferimento API Java per Aspose.Slides su Android
description: Rappresenta la collezione di gruppi di serie combinabili.
type: docs
url: /it/com.aspose.slides/ichartseriesgroupcollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Rappresenta la collezione di gruppi di serie combinabili.

--------------------

1) Ogni gruppo di serie contiene serie con tipi combinabili. I gruppi di tipi di serie combinabili sono definiti e descritti con l'enumerazione CombinableSeriesTypesGroup. Inoltre, ogni gruppo di serie contiene serie che vengono tracciate su assi primari o su assi secondari (non entrambi i casi nello stesso gruppo). Pertanto, il principio del raggruppamento delle serie è un raggruppamento per i gruppi di tipo sopra menzionati e per il tipo di tracciamento primario/secondario. 2) Un gruppo di serie contiene alcune proprietà delle serie che sono comuni a ciascuna serie nel gruppo ("properties del gruppo di serie"). Le "properties del gruppo di serie" nella classe ChartSeriesGroup sono leggibili/scrivibili. Ognuna delle "properties del gruppo di serie" può avere una proiezione di sola lettura nella classe ChartSeries.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Ottiene il gruppo di serie per serie. |
| [get_Item(int index)](#get-Item-int-) | Ottiene il gruppo di serie per indice. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```

Ottiene il gruppo di serie per serie.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Restituisce:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```

Ottiene il gruppo di serie per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)