---
title: set_LayoutTargetType()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إذا تم تعريف تخطيط منطقة الرسم يدويًا، تحدد هذه الخاصية ما إذا كان يتم تخطيط منطقة الرسم من الداخل (بدون المحاور وعناوين المحاور) أو من الخارج (مع المحاور وعناوين المحاور). اكتب LayoutTargetType.
type: docs
weight: 27
url: /ar/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) طريقة


إذا تم تعريف تخطيط منطقة الرسم يدويًا، فإن هذه الخاصية تحدد ما إذا كان سيتم تخطيط منطقة الرسم من الداخل (بدون المحاور وعناوين المحاور) أو من الخارج (مع المحاور وعناوين المحاور). اكتب [LayoutTargetType](../../layouttargettype/).

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
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

* Enum [LayoutTargetType](../../layouttargettype/)
* فئة [IChartPlotArea](../)
* مساحة الاسم [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)