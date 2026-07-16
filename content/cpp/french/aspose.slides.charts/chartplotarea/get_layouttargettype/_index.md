---
title: get_LayoutTargetType()
second_title: Référence de l'API Aspose.Slides pour C++
description: Si la disposition de la zone de tracé est définie manuellement, cette propriété indique s'il faut disposer la zone de tracé par son intérieur (sans inclure les axes et les libellés d'axe) ou par son extérieur (en incluant les axes et les libellés d'axe). Lire LayoutTargetType.
type: docs
weight: 170
url: /fr/aspose.slides.charts/chartplotarea/get_layouttargettype/
---
## ChartPlotArea::get_LayoutTargetType() méthode


Si la disposition de la zone de tracé est définie manuellement, cette propriété indique s'il faut disposer la zone de tracé par son intérieur (sans inclure les axes et les etiquettes d'axe) ou par son extérieur (en incluant les axes et les etiquettes d'axe). Lire [LayoutTargetType](../../layouttargettype/).

```cpp
Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::ChartPlotArea::get_LayoutTargetType() override
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

* Énumération [LayoutTargetType](../../layouttargettype/)
* Classe [ChartPlotArea](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)