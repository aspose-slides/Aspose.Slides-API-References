---
title: add method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Aggiungi nuova cella alla raccolta.


```python
def add(self, chart_data_cell):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell) | Nuova cella da aggiungere. |


## add(self, value) {#any}
Crea [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell) dal valore specificato e lo aggiunge alla raccolta.


```python
def add(self, value):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | **any** | Il valore. |

### Osservazioni

Questo metodo aggiunge un foglio di lavoro con nome AUTO_DATA e aggiunge tutti i valori lì.  Se usi [`IChartDataWorkbook`](/slides/python-net/it/aspose.slides.charts/ichartdataworkbook) per aggiungere o modificare i valori delle Cell, assicurati di non utilizzare questo foglio di lavoro
            Il numero massimo di valori aggiunti con questo metodo non deve superare 16711680

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | se il limite è superato |



### Vedi anche
* classe [`IChartCellCollection`](/slides/python-net/it/aspose.slides.charts/ichartcellcollection)
* classe [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell)
* classe [`IChartDataWorkbook`](/slides/python-net/it/aspose.slides.charts/ichartdataworkbook)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)