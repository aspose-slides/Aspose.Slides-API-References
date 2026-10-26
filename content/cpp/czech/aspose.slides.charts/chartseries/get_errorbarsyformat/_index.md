---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje ErrorBars řady se směrem Y.
type: docs
weight: 235
url: /cs/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() metoda


Reprezentuje ErrorBars řady se směrem Y.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## Poznámky


ErrorBars se směrem Y jsou k dispozici pro řady typu area, bar, line, scatter a bubble. Pro jakýkoli jiný typ grafu tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints k určení hodnoty (s vlastností [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Pouze pro čtení [IErrorBarsFormat](../../ierrorbarsformat/). 
## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IErrorBarsFormat](../../ierrorbarsformat/)
* Třída [ChartSeries](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)