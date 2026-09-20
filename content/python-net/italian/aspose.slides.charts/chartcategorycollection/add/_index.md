---
title: add method
second_title: Riferimento API di Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Se la categoria esiste nella raccolta, la restituisce. Altrimenti crea una nuova categoria di grafico da 
            [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell) e la aggiunge alla raccolta.

### Restituisce

Categoria aggiunta o esistente.



```python
def add(self, chart_data_cell):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell) | Cella usata per creare la categoria di grafico. |


## add(self, value) {#any}
Crea un nuovo [`ChartCategory`](/slides/python-net/it/aspose.slides.charts/chartcategory) dal valore e lo aggiunge alla raccolta.

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

Questo metodo aggiunge un foglio di lavoro con nome AUTO_DATA e vi inserisce tutti i valori.  Se usi [`ChartDataWorkbook`](/slides/python-net/it/aspose.slides.charts/chartdataworkbook) per aggiungere o modificare i valori delle celle, assicurati di non utilizzare questo foglio di lavoro
            Il numero massimo di valori aggiunti con questo metodo non deve superare 16711680

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | se il limite è superato |



### Vedi anche
* class [`ChartCategory`](/slides/python-net/it/aspose.slides.charts/chartcategory)
* class [`ChartCategoryCollection`](/slides/python-net/it/aspose.slides.charts/chartcategorycollection)
* class [`ChartDataWorkbook`](/slides/python-net/it/aspose.slides.charts/chartdataworkbook)
* class [`IChartCategory`](/slides/python-net/it/aspose.slides.charts/ichartcategory)
* class [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell)
* module [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)