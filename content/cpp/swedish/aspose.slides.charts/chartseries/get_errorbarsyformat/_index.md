---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides för C++ API-referens
description: Representerar ErrorBars för serier med riktning Y.
type: docs
weight: 235
url: /sv/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() metod

Representerar ErrorBars för serien med riktning Y.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## Anmärkningar

ErrorBars med Y-riktning är tillgängliga för serier av typen area, bar, line, scatter och bubble. För alla andra diagramtyper returnerar denna egenskap null (inklusive 3D-diagram). Vid anpassade värden använd DataPoints-samlingen för att ange värdet (med [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)-egenskapen).

Skrivskyddad [IErrorBarsFormat](../../ierrorbarsformat/). 
## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IErrorBarsFormat](../../ierrorbarsformat/)
* Klass [ChartSeries](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)