---
title: get_LayoutTargetType()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn das Layout des Plot-Bereichs manuell definiert wird, gibt diese Eigenschaft an, ob der Plot-Bereich nach seinem Inneren (nicht einschließlich Achsen und Achsenbeschriftungen) oder nach seinem Äußeren (einschließlich Achsen und Achsenbeschriftungen) angeordnet wird. Lesen Sie LayoutTargetType.
type: docs
weight: 170
url: /de/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() Methode


Wenn das Layout des Plot-Bereichs manuell definiert wird, gibt diese Eigenschaft an, ob der Plot-Bereich nach dem Innenbereich (ohne Achsen und Achsenbeschriftungen) oder nach dem Außenbereich (mit Achsen und Achsenbeschriftungen) angeordnet wird. Lesen Sie [LayoutTargetType](../../layouttargettype/).

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
```

## Anmerkungen



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