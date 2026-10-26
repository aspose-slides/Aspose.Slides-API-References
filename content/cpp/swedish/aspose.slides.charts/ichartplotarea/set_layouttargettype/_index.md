---
title: set_LayoutTargetType()
second_title: Aspose.Slides för C++ API-referens
description: Om layouten för plotområdet definieras manuellt anger denna egenskap om plotområdet ska läggas ut enligt dess insida (utan axlar och axelrubriker) eller utsida (med axlar och axelrubriker). Skriv LayoutTargetType.
type: docs
weight: 27
url: /sv/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) metod


Om layouten för plotområdet definieras manuellt anger denna egenskap om plotområdet ska läggas ut enligt dess insida (utan axlar och axelrubriker) eller utsida (med axlar och axelrubriker). Skriv [LayoutTargetType](../../layouttargettype/).

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
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

## Se även

* Enum [LayoutTargetType](../../layouttargettype/)
* Klass [IChartPlotArea](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)