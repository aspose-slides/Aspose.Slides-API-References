---
title: set_LayoutTargetType()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn das Layout des Plot-Bereichs manuell definiert ist, gibt diese Eigenschaft an, ob der Plot-Bereich innerhalb (nicht einschließlich Achsen und Achsenbeschriftungen) oder außerhalb (einschließlich Achsen und Achsenbeschriftungen) angeordnet werden soll. Schreiben Sie LayoutTargetType.
type: docs
weight: 27
url: /de/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) Methode


Wenn das Layout des Plot-Bereichs manuell definiert ist, gibt diese Eigenschaft an, ob der Plot-Bereich innerhalb (ohne Achsen und Achsenbeschriftungen) oder außerhalb (mit Achsen und Achsenbeschriftungen) angeordnet werden soll. Schreiben Sie [LayoutTargetType](../../layouttargettype/).

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
```

## Hinweise



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
* Klasse [IChartPlotArea](../)
* Namensraum [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)