---
title: get_LayoutTargetType()
second_title: Referencia de API de Aspose.Slides para C++
description: Si la disposición del área del gráfico se define manualmente, esta propiedad especifica si organizar el área del gráfico por su interior (sin incluir los ejes y las etiquetas de los ejes) o por su exterior (incluyendo los ejes y las etiquetas de los ejes). Lea LayoutTargetType.
type: docs
weight: 170
url: /es/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() método

Si la disposición del área del gráfico se define manualmente, esta propiedad especifica si organizar el área del gráfico por su interior (sin incluir los ejes y las etiquetas de los ejes) o por su exterior (incluyendo los ejes y las etiquetas de los ejes). Lea [LayoutTargetType](../../layouttargettype/).

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
```

## Observaciones


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

## Ver también

* Enum [LayoutTargetType](../../layouttargettype/)
* Clase [ChartPlotArea](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)