---
title: add method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
Aggiungi una nuova cella alla raccolta.

```python
def add(self, cell):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell) | Nuova cella da aggiungere. |

## add(self, value) {#any}
Crea [`ChartDataCell`](/slides/python-net/it/aspose.slides.charts/chartdatacell) dal valore specificato e lo aggiunge alla raccolta.

```python
def add(self, value):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| value | **any** | Il valore. |

### Osservazioni

Questo metodo aggiunge un foglio di lavoro con nome AUTO_DATA e vi aggiunge tutti i valori.  Se utilizzi [`ChartDataWorkbook`](/slides/python-net/it/aspose.slides.charts/chartdataworkbook) per aggiungere o modificare i valori delle celle, assicurati di non utilizzare questo foglio di lavoro.
Il numero massimo di valori aggiunti con questo metodo non deve superare 16711680

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | se supera il limite |

### Vedi anche
* classe [`ChartCellCollection`](/slides/python-net/it/aspose.slides.charts/chartcellcollection)
* classe [`ChartDataCell`](/slides/python-net/it/aspose.slides.charts/chartdatacell)
* classe [`ChartDataWorkbook`](/slides/python-net/it/aspose.slides.charts/chartdataworkbook)
* classe [`IChartDataCell`](/slides/python-net/it/aspose.slides.charts/ichartdatacell)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)