---
title: get_ErrorBarsXFormat()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يمثل ErrorBars للمتسلسلة مع الاتجاه X.
type: docs
weight: 222
url: /ar/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() طريقة

يمثل ErrorBars للمتسلسلة مع الاتجاه X.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## ملاحظات

ErrorBars مع اتجاه X متاحة للسلسلة من النوع area، bar، scatter و bubble. بالنسبة لأي أنواع أخرى من المخطط تُعيد هذه الخاصية null (بما في ذلك المخططات 3D). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (مع الخاصية [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

قراءة فقط [IErrorBarsFormat](../../ierrorbarsformat/).

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IErrorBarsFormat](../../ierrorbarsformat/)
* فئة [IChartSeries](../)
* نطاق [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)