---
title: get_LayoutTargetType()
second_title: Aspose.Slides für C++ API Referenz
description: Wenn das Layout des Diagrammbereichs manuell definiert ist, gibt diese Eigenschaft an, ob der Diagrammbereich nach seinem Inneren (ohne Achsen und Achsenbeschriftungen) oder nach außen (mit Achsen und Achsenbeschriftungen) angeordnet werden soll. Lesen Sie LayoutTargetType.
type: docs
weight: 14
url: /de/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() Methode


Wenn das Layout des Diagrammbereichs manuell definiert ist, gibt diese Eigenschaft an, ob der Diagrammbereich nach seinem Inneren (nicht einschließlich Achsen und Achsenbeschriftungen) oder nach außen (einschließlich Achsen und Achsenbeschriftungen) angeordnet werden soll. Lesen Sie [LayoutTargetType](../../layouttargettype/).

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
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

* Aufzählung [LayoutTargetType](../../layouttargettype/)
* Klasse [IChartPlotArea](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Bibliothek [Aspose.Slides](../../../)