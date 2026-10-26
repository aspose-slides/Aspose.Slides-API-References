---
title: set_LayoutTargetType()
second_title: مرجع API Aspose.Slides برای C++
description: اگر چیدمان ناحیهٔ نمودار به صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند که ناحیهٔ نمودار بر اساس داخل (بدون شامل محورها و برچسب‌های محور) یا خارج (شامل محورها و برچسب‌های محور) چیدمان شود. مقدار LayoutTargetType را بنویسید.
type: docs
weight: 183
url: /fa/aspose.slides.charts/chartplotarea/set_layouttargettype/
---
## ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) متد


اگر چیدمان ناحیهٔ نمودار به صورت دستی تعریف شود، این ویژگی مشخص می‌کند که ناحیهٔ نمودار براساس داخل (بدون شامل محورها و برچسب‌های محور) یا خارج (شامل محورها و برچسب‌های محور) چیدمان شود. بنویسید [LayoutTargetType](../../layouttargettype/).

```cpp
void Aspose::Slides::Charts::ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value) override
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

## موارد مرتبط

* شمارش [LayoutTargetType](../../layouttargettype/)
* کلاس [ChartPlotArea](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)