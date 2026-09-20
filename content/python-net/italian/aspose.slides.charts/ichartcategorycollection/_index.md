---
title: IChartCategoryCollection class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection classe

Rappresenta la raccolta di [`IChartCategory`](/slides/python-net/it/aspose.slides.charts/ichartcategory)

Il tipo IChartCategoryCollection espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`use_cells`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection/use_cells/) | Se vero, allora il foglio di lavoro è usato per memorizzare le categorie (questo caso supporta categorie a più livelli).<br/>            Se falso, il foglio di lavoro NON è usato per memorizzare i valori (e questo caso non supporta categorie a <br/>            più livelli).<br/>            Lettura/scrittura **bool**. |
| [`grouping_level_count`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | Restituisce il conteggio dei livelli di raggruppamento delle categorie utilizzati.<br/>            È più di uno per categorie multilivello.<br/>            Solamente lettura **int**. |

Ottiene l'elemento all'indice specificato.

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | Se la categoria esiste nella raccolta, la restituisce. Altrimenti crea una nuova categoria di grafico da [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell) e la aggiunge alla raccolta. |
| [`add(self, value)`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection/add/#any) | Crea un nuovo [`IChartCategory`](/slides/python-net/it/aspose.slides.charts/ichartcategory) dal valore e lo aggiunge alla raccolta. |
| [`index_of(self, value)`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | Cerca il [`IChartCategory`](/slides/python-net/it/aspose.slides.charts/ichartcategory) specificato e restituisce l'indice basato su zero della prima occorrenza all'interno dell'intera Collezione |
| [`remove(self, value)`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | Rimuove il valore specificato. |
| [`remove_at(self, index)`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | Rimuove l'elemento all'indice fornito. |
| [`clear(self)`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection/clear/#) | Rimuove tutti gli elementi dalla raccolta. |


### Vedi anche
* classe [`IChartCategory`](/slides/python-net/it/aspose.slides.charts/ichartcategory)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)