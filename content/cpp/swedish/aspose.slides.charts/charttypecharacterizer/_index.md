---
title: ChartTypeCharacterizer
second_title: Aspose.Slides för C++ API-referens
description: Hjälpmedel för att hämta ytterligare information om diagram och serier baserat på dess ChartType.
type: docs
weight: 339
url: /sv/aspose.slides.charts/charttypecharacterizer/
---
## ChartTypeCharacterizer klass

Hjälpmedel för att få ytterligare information om diagram och serier baserat på dess ChartType.

```cpp
class ChartTypeCharacterizer
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [ChartTypeCharacterizer](./charttypecharacterizer/)() |  |
| static **bool** [HasSeriesTrendLines](./hasseriestrendlines/)([ChartType](../charttype/)) | Returnerar om det finns trendlinjer för serien för den angivna serietypen. |
| static **bool** [Is2DChart](./is2dchart/)([ChartType](../charttype/)) | Returnerar true om *chartType* är en av 2D-diagramtyperna. |
| static **bool** [Is3DChart](./is3dchart/)([ChartType](../charttype/)) | Returnerar true om *chartType* är en av 3D-diagramtyperna. |
| static **bool** [IsBar3DChart](./isbar3dchart/)([ChartType](../charttype/)) | Returnerar true om chartType är en av bar3DChart-undertyperna (3D-kolumner eller staplar). |
| static **bool** [IsChartTypeArea](./ischarttypearea/)([ChartType](../charttype/)) | Returnerar true om chartType är en av Area-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan \"Change Chart Type\" i PowerPoint): [ChartType::Area](../charttype/), [ChartType::PercentsStackedArea](../charttype/), [ChartType::PercentsStackedArea3D](../charttype/), [ChartType::StackedArea](../charttype/), [ChartType::StackedArea3D](../charttype/), [ChartType::Area3D](../charttype/). |
| static **bool** [IsChartTypeBar](./ischarttypebar/)([ChartType](../charttype/)) | Returnerar true om chartType är en av Bar-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan \"Change Chart Type\" i PowerPoint): [ChartType::ClusteredBar](../charttype/), [ChartType::ClusteredBar3D](../charttype/), [ChartType::PercentsStackedBar](../charttype/), [ChartType::PercentsStackedBar3D](../charttype/), [ChartType::StackedBar](../charttype/), [ChartType::StackedBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/), [ChartType::StackedHorizontalCone](../charttype/), [ChartType::StackedHorizontalCylinder](../charttype/), [ChartType::StackedHorizontalPyramid](../charttype/), [ChartType::PercentsStackedHorizontalCone](../charttype/), [ChartType::PercentsStackedHorizontalCylinder](../charttype/), [ChartType::PercentsStackedHorizontalPyramid](../charttype/). |
| static **bool** [IsChartTypeBubble](./ischarttypebubble/)([ChartType](../charttype/)) | Returnerar true om chartType är en av Bubble-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan \"Change Chart Type\" i PowerPoint): [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/). |
| static **bool** [IsChartTypeColumn](./ischarttypecolumn/)([ChartType](../charttype/)) | Returnerar true om chartType är en av [Column](../../aspose.slides/column/)-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan \"Change Chart Type\" i PowerPoint): [ChartType::ClusteredColumn](../charttype/), [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/), [ChartType::PercentsStackedColumn](../charttype/), [ChartType::PercentsStackedColumn3D](../charttype/), [ChartType::PercentsStackedCone](../charttype/), [ChartType::PercentsStackedCylinder](../charttype/), [ChartType::PercentsStackedPyramid](../charttype/), [ChartType::StackedColumn](../charttype/), [ChartType::StackedColumn3D](../charttype/), [ChartType::StackedCone](../charttype/), [ChartType::StackedCylinder](../charttype/), [ChartType::StackedPyramid](../charttype/), [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/). |
| static **bool** [IsChartTypeDoughnut](./ischarttypedoughnut/)([ChartType](../charttype/)) | Returnerar true om chartType är en av Doughnut-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan \"Change Chart Type\" i PowerPoint): [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/). |
| static **bool** [IsChartTypeLine](./ischarttypeline/)([ChartType](../charttype/)) | Returnerar true om chartType är en av Line-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan \"Change Chart Type\" i PowerPoint): [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/), [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/), [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/), [ChartType::Line3D](../charttype/). |
| static **bool** [IsChartTypePie](./ischarttypepie/)([ChartType](../charttype/)) | Returnerar true om chartType är en av Pie-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan \"Change Chart Type\" i PowerPoint): [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). |
| static **bool** [IsChartTypeRadar](./ischarttyperadar/)([ChartType](../charttype/)) | Returnerar true om chartType är en av Radar-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan \"Change Chart Type\" i PowerPoint): [ChartType::FilledRadar](../charttype/), [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/). |
| static **bool** [IsChartTypeScatter](./ischarttypescatter/)([ChartType](../charttype/)) | Returnerar true om chartType är en av Scatter-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan \"Change Chart Type\" i PowerPoint): [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/). |
| static **bool** [IsChartTypeStock](./ischarttypestock/)([ChartType](../charttype/)) | Returnerar true om chartType är en av Stock-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan \"Change Chart Type\" i PowerPoint): [ChartType::HighLowClose](../charttype/), [ChartType::OpenHighLowClose](../charttype/), [ChartType::VolumeHighLowClose](../charttype/), [ChartType::VolumeOpenHighLowClose](../charttype/). |
| static **bool** [IsChartTypeSurface](./ischarttypesurface/)([ChartType](../charttype/)) | Returnerar true om chartType är en av Surface-undertyperna. Undertypsuppsättningen motsvarar den lämpliga uppsättningen i PowerPoint (se dialogrutan \"Change Chart Type\" i PowerPoint): [ChartType::Surface3D](../charttype/), [ChartType::WireframeSurface3D](../charttype/), [ChartType::Contour](../charttype/), [ChartType::WireframeContour](../charttype/). |
| static **bool** [IsErrorBarsXAllowed](./iserrorbarsxallowed/)([ChartType](../charttype/)) | Returnerar om felstaplar X är tillåtna för den angivna serietypen. |
| static **bool** [IsErrorBarsYAllowed](./iserrorbarsyallowed/)([ChartType](../charttype/)) | Returnerar om felstaplar Y är tillåtna för den angivna serietypen. |
| static **bool** [IsSeriesUsesBubbleSizeCoordinate](./isseriesusesbubblesizecoordinate/)([ChartType](../charttype/)) | Returnerar om bubbelstorlekskoordinater kan användas för den angivna serietypen. |
| static **bool** [IsSeriesUsesValueCoordinate](./isseriesusesvaluecoordinate/)([ChartType](../charttype/)) | Returnerar om den angivna serietypen använder värdekoordinater. |
| static **bool** [IsSeriesUsesXValueCoordinate](./isseriesusesxvaluecoordinate/)([ChartType](../charttype/)) | Returnerar om den angivna serietypen använder X-värdekoordinater. |
| static **bool** [IsSeriesUsesYValueCoordinate](./isseriesusesyvaluecoordinate/)([ChartType](../charttype/)) | Returnerar om den angivna serietypen använder Y-värdekoordinater. |

## Se även

* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)