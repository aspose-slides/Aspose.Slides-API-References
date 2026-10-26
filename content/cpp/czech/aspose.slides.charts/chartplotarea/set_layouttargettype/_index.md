---
title: set_LayoutTargetType()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Pokud je rozložení oblasti grafu definováno ručně, tato vlastnost určuje, zda rozvrhnout oblast grafu podle jejího vnitřku (ne včetně os a popisků os) nebo vně (včetně os a popisků os). Zapište LayoutTargetType.
type: docs
weight: 183
url: /cs/aspose.slides.charts/chartplotarea/set_layouttargettype/
---
## ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) metoda


Pokud je rozložení grafické oblasti definováno ručně, tato vlastnost určuje, zda rozvrhnout oblast grafu podle jejího vnitřku (bez os a popisků os) nebo vně (s osami a popisky os). Zapište [LayoutTargetType](../../layouttargettype/).

```cpp
void Aspose::Slides::Charts::ChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value) override
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
* Třída [ChartPlotArea](../)
* Jmenný prostor [Aspose::Slides::Charts](../../)
* Knihovna [Aspose.Slides](../../../)