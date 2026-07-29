---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides för C++ API-referens
description: Representerar ErrorBars för serier med riktning X.
type: docs
weight: 222
url: /sv/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() metod

Representerar ErrorBars för serier med riktning X.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## Anmärkningar

ErrorBars med X-riktning är tillgängliga för serier av typen area, bar, scatter och bubble. För alla andra diagramtyper returnerar denna egenskap null (inklusive 3D-diagram). Vid anpassade värden, använd DataPoints-samlingen för att ange värdet (med [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)-egenskapen).

Endast läsning [IErrorBarsFormat](../../ierrorbarsformat/). 
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IErrorBarsFormat](../../ierrorbarsformat/)
* Klass [ChartSeries](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)