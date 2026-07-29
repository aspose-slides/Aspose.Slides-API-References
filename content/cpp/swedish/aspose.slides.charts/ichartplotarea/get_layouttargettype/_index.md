---
title: get_LayoutTargetType()
second_title: Aspose.Slides för C++ API-referens
description: Om layouten för plotområdet definieras manuellt anger den här egenskapen om plotområdet ska layoutas inifrån (utan axlar och axelrubriker) eller utifrån (inklusive axlar och axelrubriker). Läs LayoutTargetType.
type: docs
weight: 14
url: /sv/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() metod


If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). Read [LayoutTargetType](../../layouttargettype/).

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
```

## Anmärkningar



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

## Se också

* Enum [LayoutTargetType](../../layouttargettype/)
* Klass [IChartPlotArea](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)