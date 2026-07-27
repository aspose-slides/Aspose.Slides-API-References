---
title: set_LayoutTargetType()
second_title: Referencia de API de Aspose.Slides para C++
description: Si la disposición del área de trazado se define manualmente, esta propiedad especifica si se dispone el área de trazado por su interior (sin incluir ejes y etiquetas de ejes) o por su exterior (incluyendo ejes y etiquetas de ejes). Escriba LayoutTargetType.
type: docs
weight: 27
url: /es/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) método


Si la disposición del área de trazado se define manualmente, esta propiedad especifica si se dispone el área de trazado por su interior (sin incluir ejes y etiquetas de ejes) o por su exterior (incluyendo ejes y etiquetas de ejes). Escriba [LayoutTargetType](../../layouttargettype/).

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
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

## Véase también

* Enum [LayoutTargetType](../../layouttargettype/)
* Clase [IChartPlotArea](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)