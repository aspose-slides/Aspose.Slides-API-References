---
title: get_LayoutTargetType()
second_title: Aspose.Slides for C++ API Referencia
description: Ha a diagramkörnyezet elrendezését manuálisan definiálják, ez a tulajdonság megadja, hogy a diagramkörnyetét a belseje (a tengelyek és tengelycímkék nélkül) vagy a külső része (a tengelyek és tengelycímkék beleértve) szerint kell-e elrendezni. Olvassa el LayoutTargetType.
type: docs
weight: 14
url: /hu/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() metódus


Ha a diagramkörnyezet elrendezését manuálisan definiálják, ez a tulajdonság megadja, hogy a diagramkörnyetét a belseje (a tengelyek és tengelycímkék nélkül) vagy a külső része (a tengelyek és tengelycímkék beleértve) szerint kell-e elrendezni. Olvasd el [LayoutTargetType](../../layouttargettype/).

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
```

## Megjegyzések



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

## Lásd még

* Enum [LayoutTargetType](../../layouttargettype/)
* Osztály [IChartPlotArea](../)
* Névtér [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)