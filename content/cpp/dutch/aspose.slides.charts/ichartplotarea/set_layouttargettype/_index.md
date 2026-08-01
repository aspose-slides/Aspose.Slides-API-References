---
title: set_LayoutTargetType()
second_title: Aspose.Slides voor C++ API-referentie
description: Als de layout van het plotgebied handmatig is gedefinieerd, geeft deze eigenschap aan of het plotgebied moet worden gelayout op basis van het binnenste (niet inclusief assen en aslabels) of aan de buitenkant (inclusief assen en aslabels). Schrijf LayoutTargetType.
type: docs
weight: 27
url: /nl/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) methode


Als de lay-out van het plotgebied handmatig is gedefinieerd, geeft deze eigenschap aan of het plotgebied moet worden gelayout op basis van het binnenste (niet inclusief assen en aslabels) of aan de buitenkant (inclusief assen en aslabels). Schrijf [LayoutTargetType](../../layouttargettype/).

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
```

## Opmerkingen



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

## Zie ook

* Enum [LayoutTargetType](../../layouttargettype/)
* Class [IChartPlotArea](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)