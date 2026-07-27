---
title: get_LayoutTargetType()
second_title: Referência da API Aspose.Slides para C++
description: Se o layout da área de plotagem for definido manualmente, esta propriedade especifica se o layout da área de plotagem deve ser feito por dentro (não incluindo eixo e rótulos dos eixos) ou por fora (incluindo eixo e rótulos dos eixos). Leia LayoutTargetType.
type: docs
weight: 14
url: /pt/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() método

Se o layout da área de plotagem for definido manualmente, esta propriedade especifica se o layout da área de plotagem deve ser feito por dentro (não incluindo eixo e rótulos dos eixos) ou por fora (incluindo eixo e rótulos dos eixos). Leia [LayoutTargetType](../../layouttargettype/).

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
```

## Observações

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

## Veja Também

* Enumeração [LayoutTargetType](../../layouttargettype/)
* Classe [IChartPlotArea](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)