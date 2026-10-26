---
title: set_range method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/ichartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Imposta l'intervallo dei dati del grafico. Le serie e le categorie verranno aggiornate in base al nuovo intervallo di dati.
            Se il numero di serie nell'intervallo dei dati è maggiore del conteggio delle serie nei dati del grafico, allora saranno aggiunte serie aggiuntive dello stesso tipo dell'ultima serie nella collezione corrente, alla fine della collezione.


```python
def set_range(self, formula):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| formula | **str** | La formula dell'intervallo di dati delle celle. Es.: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | formula è None. |
| **RuntimeError(Proxy error(ArgumentException))** | formula ha un formato non corretto. |



### Vedi anche
* classe [`IChartData`](/slides/python-net/it/aspose.slides.charts/ichartdata)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)