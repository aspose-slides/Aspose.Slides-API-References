---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides için C++ API Referansı
description: X yönündeki serinin ErrorBars'ını temsil eder.
type: docs
weight: 222
url: /tr/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() metodu

X yönündeki serinin ErrorBars'ını temsil eder.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```
## Açıklamalar

X yönündeki ErrorBars, area, bar, scatter ve bubble türündeki seriler için kullanılabilir. Diğer tüm grafik türleri için bu özellik null döndürür (3D grafikler dahil). Özel değerler durumunda, değeri belirtmek için DataPoints koleksiyonunu kullanın ([IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) özelliği ile).

Yalnızca okuma [IErrorBarsFormat](../../ierrorbarsformat/).
## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IErrorBarsFormat](../../ierrorbarsformat/)
* Sınıf [ChartSeries](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)