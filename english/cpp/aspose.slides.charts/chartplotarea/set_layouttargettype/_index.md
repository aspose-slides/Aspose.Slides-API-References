---
title: set_LayoutTargetType()
second_title: Aspose.Slides for C++ API Reference
description: If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Write LayoutTargetType.
type: docs
weight: 183
url: /cpp/aspose.slides.charts/chartplotarea/set_layouttargettype/
---
## ChartPlotArea::set_LayoutTargetType([Aspose::Slides::Charts::LayoutTargetType](../../layouttargettype/)) method


If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Write [LayoutTargetType](../../layouttargettype/).

```cpp
void Aspose::Slides::Charts::ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value) override
```

## Remarks



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

## See Also

* Enum [LayoutTargetType](../../layouttargettype/)
* Class [ChartPlotArea](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
