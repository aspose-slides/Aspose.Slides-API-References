---
title: refresh_data method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Aktualisiert die Diagrammdaten, indem sie aus der Quellarbeitsmappe neu geladen werden.

```python
def refresh_data(self):
    ...
```

### Hinweise

Wenn das Diagramm eine externe Arbeitsmappe verwendet, muss die Arbeitsmappe zum Zeitpunkt des Aufrufs zugänglich sein.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Wird ausgelöst, wenn das Format der Arbeitsmappe nicht unterstützt wird, oder wenn [`IChartData.data_source_type`](/slides/python-net/de/aspose.slides.charts/ichartdata/data_source_type) ist<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/de/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) und die externe Arbeitsmappe nicht zugegriffen oder geladen werden kann. |

### Siehe auch
* Klasse [`IChartData`](/slides/python-net/de/aspose.slides.charts/ichartdata)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)