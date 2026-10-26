---
title: GetRange()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يسترجع نطاق بيانات المخطط.
type: docs
weight: 157
url: /ar/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() طريقة

يحصل على نطاق بيانات المخطط.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```

### قيمة الإرجاع

صيغة نطاق بيانات الخلايا. على سبيل المثال: "Sheet1!$A$1:$C$4"
## ملاحظات

```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [ChartData](../)
* مساحة الاسم [Aspose::Slides::Charts](../../)
* المكتبة [Aspose.Slides](../../../)