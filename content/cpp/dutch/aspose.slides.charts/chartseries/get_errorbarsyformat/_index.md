---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt ErrorBars van de reeks met richting Y voor.
type: docs
weight: 235
url: /nl/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() methode

Stelt ErrorBars van de reeks met richting Y voor.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## Opmerkingen

ErrorBars met Y-richting zijn beschikbaar voor reeksen van het type area, bar, line, scatter en bubble. Voor alle andere soorten diagram geeft deze eigenschap null terug (inclusief 3D-diagrammen). In het geval van aangepaste waarden gebruik de DataPoints-collectie om de waarde op te geven (met [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) eigenschap).

Alleen-lezen [IErrorBarsFormat](../../ierrorbarsformat/). 
## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IErrorBarsFormat](../../ierrorbarsformat/)
* Klasse [ChartSeries](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)