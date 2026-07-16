---
title: set_LayoutTargetType()
second_title: Référence API Aspose.Slides pour C++
description: Si la mise en page de la zone de tracé est définie manuellement, cette propriété indique s'il faut disposer la zone de tracé par son intérieur (sans inclure les axes et les étiquettes d'axes) ou par son extérieur (en incluant les axes et les étiquettes d'axes). Écrivez LayoutTargetType.
type: docs
weight: 27
url: /fr/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) méthode


Si la mise en page de la zone de tracé est définie manuellement, cette propriété indique s'il faut disposer la zone de tracé par son intérieur (sans inclure les axes et les étiquettes d'axes) ou par son extérieur (en incluant les axes et les étiquettes d'axes). Écrivez [LayoutTargetType](../../layouttargettype/).

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
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