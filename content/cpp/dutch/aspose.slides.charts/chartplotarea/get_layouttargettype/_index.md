---
title: get_LayoutTargetType()
second_title: Aspose.Slides voor C++ API-referentie
description: Als de lay-out van het plotgebied handmatig is gedefinieerd, specificeert deze eigenschap of het plotgebied moet worden gelayout door de binnenkant (exclusief as en aslabels) of de buitenkant (inclusief as en aslabels). Lees LayoutTargetType.
type: docs
weight: 170
url: /nl/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() methode


Als de lay-out van het plotgebied handmatig is gedefinieerd, specificeert deze eigenschap of het plotgebied moet worden gelayout door zijn binnenkant (exclusief as en aslabels) of buitenkant (inclusief as en aslabels). Lees [LayoutTargetType](../../layouttargettype/).

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
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
* Klasse [ChartPlotArea](../)
* Namespace [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)