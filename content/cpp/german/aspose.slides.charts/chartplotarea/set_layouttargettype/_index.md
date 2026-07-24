---
title: set_LayoutTargetType()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn das Layout des Plot-Bereichs manuell definiert ist, gibt diese Eigenschaft an, ob der Plot-Bereich anhand seines Inneren (ohne axis und axis labels) oder außerhalb (mit axis und axis labels) angeordnet wird. Schreiben Sie LayoutTargetType.
type: docs
weight: 183
url: /de/aspose.slides.charts/chartplotarea/set_layouttargettype/
---
## ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) Methode

Wenn das Layout des Plot-Bereichs manuell definiert ist, gibt diese Eigenschaft an, ob der Plot-Bereich anhand seines Inneren (nicht einschließlich axis und axis labels) oder außerhalb (einschließlich axis und axis labels) angeordnet wird. Schreiben Sie [LayoutTargetType](../../layouttargettype/).

```cpp
void Aspose::Slides::Charts::ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value) override
```

## Bemerkungen



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

## Siehe auch

* Enum [LayoutTargetType](../../layouttargettype/)
* Klasse [ChartPlotArea](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)