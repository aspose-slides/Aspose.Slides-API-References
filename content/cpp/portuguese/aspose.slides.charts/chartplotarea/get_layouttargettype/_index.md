---
title: get_LayoutTargetType()
second_title: Referência da API Aspose.Slides for C++
description: Se o layout da área do gráfico for definido manualmente, esta propriedade especifica se o layout da área do gráfico será interno (não incluindo eixos e rótulos dos eixos) ou externo (incluindo eixos e rótulos dos eixos). Leia LayoutTargetType.
type: docs
weight: 170
url: /pt/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() método


Se o layout da área do gráfico for definido manualmente, esta propriedade especifica se o layout da área do gráfico será feito por dentro (não incluindo eixos e rótulos dos eixos) ou por fora (incluindo eixos e rótulos dos eixos). Leia [LayoutTargetType](../../layouttargettype/).

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
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

## Ver Também

* Enum [LayoutTargetType](../../layouttargettype/)
* Classe [ChartPlotArea](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)