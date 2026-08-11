---
title: get_ErrorBarsXFormat()
second_title: مرجع API Aspose.Slides برای C++
description: نمایش ErrorBars از سِری‌ها با جهت X.
type: docs
weight: 222
url: /fa/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() method

نمایش ErrorBars از سِری‌ها با جهت X.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## نکات

ErrorBars با جهت X برای سِری‌هایی از نوع area، bar، scatter و bubble در دسترس هستند. برای هر نوع دیگر نمودار، این خاصیت مقدار null را برمی‌گرداند (شامل نمودارهای 3D). در صورت نیاز به مقادیر سفارشی، از مجموعه DataPoints برای مشخص کردن مقدار استفاده کنید (با خاصیت [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

فقط خواندنی [IErrorBarsFormat](../../ierrorbarsformat/). 

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IErrorBarsFormat](../../ierrorbarsformat/)
* کلاس [ChartSeries](../)
* فضای نام [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)