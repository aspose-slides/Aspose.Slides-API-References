---
title: set_external_workbook method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/chartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
Imposta un workbook esterno come origine dati per il grafico. I dati del grafico saranno aggiornati dal workbook di destinazione.

```python
def set_external_workbook(self, workbook_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| workbook_path | **str** | Percorso del workbook di destinazione |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Il workbook esterno non è disponibile o non può essere caricato. |

## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Imposta un workbook esterno come origine dati per il grafico.

```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| workbook_path | **str** | Percorso del workbook di destinazione |
| update_chart_data | **bool** | Se il valore è false solo il percorso del workbook verrà aggiornato. <br/><br/> I dati del grafico non saranno caricati né aggiornati dal workbook di destinazione. Può essere usato quando il workbook di destinazione non esiste o non è disponibile.<br/><br/> Se il valore è true i dati del grafico saranno aggiornati dal workbook di destinazione. |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Il workbook esterno non è disponibile o non può essere caricato. |

### Vedi anche
* classe [`ChartData`](/slides/python-net/it/aspose.slides.charts/chartdata)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)