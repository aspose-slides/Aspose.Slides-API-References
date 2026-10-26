---
title: set_LayoutTargetType()
second_title: Aspose.Slides للغة C++ - مرجع API
description: إذا تم تعريف تخطيط منطقة الرسم يدويًا، تحدد هذه الخاصية ما إذا كان يجب تخطيط منطقة الرسم من الداخل (دون تضمين المحور وعناوين المحور) أو من الخارج (بما في ذلك المحور وعناوين المحور). اكتب LayoutTargetType.
type: docs
weight: 183
url: /ar/aspose.slides.charts/chartplotarea/set_layouttargettype/
---
## ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) طريقة

إذا تم تعريف تخطيط مساحة الرسم يدويًا فإن هذه الخاصية تحدد ما إذا كان يتم تخطيط مساحة الرسم من الداخل (دون تضمين المحور وعناوين المحور) أو من الخارج (بما في ذلك المحور وعناوين المحور). اكتب [LayoutTargetType](../../layouttargettype/).

```cpp
void Aspose::Slides::Charts::ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value) override
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
* فئة [ChartPlotArea](../)
* حيز الاسم [Aspose::Slides::Charts](../../)
* مكتبة [Aspose.Slides](../../../)