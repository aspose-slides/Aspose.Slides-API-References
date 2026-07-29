---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides för C++ API-referens
description: Representerar ErrorBars för serier med riktning Y.
type: docs
weight: 235
url: /sv/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() metod

Representerar ErrorBars för serier med riktning Y.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```
## Anmärkningar

ErrorBars med Y-riktning är tillgängliga för serier av typ area, bar, line, scatter och bubble. För alla andra typer av diagram returnerar denna egenskap null (inklusive 3D-diagram). Om du har anpassade värden, använd DataPoints-samlingen för att ange värdet (med [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)-egenskapen).

Skrivskyddad [IErrorBarsFormat](../../ierrorbarsformat/).
## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IErrorBarsFormat](../../ierrorbarsformat/)
* Klass [IChartSeries](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)