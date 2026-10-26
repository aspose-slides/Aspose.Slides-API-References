---
title: get_LayoutTargetType()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Pokud je rozložení kreslicí plochy definováno ručně, tato vlastnost určuje, zda rozložit kreslicí plochu podle jejího vnitřku (bez os a popisků os) nebo podle vnějšího okraje (včetně os a popisků os). Přečtěte si LayoutTargetType.
type: docs
weight: 170
url: /cs/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() metoda

Pokud je rozložení kreslicí plochy definováno ručně, tato vlastnost určuje, zda rozložit kreslicí plochu podle jejího vnitřku (bez os a popisků os) nebo podle vnějšího okraje (včetně os a popisků os). Přečtěte si [LayoutTargetType](../../layouttargettype/).

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
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