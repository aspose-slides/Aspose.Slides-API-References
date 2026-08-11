---
title: get_ErrorBarsYFormat()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يمثل ErrorBars للسلسلة مع الاتجاه Y.
type: docs
weight: 235
url: /ar/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() طريقة


يمثل ErrorBars لسلسلة مع الاتجاه Y.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## ملاحظات


ErrorBars مع الاتجاه Y متاحة للسلسلة من النوع area, bar, line, scatter و bubble. لأي أنواع أخرى من المخطط تُرجع هذه الخاصية null (بما في ذلك مخططات 3D). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (مع الخاصية [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

للقراءة فقط [IErrorBarsFormat](../../ierrorbarsformat/). 
## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IErrorBarsFormat](../../ierrorbarsformat/)
* فئة [ChartSeries](../)
* مساحة الاسم [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)