---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides pro C++ API Reference
description: Představuje ErrorBars řady se směrem X.
type: docs
weight: 222
url: /cs/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() metoda

Představuje ErrorBars řady se směrem X.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## Poznámky

ErrorBars se směrem X jsou k dispozici pro řady typu area, bar, scatter a bubble. Pro jakýkoli jiný typ grafu tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints k určení hodnoty (s vlastností [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Pouze pro čtení [IErrorBarsFormat](../../ierrorbarsformat/). 
## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IErrorBarsFormat](../../ierrorbarsformat/)
* Třída [ChartSeries](../)
* Obor názvů [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)