---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides for C++ API Referansı
description: Serinin Y yönündeki ErrorBars öğesini temsil eder.
type: docs
weight: 235
url: /tr/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() metod

Y yönündeki serinin ErrorBars öğesini temsil eder.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## Açıklamalar

Y yönündeki ErrorBars, area, bar, line, scatter ve bubble tipindeki seriler için kullanılabilir. Diğer tüm grafik tipleri için bu özellik null döner (3D grafikler dahil). Özel değerler durumunda, değeri belirtmek için DataPoints koleksiyonunu kullanın ([IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) özelliği ile).

Salt okunur [IErrorBarsFormat](../../ierrorbarsformat/).

## Diğer Bağlantılar

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IErrorBarsFormat](../../ierrorbarsformat/)
* Sınıf [IChartSeries](../)
* Ad alanı [Aspose::Slides::Charts](../../)
* Kütüphane [Aspose.Slides](../../../)