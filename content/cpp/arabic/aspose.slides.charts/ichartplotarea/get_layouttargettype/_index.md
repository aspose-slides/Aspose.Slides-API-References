---
title: get_LayoutTargetType()
second_title: مرجع API ل Aspose.Slides للغة C++
description: إذا تم تعريف تخطيط منطقة الرسم يدويًا، تحدد هذه الخاصية ما إذا كان سيتم تخطيط منطقة الرسم من الداخل (بدون تضمين المحاور وتسميات المحاور) أو من الخارج (مع تضمين المحAxes وتسميات المحAxes). اقرأ LayoutTargetType.
type: docs
weight: 14
url: /ar/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() طريقة


إذا تم تعريف تخطيط منطقة الرسم يدويًا، فإن هذه الخاصية تحدد ما إذا كان سيتم تخطيط منطقة الرسم من الداخل (بدون تضمين المحاور وتسميات المحاور) أو من الخارج (مع تضمين المحاور وتسميات المحاور). اقرأ [LayoutTargetType](../../layouttargettype/).

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

## انظر أيضًا

* تعداد [LayoutTargetType](../../layouttargettype/)
* فئة [IChartPlotArea](../)
* النطاق [Aspose::Slides::Charts](../../)
* المكتبة [Aspose.Slides](../../../)