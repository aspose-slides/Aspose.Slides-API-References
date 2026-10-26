---
title: get_LayoutTargetType()
second_title: Riferimento API Aspose.Slides per C++
description: Se il layout dell'area del grafico è definito manualmente, questa proprietà specifica se disporre l'area del grafico internamente (escludendo gli assi e le etichette degli assi) o esternamente (includendo gli assi e le etichette degli assi). Leggi LayoutTargetType.
type: docs
weight: 170
url: /it/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() metodo

Se il layout dell'area del grafico è definito manualmente, questa proprietà specifica se disporre l'area del grafico internamente (escludendo gli assi e le etichette degli assi) o esternamente (includendo gli assi e le etichette degli assi). Leggi [LayoutTargetType](../../layouttargettype/).

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
```

## Osservazioni

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

## Vedi anche

* Enumerazione [LayoutTargetType](../../layouttargettype/)
* Classe [ChartPlotArea](../)
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)