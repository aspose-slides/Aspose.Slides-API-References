---
title: GetRange()
second_title: Aspose.Slides برای مرجع API C++
description: محدوده داده‌های نمودار را دریافت می‌کند.
type: docs
weight: 157
url: /fa/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() متد


محدوده داده‌های نمودار را دریافت می‌کند.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### مقدار بازگشت

فرمول محدوده داده‌های سلول‌ها. به عنوان مثال: "Sheet1!$A$1:$C$4"
## توضیحات




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [ChartData](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)