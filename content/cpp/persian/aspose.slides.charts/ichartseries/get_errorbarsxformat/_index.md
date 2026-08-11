---
title: get_ErrorBarsXFormat()
second_title: مرجع API Aspose.Slides برای C++
description: نمایش ErrorBars سری با جهت X.
type: docs
weight: 222
url: /fa/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() متد


نمایش ErrorBars سری با جهت X.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## ملاحظات


ErrorBars با جهت X برای سری‌های از نوع area، bar، scatter و bubble قابل استفاده هستند. برای سایر انواع نمودار این ویژگی مقدار null برمی‌گرداند (از جمله نمودارهای 3D). در صورت استفاده از مقادیر سفارشی، از مجموعه DataPoints برای تعیین مقدار استفاده کنید (با ویژگی [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

فقط‌خواندنی [IErrorBarsFormat](../../ierrorbarsformat/). 
## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IErrorBarsFormat](../../ierrorbarsformat/)
* کلاس [IChartSeries](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)