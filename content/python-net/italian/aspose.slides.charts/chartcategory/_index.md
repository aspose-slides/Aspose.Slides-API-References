---
title: ChartCategory class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/chartcategory/
---
## classe ChartCategory

Rappresenta le categorie del grafico.

Il tipo ChartCategory espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`use_cell`](/slides/python-net/it/aspose.slides.charts/chartcategory/use_cell/) | Se true, allora la proprietà AsCell è effettiva. In altre parole, il foglio di lavoro è usato per <br/> memorizzare la categoria (questo caso supporta una categoria a più livelli).<br/> Se false, allora la proprietà AsLiteral è effettiva. In altre parole, il foglio di lavoro NON è usato <br/> per memorizzare la categoria (e questo caso non supporta categorie a più livelli).<br/> Sola lettura **bool**. |
| [`as_cell`](/slides/python-net/it/aspose.slides.charts/chartcategory/as_cell/) | Restituisce o imposta l'oggetto IChartDataCell.<br/> Se la categoria è a più livelli, allora viene usato l'oggetto IChartDataCell per il livello "0".<br/> Lettura/scrittura [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/it/aspose.slides.charts/chartcategory/as_literal/) | Restituisce o imposta l'oggetto AsLiteral.<br/> Lettura/scrittura **any**. |
| [`value`](/slides/python-net/it/aspose.slides.charts/chartcategory/value/) | Se UseCell è true, allora questa proprietà rappresenta la proprietà AsCell.Value.<br/> Se UseCell è false, allora questa proprietà rappresenta la proprietà AsLiteral.<br/> Lettura/scrittura **any**. |
| [`grouping_levels`](/slides/python-net/it/aspose.slides.charts/chartcategory/grouping_levels/) | Contenitore gestito dei valori dei livelli di raggruppamento della categoria del grafico.<br/> Una categoria a più livelli contiene più di un livello di raggruppamento.<br/> L'indicizzazione dei livelli di raggruppamento parte da zero.<br/> Sola lettura [`IChartCategoryLevelsManager`](/slides/python-net/it/aspose.slides.charts/ichartcategorylevelsmanager). |
| [`cached_value`](/slides/python-net/it/aspose.slides.charts/chartcategory/cached_value/) | Ottiene il valore memorizzato nella cache di una categoria del grafico.<br/> Sola lettura [`ICachedChartValue`](/slides/python-net/it/aspose.slides.charts/icachedchartvalue). |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`remove(self)`](/slides/python-net/it/aspose.slides.charts/chartcategory/remove/#) | Rimuove la categoria dal grafico. |

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)