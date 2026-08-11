---
title: get_LayoutTargetType()
second_title: Aspose.Slides برای C++ مرجع API
description: اگر چیدمان ناحیه نمودار به صورت دستی تعریف شده باشد، این ویژگی تعیین می‌کند که ناحیه نمودار از داخل (بدون شامل محور و برچسب‌های محور) یا از بیرون (شامل محور و برچسب‌های محور) چیدمان شود. خواندن LayoutTargetType.
type: docs
weight: 170
url: /fa/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() متد


اگر چیدمان ناحیه نمودار به صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند که ناحیه نمودار از داخل (بدون شامل محور و برچسب‌های محور) یا از بیرون (شامل محور و برچسب‌های محور) چیدمان شود. خوانید [LayoutTargetType](../../layouttargettype/).

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
```

## توضیحات



```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 20.0f, 100.0f, 600.0f, 400.0f);

chart->get_PlotArea()->set_X(0.2f);
chart->get_PlotArea()->set_Y(0.2f);
chart->get_PlotArea()->set_Width(0.7f);
chart->get_PlotArea()->set_Height(0.7f);

chart->get_PlotArea()->set_LayoutTargetType(LayoutTargetType::Inner);
// ...
```

## مراجع

* شمارش [LayoutTargetType](../../layouttargettype/)
* کلاس [ChartPlotArea](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)