---
title: get_LayoutTargetType()
second_title: Aspose.Slides voor C++ API-referentie
description: Als de lay-out van het plotgebied handmatig is gedefinieerd, geeft deze eigenschap aan of het plotgebied binnen (zonder assen en aslabels) of buiten (met assen en aslabels) moet worden geplaatst. Lees LayoutTargetType.
type: docs
weight: 14
url: /nl/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() methode


Als de lay-out van het plotgebied handmatig is gedefinieerd, geeft deze eigenschap aan of het plotgebied binnen (niet inclusief assen en as-labels) of buiten (inclusief assen en as-labels) moet worden geplaatst. Lees [LayoutTargetType](../../layouttargettype/).

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
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
* Klasse [IChartPlotArea](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)