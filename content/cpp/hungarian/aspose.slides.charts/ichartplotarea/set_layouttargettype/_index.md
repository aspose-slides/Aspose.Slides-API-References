---
title: set_LayoutTargetType()
second_title: Aspose.Slides C++ API referencia
description: Ha a diagramterület elrendezése manuálisan van meghatározva, ez a tulajdonság meghatározza, hogy a diagramterületet a belseje (a tengelyek és a tengelycímkék nélkül) vagy a külseje (a tengelyekkel és a tengelycímkékkel együtt) alapján kell-e elrendezni. Írja be LayoutTargetType.
type: docs
weight: 27
url: /hu/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) metódus

Ha a diagramterület elrendezése manuálisan van meghatározva, ez a tulajdonság azt határozza meg, hogy a diagramterületet a belseje (a tengelyek és tengelycímkék nélkül) vagy a külseje (a tengelyekkel és tengelycímkékkel együtt) alapján kell-e elrendezni. Írja be [LayoutTargetType](../../layouttargettype/).

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
```

## Megjegyzés

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
* Könyvtár [Aspose.Slides](../../../)