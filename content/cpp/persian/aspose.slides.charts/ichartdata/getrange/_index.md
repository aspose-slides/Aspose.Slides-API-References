---
title: GetRange()
second_title: Aspose.Slides برای مرجع API C++
description: محدوده داده‌های نمودار را دریافت می‌کند.
type: docs
weight: 170
url: /fa/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() متد

محدوده داده‌های نمودار را دریافت می‌کند.

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```

### مقدار بازگشت

فرمول محدوده دادهٔ سلول‌ها. به عنوان مثال: "Sheet1!$A$1:$C$4"

## توضیحات

```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## همچنین ببینید

* کلاس [String](../../../system/string/)
* کلاس [IChartData](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)