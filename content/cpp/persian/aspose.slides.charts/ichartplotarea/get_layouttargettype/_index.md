---
title: get_LayoutTargetType()
second_title: مرجع API Aspose.Slides برای C++
description: اگر طرح ناحیه نمودار به‌صورت دستی تعریف شود، این ویژگی مشخص می‌کند که آیا ناحیه نمودار براساس داخل آن (بدون شامل کردن محورها و برچسب‌های محورها) یا خارج آن (شامل محورها و برچسب‌های محورها) چینش شود. به LayoutTargetType مراجعه کنید.
type: docs
weight: 14
url: /fa/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() متد

اگر طرح ناحیه نمودار به‌صورت دستی تعریف شود، این ویژگی مشخص می‌کند که آیا ناحیه نمودار بر پایه داخل آن (بدون شامل کردن محورها و برچسب‌های محورها) یا خارج آن (شامل محورها و برچسب‌های محورها) چینش شود. مطالعه کنید [LayoutTargetType](../../layouttargettype/).

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
```

## ملاحظات

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

## موارد مرتبط

* enum [LayoutTargetType](../../layouttargettype/)
* کلاس [IChartPlotArea](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)