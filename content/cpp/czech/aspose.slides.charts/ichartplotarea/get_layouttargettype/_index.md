---
title: get_LayoutTargetType()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Pokud je rozvržení oblasti diagramu definováno ručně, tato vlastnost určuje, zda rozvržení oblasti diagramu probíhá podle jejího vnitřku (neobsahuje osy a popisky os) nebo podle vnějšího okraje (obsahuje osy a popisky os). Přečtěte si LayoutTargetType.
type: docs
weight: 14
url: /cs/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() metoda

Pokud je rozvržení oblasti diagramu definováno ručně, tato vlastnost určuje, zda rozvržení oblasti diagramu se provádí podle jejího vnitřku (neobsahuje osy a popisky os) nebo podle vnějšího okraje (obsahuje osy a popisky os). Přečtěte si [LayoutTargetType](../../layouttargettype/).

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
```

## Poznámky

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

## Viz také

* Výčet [LayoutTargetType](../../layouttargettype/)
* Třída [IChartPlotArea](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)