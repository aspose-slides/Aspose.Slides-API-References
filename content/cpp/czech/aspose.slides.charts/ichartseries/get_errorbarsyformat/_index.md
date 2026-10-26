---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Representuje ErrorBars řady se směrem Y.
type: docs
weight: 235
url: /cs/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() metoda

Representuje ErrorBars řady se směrem Y.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## Poznámky

ErrorBars se směrem Y jsou dostupné pro řady typu area, bar, line, scatter a bubble. Pro jakýkoli jiný typ grafu tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints k určení hodnoty (s vlastností [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Pouze ke čtení [IErrorBarsFormat](../../ierrorbarsformat/). 
## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IErrorBarsFormat](../../ierrorbarsformat/)
* Třída [IChartSeries](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)