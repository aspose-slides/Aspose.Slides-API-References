---
title: get_LayoutTargetType()
second_title: Référence de l'API Aspose.Slides pour C++
description: Si la disposition de la zone de tracé est définie manuellement, cette propriété indique s'il faut disposer la zone de tracé à l'intérieur (excluant les axes et les libellés d'axes) ou à l'extérieur (incluant les axes et les libellés d'axes). Lire LayoutTargetType.
type: docs
weight: 14
url: /fr/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() méthode

Si la disposition de la zone de tracé est définie manuellement, cette propriété indique s'il faut disposer la zone de tracé à l'intérieur (excluant les axes et les libellés des axes) ou à l'extérieur (incluant les axes et les libellés des axes). Lire [LayoutTargetType](../../layouttargettype/).

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
```

## Remarques

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

## Voir aussi

* Enum [LayoutTargetType](../../layouttargettype/)
* Classe [IChartPlotArea](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)