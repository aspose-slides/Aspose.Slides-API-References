---
title: refresh_data method
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Aggiorna i dati del grafico ricaricandoli dal workbook di origine.

```python
def refresh_data(self):
    ...
```

### Osservazioni

Se il grafico utilizza un workbook esterno, il workbook deve essere accessibile al momento della chiamata.

### Eccezioni

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Generato quando il formato del workbook non è supportato, oppure quando [`IChartData.data_source_type`](/slides/python-net/it/aspose.slides.charts/ichartdata/data_source_type) è<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/it/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) e il workbook esterno non può essere accessibile o caricato. |

### Vedi anche
* classe [`IChartData`](/slides/python-net/it/aspose.slides.charts/ichartdata)
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)