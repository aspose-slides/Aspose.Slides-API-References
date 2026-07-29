---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides för C++ API-referens
description: Representerar ErrorBars för serier med riktning X.
type: docs
weight: 222
url: /sv/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() metod


Representerar ErrorBars för en serie med riktning X.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## Anmärkningar


ErrorBars med X-riktning är tillgängliga för serier av typen area, bar, scatter och bubble. För alla andra diagramtyper returnerar denna egenskap null (inklusive 3D-diagram). Vid anpassade värden använd DataPoints-samlingen för att ange värdet (med [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) egenskap). 

Skrivskyddad [IErrorBarsFormat](../../ierrorbarsformat/). 
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IErrorBarsFormat](../../ierrorbarsformat/)
* Klass [IChartSeries](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)