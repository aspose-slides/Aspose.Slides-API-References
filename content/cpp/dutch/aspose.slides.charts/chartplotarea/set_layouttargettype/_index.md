---
title: set_LayoutTargetType()
second_title: Aspose.Slides voor C++ API-referentie
description: Als de lay-out van het plotgebied handmatig wordt gedefinieerd, geeft deze eigenschap aan of het plotgebied moet worden uitgelijnd op basis van de binnenkant (zonder assen en aslabels) of de buitenkant (met assen en aslabels). Schrijf LayoutTargetType.
type: docs
weight: 183
url: /nl/aspose.slides.charts/chartplotarea/set_layouttargettype/
---
## ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) method


Als de lay-out van het plotgebied handmatig wordt gedefinieerd, geeft deze eigenschap aan of het plotgebied moet worden uitgelijnd door zijn binnenkant (zonder assen en aslabels) of buitenkant (met assen en aslabels). Write [LayoutTargetType](../../layouttargettype/).

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