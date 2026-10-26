---
title: set_LayoutTargetType()
second_title: Aspose.Slides برای C++ مرجع API
description: اگر چیدمان ناحیهٔ نمودار به‌صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند که ناحیهٔ نمودار بر اساس داخل (بدون شامل محورها و برچسب‌های محورها) یا خارج (شامل محورها و برچسب‌های محورها) چیدمان شود. مقدار LayoutTargetType را بنویسید.
type: docs
weight: 27
url: /fa/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) method

اگر چیدمان ناحیه نمودار به‌صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند که ناحیه نمودار بر اساس داخل (بدون شامل محورها و برچسب‌های محورها) یا خارج (شامل محورها و برچسب‌های محورها) چیدمان شود. بنویسید [LayoutTargetType](../../layouttargettype/).

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
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

* Enum [LayoutTargetType](../../layouttargettype/)
* Class [IChartPlotArea](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)