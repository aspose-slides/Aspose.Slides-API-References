---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides لـ C++ مرجع API
description: يمثل ErrorBars للسلسلة باتجاه X.
type: docs
weight: 222
url: /ar/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() طريقة

يمثل ErrorBars للسلسلة باتجاه X.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## ملاحظات

ErrorBars باتجاه X متاحة للسلسلة من النوع area أو bar أو scatter أو bubble. بالنسبة لأي أنواع أخرى من المخطط، تُعيد هذه الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حالة القيم المخصصة، استخدم مجموعة DataPoints لتحديد القيمة (مع الخاصية [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

قراءة فقط [IErrorBarsFormat](../../ierrorbarsformat/).

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IErrorBarsFormat](../../ierrorbarsformat/)
* فئة [ChartSeries](../)
* مساحة الاسم [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)