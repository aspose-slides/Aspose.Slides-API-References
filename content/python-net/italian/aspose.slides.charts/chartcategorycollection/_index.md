---
title: ChartCategoryCollection class
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection classe

Rappresenta una collezione di [`ChartCategory`](/slides/python-net/it/aspose.slides.charts/chartcategory)

Il tipo ChartCategoryCollection espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`use_cells`](/slides/python-net/it/aspose.slides.charts/chartcategorycollection/use_cells/) | Se vero, il foglio di lavoro viene utilizzato per memorizzare le categorie (questo caso supporta categorie a più livelli).<br/>Se falso, il foglio di lavoro NON viene utilizzato per memorizzare i valori (e questo caso non supporta categorie a più livelli).<br/>Lettura/Scrittura **bool**. |
| [`grouping_level_count`](/slides/python-net/it/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | Restituisce il conteggio dei livelli di raggruppamento delle categorie utilizzati.<br/>È più di uno per categorie a più livelli.<br/>Solo lettura **int**. |

Ottiene l'elemento all'indice specificato.

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/it/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | Se la categoria esiste nella collezione, la restituisce.<br/>Altrimenti crea una nuova categoria di grafico da [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell) e la aggiunge alla collezione. |
| [`add(self, value)`](/slides/python-net/it/aspose.slides.charts/chartcategorycollection/add/#any) | Crea un nuovo [`ChartCategory`](/slides/python-net/it/aspose.slides.charts/chartcategory) dal valore e lo aggiunge alla collezione. |
| [`index_of(self, value)`](/slides/python-net/it/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | Cerca il [`ChartCategory`](/slides/python-net/it/aspose.slides.charts/chartcategory) specificato e restituisce l'indice basato su zero della prima occorrenza all'interno dell'intera Collection. |
| [`remove(self, value)`](/slides/python-net/it/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | Rimuove il valore specificato. |
| [`remove_at(self, index)`](/slides/python-net/it/aspose.slides.charts/chartcategorycollection/remove_at/#int) | Rimuove l'elemento all'indice specificato. |
| [`clear(self)`](/slides/python-net/it/aspose.slides.charts/chartcategorycollection/clear/#) | Rimuove tutti gli elementi dalla collezione. |

### Vedi anche
* classe [`ChartCategory`](/slides/python-net/it/aspose.slides.charts/chartcategory)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)