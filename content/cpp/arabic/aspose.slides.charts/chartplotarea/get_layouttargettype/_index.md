---
title: get_LayoutTargetType()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إذا تم تعريف تخطيط مساحة الرسم يدويًا، تحدد هذه الخاصية ما إذا كان سيتم تخطيط مساحة الرسم من الداخل (دون تضمين المحاور وعناوين المحاور) أو من الخارج (مع تضمين المحاور وعناوين المحاور). اقرأ LayoutTargetType.
type: docs
weight: 170
url: /ar/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() طريقة

إذا تم تعريف تخطيط مساحة الرسم يدويًا، فإن هذه الخاصية تحدد ما إذا كان سيتم تخطيط مساحة الرسم من الداخل (بدون تضمين المحاور وعناوين المحاور) أو من الخارج (مع تضمين المحاور وعناوين المحاور). اقرأ [LayoutTargetType](../../layouttargettype/).

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
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

## انظر أيضا

* Enum [LayoutTargetType](../../layouttargettype/)
* فئة [ChartPlotArea](../)
* نطاق [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)