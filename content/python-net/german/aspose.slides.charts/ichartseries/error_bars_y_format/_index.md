---
title: error_bars_y_format property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartseries/error_bars_y_format/
weight: 120
---
## error_bars_y_format Eigenschaft
Stellt ErrorBars von Serien mit Richtung Y dar.

            ErrorBars mit Y-Richtung sind für Serien vom Typ area, bar, line, scatter und bubble verfügbar.
            Für alle anderen Diagrammtypen gibt diese Eigenschaft None zurück (einschließlich 3D-Diagramme).
            Im Falle benutzerdefinierter Werte verwenden Sie die DataPoints-Sammlung, um den Wert anzugeben
            (mit [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) Eigenschaft).

            Nur lesbar [`IErrorBarsFormat`](/slides/python-net/de/aspose.slides.charts/ierrorbarsformat).

### Definition:
```python
@property
def error_bars_y_format(self):
    ...
```

### Siehe auch
* Klasse [`IChartSeries`](/slides/python-net/de/aspose.slides.charts/ichartseries)
* Klasse [`IErrorBarsFormat`](/slides/python-net/de/aspose.slides.charts/ierrorbarsformat)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)