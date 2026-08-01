---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt ErrorBars van series met richting X voor.
type: docs
weight: 222
url: /nl/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() method


Stelt ErrorBars van een serie met richting X voor.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## Opmerkingen


ErrorBars met X-richting zijn beschikbaar voor series van het type area, bar, scatter en bubble. Voor andere soorten diagrammen geeft deze eigenschap null terug (inclusief 3D-diagrammen). In het geval van aangepaste waarden gebruik je de DataPoints-collectie om de waarde op te geven (met de [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) eigenschap). 

Alleen-lezen [IErrorBarsFormat](../../ierrorbarsformat/). 
## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IErrorBarsFormat](../../ierrorbarsformat/)
* Klasse [IChartSeries](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)