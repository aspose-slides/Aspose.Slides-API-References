---
title: set_LayoutTargetType()
second_title: Aspose.Slides för C++ API-referens
description: Om layouten för plotområdet definieras manuellt anger denna egenskap huruvida plotområdet ska layoutas enligt dess insida (utan att inkludera axel och axelrubriker) eller utsida (inkluderande axel och axelrubriker). Skriv LayoutTargetType.
type: docs
weight: 183
url: /sv/aspose.slides.charts/chartplotarea/set_layouttargettype/
---
## ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) metod


Om layouten för plotområdet definieras manuellt anger den här egenskapen huruvida plotområdet ska layoutas enligt dess innersida (utan att inkludera axel och axelrubriker) eller utsida (inkluderande axel och axelrubriker). Skriv [LayoutTargetType](../../layouttargettype/).

```cpp
void Aspose::Slides::Charts::ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value) override
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