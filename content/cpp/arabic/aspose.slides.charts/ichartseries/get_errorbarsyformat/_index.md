---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides للغة C++ مرجع API
description: يمثل ErrorBars للسلسلة مع الاتجاه Y.
type: docs
weight: 235
url: /ar/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() طريقة


يمثل ErrorBars للسلسلة مع الاتجاه Y.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## ملاحظات


ErrorBars باتجاه Y متاح للسلسلات من النوع area و bar و line و scatter و bubble. بالنسبة لأي أنواع أخرى من المخطط تُعيد هذه الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (مع خاصية [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

للقراءة فقط [IErrorBarsFormat](../../ierrorbarsformat/). 
## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IErrorBarsFormat](../../ierrorbarsformat/)
* Class [IChartSeries](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)