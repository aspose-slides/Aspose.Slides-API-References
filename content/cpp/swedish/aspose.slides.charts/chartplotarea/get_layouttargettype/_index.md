---
title: get_LayoutTargetType()
second_title: Aspose.Slides för C++ API-referens
description: Om diagramområdets layout definierats manuellt anger den här egenskapen om diagramområdet ska läggas upp efter insidan (utan axlar och axelrubriker) eller utsidan (med axlar och axelrubriker). Läs LayoutTargetType.
type: docs
weight: 170
url: /sv/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() metod


Om layouten för diagramområdet definierats manuellt anger den här egenskapen om diagramområdet ska läggas upp efter insidan (exklusive axlar och axelrubriker) eller utsidan (inklusive axlar och axelrubriker). Läs [LayoutTargetType](../../layouttargettype/).

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
```

## Anmärkningar



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

## Se även

* Enum [LayoutTargetType](../../layouttargettype/)
* Klass [ChartPlotArea](../)
* Namnrymd [Aspose::Slides::Charts](../../)
* Bibliotek [Aspose.Slides](../../../)