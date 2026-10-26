---
title: set_external_workbook method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Imposta una cartella di lavoro esterna come origine dati per il grafico. I dati del grafico verranno aggiornati dalla cartella di lavoro di destinazione.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | Percorso della cartella di lavoro di destinazione |

### Eccezioni

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | La cartella di lavoro esterna non è disponibile o non può essere caricata. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Imposta una cartella di lavoro esterna come origine dati per il grafico.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | Percorso della cartella di lavoro di destinazione |
| update_chart_data | **bool** | Se il valore è false verrà aggiornato solo il percorso della cartella di lavoro. <br/><br/>             I dati del grafico non verranno caricati né aggiornati dalla cartella di lavoro di destinazione. Può essere usato quando la cartella di lavoro di destinazione non esiste o non è disponibile.<br/><br/>             Se il valore è true i dati del grafico verranno aggiornati dalla cartella di lavoro di destinazione. |

### Eccezioni

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | La cartella di lavoro esterna non è disponibile o non può essere caricata. |



### Vedi anche
* classe [`IChartData`](/slides/python-net/it/aspose.slides.charts/ichartdata)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)