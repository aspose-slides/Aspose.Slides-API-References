---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Představuje ErrorBars řady se směrem X.
type: docs
weight: 222
url: /cs/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() metoda


Představuje ErrorBars řady se směrem X.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## Poznámky


ErrorBars se směrem X jsou k dispozici pro řady typu area, bar, scatter a bubble. Pro všechny ostatní typy grafu tato vlastnost vrací null (včetně 3D grafů). V případě vlastních hodnot použijte kolekci DataPoints k určení hodnoty (s vlastností [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Pouze pro čtení [IErrorBarsFormat](../../ierrorbarsformat/). 
## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IErrorBarsFormat](../../ierrorbarsformat/)
* Třída [IChartSeries](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)