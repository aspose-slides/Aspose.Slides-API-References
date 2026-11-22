---
title: refresh_data method
second_title: Aspose.Slides per Python tramite .NET - Riferimento API
description: 
type: docs
url: /it/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Aggiorna i dati del grafico ricaricandoli dalla cartella di lavoro di origine.


```python
def refresh_data(self):
    ...
```


### Osservazioni

Se il grafico utilizza una cartella di lavoro esterna, la cartella di lavoro deve essere accessibile al momento della chiamata.

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Lanciato quando il formato della cartella di lavoro non è supportato, oppure quando [`ChartData.data_source_type`](/slides/python-net/it/aspose.slides.charts/chartdata/data_source_type) è<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/it/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) e la cartella di lavoro esterna non può essere raggiunta o caricata. |



### Vedi anche
* classe [`ChartData`](/slides/python-net/it/aspose.slides.charts/chartdata)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)