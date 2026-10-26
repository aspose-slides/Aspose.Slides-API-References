---
title: get_Format()
second_title: Aspose.Slides برای مرجع API C++
description: نمایانگر خصوصیات قالب‌بندی سطح نقطه داده است. خواندن IFormat.
type: docs
weight: 1
url: /fa/aspose.slides.charts/ichartdatapointlevel/get_format/
---
## IChartDataPointLevel::get_Format() متد


خواص قالب‌بندی سطح نقطه داده را نشان می‌دهد. بخوانید [IFormat](../../iformat/).

```cpp
virtual System::SharedPtr<IFormat> Aspose::Slides::Charts::IChartDataPointLevel::get_Format()=0
```

## توضیحات






```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Treemap, 50.0f, 50.0f, 500.0f, 400.0f);
auto series = chart->get_ChartData()->get_Series()->idx_get(0);

auto dataPointLevel = series->get_DataPoints()->idx_get(7)->get_DataPointLevels()->idx_get(2);
dataPointLevel->get_Format()->get_Fill()->set_FillType(FillType::Solid);
dataPointLevel->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(Color::get_Red());
```

## مراجع دیگر

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IFormat](../../iformat/)
* کلاس [IChartDataPointLevel](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)