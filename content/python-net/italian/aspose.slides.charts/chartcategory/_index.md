---
title: ChartCategory class
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.charts/chartcategory/
---
## ChartCategory classe

Rappresenta le categorie del grafico.

Il tipo ChartCategory espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`use_cell`](/slides/python-net/it/aspose.slides.charts/chartcategory/use_cell/) | Se vero, la proprietà AsCell è effettiva. In altre parole, il worksheet è usato per <br/>            memorizzare la categoria (questo caso supporta una categoria a più livelli).<br/>            Se falso, la proprietà AsLiteral è effettiva. In altre parole, il worksheet NON è usato <br/>            per memorizzare la categoria (e questo caso non supporta categorie a più livelli).<br/>            Solo lettura **bool**. |
| [`as_cell`](/slides/python-net/it/aspose.slides.charts/chartcategory/as_cell/) | Restituisce o imposta l'oggetto IChartDataCell.<br/>            Se la categoria è a più livelli, allora viene usato l'oggetto IChartDataCell per il livello "0".<br/>            Lettura/scrittura [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/it/aspose.slides.charts/chartcategory/as_literal/) | Restituisce o imposta l'oggetto AsLiteral.<br/>            Lettura/scrittura **any**. |
| [`value`](/slides/python-net/it/aspose.slides.charts/chartcategory/value/) | Se UseCell è vero, questa proprietà rappresenta la proprietà AsCell.Value.<br/>            Se UseCell è falso, questa proprietà rappresenta la proprietà AsLiteral.<br/>            Lettura/scrittura **any**. |
| [`grouping_levels`](/slides/python-net/it/aspose.slides.charts/chartcategory/grouping_levels/) | Contenitore gestito dei valori dei livelli di raggruppamento della categoria del grafico.<br/>            Una categoria a più livelli contiene più di un livello di raggruppamento.<br/>            L'indicizzazione dei livelli di raggruppamento parte da zero.<br/>            Solo lettura [`IChartCategoryLevelsManager`](/slides/python-net/it/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`remove(self)`](/slides/python-net/it/aspose.slides.charts/chartcategory/remove/#) | Rimuove la categoria dal grafico. |

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)