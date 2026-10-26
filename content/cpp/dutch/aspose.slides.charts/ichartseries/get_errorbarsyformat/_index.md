---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt ErrorBars van series met richting Y voor.
type: docs
weight: 235
url: /nl/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() methode

Stelt ErrorBars van de serie met richting Y voor.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## Opmerkingen

ErrorBars met Y-richting zijn beschikbaar voor series van het type area, bar, line, scatter en bubble. Voor alle andere type grafieken geeft deze eigenschap null terug (inclusief 3D-grafieken). In het geval van aangepaste waarden gebruik je de DataPoints-collectie om de waarde op te geven (met [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) eigenschap).

Alleen-lezen [IErrorBarsFormat](../../ierrorbarsformat/). 
## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IErrorBarsFormat](../../ierrorbarsformat/)
* Klasse [IChartSeries](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)