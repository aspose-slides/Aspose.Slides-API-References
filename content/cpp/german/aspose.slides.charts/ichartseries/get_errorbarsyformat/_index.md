---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt ErrorBars von Serien mit Richtung Y dar.
type: docs
weight: 235
url: /de/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() Methode

Stellt ErrorBars von Serien mit Richtung Y dar.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## Bemerkungen

ErrorBars mit Y-Richtung sind für Serien vom Typ area, bar, line, scatter und bubble verfügbar. Für alle anderen Diagrammtypen gibt diese Eigenschaft null zurück (einschließlich 3D-Diagramme). Im Falle benutzerdefinierter Werte verwenden Sie die DataPoints-Sammlung, um den Wert anzugeben (mit [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)-Eigenschaft).

Schreibgeschützt [IErrorBarsFormat](../../ierrorbarsformat/). 
## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IErrorBarsFormat](../../ierrorbarsformat/)
* Klasse [IChartSeries](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)