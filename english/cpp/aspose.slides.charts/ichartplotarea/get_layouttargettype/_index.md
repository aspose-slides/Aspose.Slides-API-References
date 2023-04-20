---
title: get_LayoutTargetType()
second_title: Aspose.Slides for C++ API Reference
description: If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Read LayoutTargetType.
type: docs
weight: 14
url: /cpp/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() method


If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Read [LayoutTargetType](../../layouttargettype/).

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
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
* Class [IChartPlotArea](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)