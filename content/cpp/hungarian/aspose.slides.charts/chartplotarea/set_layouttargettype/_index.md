---
title: set_LayoutTargetType()
second_title: Aspose.Slides C++ API-referencia
description: Ha a diagramterület elrendezése kézzel van definiálva, ez a tulajdonság meghatározza, hogy a diagramterületet a belseje (nem tartalmazza a tengelyt és a tengelycímkéket) vagy a külső része (tartalmazza a tengelyt és a tengelycímkéket) szerint rendezzük el. Írja be LayoutTargetType.
type: docs
weight: 183
url: /hu/aspose.slides.charts/chartplotarea/set_layouttargettype/
---
## ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) metódus


Ha a diagramterület elrendezése kézzel van definiálva, ez a tulajdonság azt határozza meg, hogy a diagramterületet a belseje (nem tartalmazza a tengelyt és a tengelycímkéket) vagy a külső része (tartalmazza a tengelyt és a tengelycímkéket) szerint rendezzük el. Írja be [LayoutTargetType](../../layouttargettype/).

```cpp
void Aspose::Slides::Charts::ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value) override
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
* Névtér [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)