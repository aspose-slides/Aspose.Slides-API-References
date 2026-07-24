---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides für C++ API Referenz
description: Stellt ErrorBars von Serien mit Richtung X dar.
type: docs
weight: 222
url: /de/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() Methode

Stellt ErrorBars einer Serie mit Richtung X dar.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## Hinweise

ErrorBars mit X-Richtung sind für Serien vom Typ area, bar, scatter und bubble verfügbar. Für alle anderen Diagrammtypen gibt diese Eigenschaft null zurück (einschließlich 3D-Diagramme). Im Falle benutzerdefinierter Werte verwenden Sie die DataPoints-Sammlung, um den Wert anzugeben (mit [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) Eigenschaft).

Nur lesbar [IErrorBarsFormat](../../ierrorbarsformat/).
## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IErrorBarsFormat](../../ierrorbarsformat/)
* Klasse [IChartSeries](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)