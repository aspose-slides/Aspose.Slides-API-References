---
title: set_LayoutTargetType()
second_title: Riferimento API Aspose.Slides per C++
description: Se il layout dell'area del grafico è definito manualmente, questa proprietà specifica se posizionare l'area del grafico all'interno (non includendo assi ed etichette degli assi) o all'esterno (includendo assi ed etichette degli assi). Scrivi LayoutTargetType.
type: docs
weight: 27
url: /it/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) method

Se il layout dell'area del grafico è definito manualmente, questa proprietà specifica se posizionare l'area del grafico all'interno (non includendo assi ed etichette degli assi) o all'esterno (includendo assi ed etichette degli assi). Scrivi [LayoutTargetType](../../layouttargettype/).

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
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
* Spazio dei nomi [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)