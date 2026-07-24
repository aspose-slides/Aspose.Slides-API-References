---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides için C++ API Referansı
description: Serinin Y yönündeki ErrorBars'ı temsil eder.
type: docs
weight: 235
url: /tr/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() metot


Y yönündeki serinin ErrorBars'ını temsil eder.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## Açıklamalar


Y yönündeki ErrorBars, area, bar, line, scatter ve bubble türündeki seriler için kullanılabilir. Diğer tüm grafik türleri için bu özellik null döndürür (3D grafikler dahil). Özel değerler durumunda, değeri belirtmek için DataPoints koleksiyonunu kullanın ([IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) özelliği ile).

Yalnızca okunabilir [IErrorBarsFormat](../../ierrorbarsformat/). 
## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IErrorBarsFormat](../../ierrorbarsformat/)
* Sınıf [ChartSeries](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)