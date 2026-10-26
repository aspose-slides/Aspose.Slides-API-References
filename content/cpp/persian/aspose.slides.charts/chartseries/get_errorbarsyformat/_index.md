---
title: get_ErrorBarsYFormat()
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر ErrorBars سری با جهت Y است.
type: docs
weight: 235
url: /fa/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() متد

نمایانگر ErrorBars سری با جهت Y است.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## توضیحات

ErrorBars با جهت Y برای سری‌های از نوع area, bar, line, scatter و bubble در دسترس هستند. برای هر نوع دیگر نمودار این ویژگی null باز می‌گرداند (از جمله نمودارهای 3D). در صورت استفاده از مقادیر سفارشی از مجموعه DataPoints برای تعیین مقدار استفاده کنید (با ویژگی [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

فقط-خواندنی [IErrorBarsFormat](../../ierrorbarsformat/). 

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IErrorBarsFormat](../../ierrorbarsformat/)
* کلاس [ChartSeries](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)