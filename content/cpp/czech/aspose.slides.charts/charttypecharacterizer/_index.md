---
title: ChartTypeCharacterizer
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Pomocník pro získání dalších informací o grafech a řadách podle jejich ChartType.
type: docs
weight: 339
url: /cs/aspose.slides.charts/charttypecharacterizer/
---
## ChartTypeCharacterizer třída

Helper for getting additional information about charts and series by its ChartType.

```cpp
class ChartTypeCharacterizer
```

## Metody

| Metoda | Popis |
| --- | --- |
|  [ChartTypeCharacterizer](./charttypecharacterizer/)() |  |
| static **bool** [HasSeriesTrendLines](./hasseriestrendlines/)([ChartType](../charttype/)) | Vrací, zda existují trendové čáry řady pro zadaný typ řady. |
| static **bool** [Is2DChart](./is2dchart/)([ChartType](../charttype/)) | Vrátí true, pokud *chartType* je jedním z 2D typů grafu. |
| static **bool** [Is3DChart](./is3dchart/)([ChartType](../charttype/)) | Vrátí true, pokud *chartType* je jedním z 3D typů grafu. |
| static **bool** [IsBar3DChart](./isbar3dchart/)([ChartType](../charttype/)) | Vrátí true, pokud chartType je jedním z podtypů bar3DChart (3D sloupců nebo pruhů). |
| static **bool** [IsChartTypeArea](./ischarttypearea/)([ChartType](../charttype/)) | Vrátí true, pokud chartType je jedním z podtypů Area. Množina podtypů odpovídá příslušné sadě v PowerPointu (viz dialog \"Change Chart Type\" v PowerPointu): [ChartType::Area](../charttype/), [ChartType::PercentsStackedArea](../charttype/), [ChartType::PercentsStackedArea3D](../charttype/), [ChartType::StackedArea](../charttype/), [ChartType::StackedArea3D](../charttype/), [ChartType::Area3D](../charttype/). |
| static **bool** [IsChartTypeBar](./ischarttypebar/)([ChartType](../charttype/)) | Vrátí true, pokud chartType je jedním z podtypů Bar. Množina podtypů odpovídá příslušné sadě v PowerPointu (viz dialog \"Change Chart Type\" v PowerPointu): [ChartType::ClusteredBar](../charttype/), [ChartType::ClusteredBar3D](../charttype/), [ChartType::PercentsStackedBar](../charttype/), [ChartType::PercentsStackedBar3D](../charttype/), [ChartType::StackedBar](../charttype/), [ChartType::StackedBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/), [ChartType::StackedHorizontalCone](../charttype/), [ChartType::StackedHorizontalCylinder](../charttype/), [ChartType::StackedHorizontalPyramid](../charttype/), [ChartType::PercentsStackedHorizontalCone](../charttype/), [ChartType::PercentsStackedHorizontalCylinder](../charttype/), [ChartType::PercentsStackedHorizontalPyramid](../charttype/). |
| static **bool** [IsChartTypeBubble](./ischarttypebubble/)([ChartType](../charttype/)) | Vrátí true, pokud chartType je jedním z podtypů Bubble. Množina podtypů odpovídá příslušné sadě v PowerPointu (viz dialog \"Change Chart Type\" v PowerPointu): [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/). |
| static **bool** [IsChartTypeColumn](./ischarttypecolumn/)([ChartType](../charttype/)) | Vrátí true, pokud chartType je jedním z podtypů [Column](../../aspose.slides/column/). Množina podtypů odpovídá příslušné sadě v PowerPointu (viz dialog \"Change Chart Type\" v PowerPointu): [ChartType::ClusteredColumn](../charttype/), [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/), [ChartType::PercentsStackedColumn](../charttype/), [ChartType::PercentsStackedColumn3D](../charttype/), [ChartType::PercentsStackedCone](../charttype/), [ChartType::PercentsStackedCylinder](../charttype/), [ChartType::PercentsStackedPyramid](../charttype/), [ChartType::StackedColumn](../charttype/), [ChartType::StackedColumn3D](../charttype/), [ChartType::StackedCone](../charttype/), [ChartType::StackedCylinder](../charttype/), [ChartType::StackedPyramid](../charttype/), [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/). |
| static **bool** [IsChartTypeDoughnut](./ischarttypedoughnut/)([ChartType](../charttype/)) | Vrátí true, pokud chartType je jedním z podtypů Doughnut. Množina podtypů odpovídá příslušné sadě v PowerPointu (viz dialog \"Change Chart Type\" v PowerPointu): [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/). |
| static **bool** [IsChartTypeLine](./ischarttypeline/)([ChartType](../charttype/)) | Vrátí true, pokud chartType je jedním z podtypů Line. Množina podtypů odpovídá příslušné sadě v PowerPointu (viz dialog \"Change Chart Type\" v PowerPointu): [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/), [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/), [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/), [ChartType::Line3D](../charttype/). |
| static **bool** [IsChartTypePie](./ischarttypepie/)([ChartType](../charttype/)) | Vrátí true, pokud chartType je jedním z podtypů Pie. Množina podtypů odpovídá příslušné sadě v PowerPointu (viz dialog \"Change Chart Type\" v PowerPointu): [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). |
| static **bool** [IsChartTypeRadar](./ischarttyperadar/)([ChartType](../charttype/)) | Vrátí true, pokud chartType je jedním z podtypů Radar. Množina podtypů odpovídá příslušné sadě v PowerPointu (viz dialog \"Change Chart Type\" v PowerPointu): [ChartType::FilledRadar](../charttype/), [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/). |
| static **bool** [IsChartTypeScatter](./ischarttypescatter/)([ChartType](../charttype/)) | Vrátí true, pokud chartType je jedním z podtypů Scatter. Množina podtypů odpovídá příslušné sadě v PowerPointu (viz dialog \"Change Chart Type\" v PowerPointu): [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/). |
| static **bool** [IsChartTypeStock](./ischarttypestock/)([ChartType](../charttype/)) | Vrátí true, pokud chartType je jedním z podtypů Stock. Množina podtypů odpovídá příslušné sadě v PowerPointu (viz dialog \"Change Chart Type\" v PowerPointu): [ChartType::HighLowClose](../charttype/), [ChartType::OpenHighLowClose](../charttype/), [ChartType::VolumeHighLowClose](../charttype/), [ChartType::VolumeOpenHighLowClose](../charttype/). |
| static **bool** [IsChartTypeSurface](./ischarttypesurface/)([ChartType](../charttype/)) | Vrátí true, pokud chartType je jedním z podtypů Surface. Množina podtypů odpovídá příslušné sadě v PowerPointu (viz dialog \"Change Chart Type\" v PowerPointu): [ChartType::Surface3D](../charttype/), [ChartType::WireframeSurface3D](../charttype/), [ChartType::Contour](../charttype/), [ChartType::WireframeContour](../charttype/). |
| static **bool** [IsErrorBarsXAllowed](./iserrorbarsxallowed/)([ChartType](../charttype/)) | Vrací, zda jsou pro zadaný typ řady povoleny chybové pruhy X. |
| static **bool** [IsErrorBarsYAllowed](./iserrorbarsyallowed/)([ChartType](../charttype/)) | Vrací, zda jsou pro zadaný typ řady povoleny chybové pruhy Y. |
| static **bool** [IsSeriesUsesBubbleSizeCoordinate](./isseriesusesbubblesizecoordinate/)([ChartType](../charttype/)) | Vrací, zda lze pro zadaný typ řady použít souřadnice velikosti bubliny. |
| static **bool** [IsSeriesUsesValueCoordinate](./isseriesusesvaluecoordinate/)([ChartType](../charttype/)) | Vrací, zda zadaný typ řady používá souřadnice hodnot. |
| static **bool** [IsSeriesUsesXValueCoordinate](./isseriesusesxvaluecoordinate/)([ChartType](../charttype/)) | Vrací, zda zadaný typ řady používá X souřadnice hodnot. |
| static **bool** [IsSeriesUsesYValueCoordinate](./isseriesusesyvaluecoordinate/)([ChartType](../charttype/)) | Vrací, zda zadaný typ řady používá Y souřadnice hodnot. |

## Viz také

* Jmenný prostor [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)