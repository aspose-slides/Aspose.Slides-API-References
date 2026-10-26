---
title: get_LayoutTargetType()
second_title: Aspose.Slides C++ API referencia
description: Ha az ábraterület elrendezése manuálisan van meghatározva, ez a tulajdonság azt határozza meg, hogy a területet a belseje (a tengelyek és tengelycímkék nélkül) vagy a külseje (a tengelyekkel és tengelycímkékkel együtt) szerint rendezze el. Olvassa el LayoutTargetType.
type: docs
weight: 170
url: /hu/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() metódus


Ha az ábraterület elrendezése manuálisan van meghatározva, ez a tulajdonság azt határozza meg, hogy a területet a belseje (a tengelyek és tengelycímkék nélkül) vagy a külseje (a tengelyekkel és tengelycímkékkel együtt) szerint rendezze el. Olvassa el [LayoutTargetType](../../layouttargettype/).

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
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
* Osztály [ChartPlotArea](../)
* Névterület [Aspose::Slides::Charts](../../)
* Könyvtár [Aspose.Slides](../../../)