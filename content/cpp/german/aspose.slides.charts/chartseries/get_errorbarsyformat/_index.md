---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt ErrorBars einer Serie mit Richtung Y dar.
type: docs
weight: 235
url: /de/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() Methode

Stellt ErrorBars einer Serie mit Richtung Y dar.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## Bemerkungen

ErrorBars mit Y-Richtung sind für Serien vom Typ area, bar, line, scatter und bubble verfügbar. Für alle anderen Diagrammtypen gibt diese Eigenschaft null zurück (einschließlich 3D-Diagramme). Im Falle benutzerdefinierter Werte verwenden Sie die DataPoints-Sammlung, um den Wert anzugeben (mit [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)-Eigenschaft).

Nur lesbar [IErrorBarsFormat](../../ierrorbarsformat/).
## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IErrorBarsFormat](../../ierrorbarsformat/)
* Klasse [ChartSeries](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)