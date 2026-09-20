---
title: IChartCategory class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartcategory/
---
## IChartCategory classe

Rappresenta le categorie del grafico.

Il tipo IChartCategory espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`use_cell`](/slides/python-net/it/aspose.slides.charts/ichartcategory/use_cell/) | Se true allora la proprietà AsCell è effettiva. In altre parole, il foglio di lavoro è usato per <br/>            memorizzare la categoria (questo caso supporta una categoria a più livelli).<br/>            Se false allora la proprietà AsLiteral è effettiva. In altre parole, il foglio di lavoro NON è usato <br/>            per memorizzare la categoria (e questo caso non supporta categorie a più livelli).<br/>            Solo lettura **bool**. |
| [`as_cell`](/slides/python-net/it/aspose.slides.charts/ichartcategory/as_cell/) | Restituisce o imposta l'oggetto IChartDataCell.<br/>            Se la categoria è a più livelli allora viene usato l'oggetto IChartDataCell per il livello "0".<br/>            Lettura/scrittura [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/it/aspose.slides.charts/ichartcategory/as_literal/) | Restituisce o imposta AsLiteral se UseCell è false.<br/>            Lettura/scrittura **any**. |
| [`value`](/slides/python-net/it/aspose.slides.charts/ichartcategory/value/) | Se UseCell è true allora questa proprietà rappresenta la proprietà AsCell.Value.<br/>            Se UseCell è false allora questa proprietà rappresenta la proprietà AsLiteral.<br/>            Lettura/scrittura **any**. |
| [`grouping_levels`](/slides/python-net/it/aspose.slides.charts/ichartcategory/grouping_levels/) | Contenitore gestito dei valori dei livelli di raggruppamento della categoria del grafico.<br/>            La categoria a più livelli contiene più di un livello di raggruppamento.<br/>            L'indicizzazione dei livelli di raggruppamento è basata su zero.<br/>            Solo lettura [`IChartCategoryLevelsManager`](/slides/python-net/it/aspose.slides.charts/ichartcategorylevelsmanager). |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`remove(self)`](/slides/python-net/it/aspose.slides.charts/ichartcategory/remove/#) | Rimuove la categoria dal grafico. |

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)