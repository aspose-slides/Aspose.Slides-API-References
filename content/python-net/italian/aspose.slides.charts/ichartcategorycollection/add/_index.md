---
title: add method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Se la categoria esiste nella collezione, la restituisce. Altrimenti crea una nuova categoria di grafico da [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell) e la aggiunge alla collezione.

### Restituisce

Categoria aggiunta o esistente.

```python
def add(self, chart_data_cell):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell) | Cell used to create chart category. |

## add(self, value) {#any}
Crea un nuovo [`IChartCategory`](/slides/python-net/it/aspose.slides.charts/ichartcategory) dal valore e lo aggiunge alla collezione.

### Restituisce

Aggiunto [`IChartCategory`](/slides/python-net/it/aspose.slides.charts/ichartcategory).

```python
def add(self, value):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | **any** | Il valore. |

### Osservazioni

Questo metodo aggiunge un foglio di lavoro con nome AUTO_DATA e vi aggiunge tutti i valori. Se usi [`IChartDataWorkbook`](/slides/python-net/it/aspose.slides.charts/ichartdataworkbook) per aggiungere o modificare i valori delle celle, assicurati di non utilizzare questo foglio di lavoro
Il numero massimo di valori aggiunti con questo metodo non deve superare 16711680

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | se il limite è superato |

### Vedi anche
* classe [`IChartCategory`](/slides/python-net/it/aspose.slides.charts/ichartcategory)
* classe [`IChartCategoryCollection`](/slides/python-net/it/aspose.slides.charts/ichartcategorycollection)
* classe [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell)
* classe [`IChartDataWorkbook`](/slides/python-net/it/aspose.slides.charts/ichartdataworkbook)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)