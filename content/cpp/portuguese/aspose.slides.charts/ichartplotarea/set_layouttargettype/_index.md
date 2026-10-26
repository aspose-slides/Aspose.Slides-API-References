---
title: set_LayoutTargetType()
second_title: Referência da API Aspose.Slides para C++
description: Se o layout da área de plotagem for definido manualmente, esta propriedade especifica se o layout da área de plotagem deve ser feito pelo seu interior (não incluindo eixos e rótulos dos eixos) ou exterior (incluindo eixos e rótulos dos eixos). Escreva LayoutTargetType.
type: docs
weight: 27
url: /pt/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) método

Se o layout da área de plotagem for definido manualmente, esta propriedade especifica se o layout da área de plotagem deve ser pelo seu interior (não incluindo eixos e rótulos dos eixos) ou exterior (incluindo eixos e rótulos dos eixos). Write [LayoutTargetType](../../layouttargettype/).

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
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

## Ver também

* Enum [LayoutTargetType](../../layouttargettype/)
* Classe [IChartPlotArea](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)