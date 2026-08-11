---
title: get_ErrorBarsYFormat()
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر ErrorBars سری با جهت Y است.
type: docs
weight: 235
url: /fa/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() method

نمایانگر ErrorBars سری با جهت Y است.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```
## توضیحات

ErrorBars با جهت Y برای سری‌های از نوع area, bar, line, scatter و bubble در دسترس هستند. برای هر نوع دیگر نمودار این ویژگی مقدار null برمی‌گرداند (از جمله نمودارهای 3D). در صورت استفاده از مقادیر سفارشی، از مجموعه DataPoints برای تعیین مقدار استفاده کنید (با ویژگی [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

فقط‌خواندنی [IErrorBarsFormat](../../ierrorbarsformat/).
## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IErrorBarsFormat](../../ierrorbarsformat/)
* کلاس [IChartSeries](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)