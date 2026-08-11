---
title: GetRange()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على نطاق بيانات المخطط.
type: docs
weight: 170
url: /ar/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() method

يحصل على نطاق بيانات المخطط.

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```

### قيمة الإرجاع

صيغة نطاق بيانات الخلايا. مثال: \"Sheet1!$A$1:$C$4\"
## ملاحظات

```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [IChartData](../)
* نطاق [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)