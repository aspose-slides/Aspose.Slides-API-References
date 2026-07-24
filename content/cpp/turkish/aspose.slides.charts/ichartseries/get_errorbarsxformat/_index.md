---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides C++ API Referansı
description: Serinin X yönündeki ErrorBars'ını temsil eder.
type: docs
weight: 222
url: /tr/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() method

X yönündeki serinin ErrorBars'ını temsil eder.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## Açıklamalar

X yönündeki ErrorBars, area, bar, scatter ve bubble tipindeki seriler için kullanılabilir. Diğer tüm grafik türleri için bu özellik null döndürür (3D grafikler dahil). Özel değerler durumunda, değeri belirtmek için DataPoints koleksiyonunu kullanın ([IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) özelliği ile).

Yalnızca okunur [IErrorBarsFormat](../../ierrorbarsformat/). 
## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IErrorBarsFormat](../../ierrorbarsformat/)
* Sınıf [IChartSeries](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)