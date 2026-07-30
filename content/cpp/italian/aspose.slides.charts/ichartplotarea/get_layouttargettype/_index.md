---
title: get_LayoutTargetType()
second_title: Riferimento API di Aspose.Slides per C++
description: Se il layout dell'area del grafico è definito manualmente, questa proprietà specifica se posizionare l'area del grafico al suo interno (escludendo gli assi e le etichette degli assi) o all'esterno (includendo gli assi e le etichette degli assi). Leggi LayoutTargetType.
type: docs
weight: 14
url: /it/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() metodo

Se il layout dell'area del grafico è definito manualmente, questa proprietà specifica se posizionare l'area del grafico al suo interno (escludendo gli assi e le etichette degli assi) o all'esterno (includendo gli assi e le etichette degli assi). Leggi [LayoutTargetType](../../layouttargettype/).

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
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

* Enum [LayoutTargetType](../../layouttargettype/)
* Classe [IChartPlotArea](../)
* Namespace [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)