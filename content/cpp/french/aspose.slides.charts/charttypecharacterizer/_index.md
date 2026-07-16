---
title: ChartTypeCharacterizer
second_title: Aspose.Slides pour C++ Référence de l'API
description: Assistant pour obtenir des informations supplémentaires sur les graphiques et les séries à partir de son ChartType.
type: docs
weight: 339
url: /fr/aspose.slides.charts/charttypecharacterizer/
---
## ChartTypeCharacterizer classe

Assistant pour obtenir des informations supplémentaires sur les graphiques et les séries à partir de son ChartType.

```cpp
class ChartTypeCharacterizer
```

## Méthodes

| Méthode | Description |
| --- | --- |
|  [ChartTypeCharacterizer](./charttypecharacterizer/)() |  |
| static **bool** [HasSeriesTrendLines](./hasseriestrendlines/)([ChartType](../charttype/)) | Renvoie s'il existe des lignes de tendance de série pour le type de série spécifié. |
| static **bool** [Is2DChart](./is2dchart/)([ChartType](../charttype/)) | Renvoie true si *chartType* est l'un des types de graphique 2D. |
| static **bool** [Is3DChart](./is3dchart/)([ChartType](../charttype/)) | Renvoie true si *chartType* est l'un des types de graphique 3D. |
| static **bool** [IsBar3DChart](./isbar3dchart/)([ChartType](../charttype/)) | Renvoie true si chartType est l'un des sous-types bar3DChart (colonnes ou barres 3D). |
| static **bool** [IsChartTypeArea](./ischarttypearea/)([ChartType](../charttype/)) | Renvoie true si chartType est l'un des sous-types Area. L'ensemble des sous-types correspond à celui approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType::Area](../charttype/), [ChartType::PercentsStackedArea](../charttype/), [ChartType::PercentsStackedArea3D](../charttype/), [ChartType::StackedArea](../charttype/), [ChartType::StackedArea3D](../charttype/), [ChartType::Area3D](../charttype/). |
| static **bool** [IsChartTypeBar](./ischarttypebar/)([ChartType](../charttype/)) | Renvoie true si chartType est l'un des sous-types Bar. L'ensemble des sous-types correspond à celui approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType::ClusteredBar](../charttype/), [ChartType::ClusteredBar3D](../charttype/), [ChartType::PercentsStackedBar](../charttype/), [ChartType::PercentsStackedBar3D](../charttype/), [ChartType::StackedBar](../charttype/), [ChartType::StackedBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/), [ChartType::StackedHorizontalCone](../charttype/), [ChartType::StackedHorizontalCylinder](../charttype/), [ChartType::StackedHorizontalPyramid](../charttype/), [ChartType::PercentsStackedHorizontalCone](../charttype/), [ChartType::PercentsStackedHorizontalCylinder](../charttype/), [ChartType::PercentsStackedHorizontalPyramid](../charttype/). |
| static **bool** [IsChartTypeBubble](./ischarttypebubble/)([ChartType](../charttype/)) | Renvoie true si chartType est l'un des sous-types Bubble. L'ensemble des sous-types correspond à celui approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/). |
| static **bool** [IsChartTypeColumn](./ischarttypecolumn/)([ChartType](../charttype/)) | Renvoie true si chartType est l'un des sous-types [Column](../../aspose.slides/column/). L'ensemble des sous-types correspond à celui approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType::ClusteredColumn](../charttype/), [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/), [ChartType::PercentsStackedColumn](../charttype/), [ChartType::PercentsStackedColumn3D](../charttype/), [ChartType::PercentsStackedCone](../charttype/), [ChartType::PercentsStackedCylinder](../charttype/), [ChartType::PercentsStackedPyramid](../charttype/), [ChartType::StackedColumn](../charttype/), [ChartType::StackedColumn3D](../charttype/), [ChartType::StackedCone](../charttype/), [ChartType::StackedCylinder](../charttype/), [ChartType::StackedPyramid](../charttype/), [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/). |
| static **bool** [IsChartTypeDoughnut](./ischarttypedoughnut/)([ChartType](../charttype/)) | Renvoie true si chartType est l'un des sous-types Doughnut. L'ensemble des sous-types correspond à celui approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/). |
| static **bool** [IsChartTypeLine](./ischarttypeline/)([ChartType](../charttype/)) | Renvoie true si chartType est l'un des sous-types Line. L'ensemble des sous-types correspond à celui approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/), [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/), [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/), [ChartType::Line3D](../charttype/). |
| static **bool** [IsChartTypePie](./ischarttypepie/)([ChartType](../charttype/)) | Renvoie true si chartType est l'un des sous-types Pie. L'ensemble des sous-types correspond à celui approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). |
| static **bool** [IsChartTypeRadar](./ischarttyperadar/)([ChartType](../charttype/)) | Renvoie true si chartType est l'un des sous-types Radar. L'ensemble des sous-types correspond à celui approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType::FilledRadar](../charttype/), [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/). |
| static **bool** [IsChartTypeScatter](./ischarttypescatter/)([ChartType](../charttype/)) | Renvoie true si chartType est l'un des sous-types Scatter. L'ensemble des sous-types correspond à celui approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/). |
| static **bool** [IsChartTypeStock](./ischarttypestock/)([ChartType](../charttype/)) | Renvoie true si chartType est l'un des sous-types Stock. L'ensemble des sous-types correspond à celui approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType::HighLowClose](../charttype/), [ChartType::OpenHighLowClose](../charttype/), [ChartType::VolumeHighLowClose](../charttype/), [ChartType::VolumeOpenHighLowClose](../charttype/). |
| static **bool** [IsChartTypeSurface](./ischarttypesurface/)([ChartType](../charttype/)) | Renvoie true si chartType est l'un des sous-types Surface. L'ensemble des sous-types correspond à celui approprié dans PowerPoint (voir la boîte de dialogue « Change Chart Type » dans PowerPoint) : [ChartType::Surface3D](../charttype/), [ChartType::WireframeSurface3D](../charttype/), [ChartType::Contour](../charttype/), [ChartType::WireframeContour](../charttype/). |
| static **bool** [IsErrorBarsXAllowed](./iserrorbarsxallowed/)([ChartType](../charttype/)) | Renvoie si les barres d'erreur X sont autorisées pour le type de série spécifié. |
| static **bool** [IsErrorBarsYAllowed](./iserrorbarsyallowed/)([ChartType](../charttype/)) | Renvoie si les barres d'erreur Y sont autorisées pour le type de série spécifié. |
| static **bool** [IsSeriesUsesBubbleSizeCoordinate](./isseriesusesbubblesizecoordinate/)([ChartType](../charttype/)) | Renvoie si les coordonnées de taille de bulle peuvent être utilisées pour le type de série spécifié. |
| static **bool** [IsSeriesUsesValueCoordinate](./isseriesusesvaluecoordinate/)([ChartType](../charttype/)) | Renvoie si le type de série spécifié utilise des coordonnées de valeur. |
| static **bool** [IsSeriesUsesXValueCoordinate](./isseriesusesxvaluecoordinate/)([ChartType](../charttype/)) | Renvoie si le type de série spécifié utilise les coordonnées de valeur X. |
| static **bool** [IsSeriesUsesYValueCoordinate](./isseriesusesyvaluecoordinate/)([ChartType](../charttype/)) | Renvoie si le type de série spécifié utilise les coordonnées de valeur Y. |

## Voir aussi

* Espace de noms [Aspose::Slides::Charts](../)
* Bibliothèque [Aspose.Slides](../../)