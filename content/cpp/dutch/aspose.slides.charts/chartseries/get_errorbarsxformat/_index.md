---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de ErrorBars van series met richting X voor.
type: docs
weight: 222
url: /nl/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() methode

Representeert ErrorBars van serie met richting X.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## Opmerkingen

ErrorBars met X-richting zijn beschikbaar voor series van type area, bar, scatter en bubble. Voor alle andere typen grafiek retourneert deze eigenschap null (inclusief 3D-grafieken). Gebruik in geval van aangepaste waarden de DataPoints-collectie om de waarde op te geven (met [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) eigenschap).

Alleen-lezen [IErrorBarsFormat](../../ierrorbarsformat/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IErrorBarsFormat](../../ierrorbarsformat/)
* Klasse [ChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)