---
title: ChartTypeCharacterizer
second_title: Aspose.Slides C++ API referencia
description: Segédeszköz a diagramok és sorozatok további információinak lekéréséhez a ChartType alapján.
type: docs
weight: 339
url: /hu/aspose.slides.charts/charttypecharacterizer/
---
## ChartTypeCharacterizer osztály


Helper for getting additional information about charts and series by its ChartType.

```cpp
class ChartTypeCharacterizer
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
|  [ChartTypeCharacterizer](./charttypecharacterizer/)() |  |
| static **bool** [HasSeriesTrendLines](./hasseriestrendlines/)([ChartType](../charttype/)) | Visszaadja, hogy a megadott sorozattípushoz tartoznak-e trendvonalak. |
| static **bool** [Is2DChart](./is2dchart/)([ChartType](../charttype/)) | Igaz értéket ad vissza, ha a *chartType* a 2D diagramtípusok egyike. |
| static **bool** [Is3DChart](./is3dchart/)([ChartType](../charttype/)) | Igaz értéket ad vissza, ha a *chartType* a 3D diagramtípusok egyike. |
| static **bool** [IsBar3DChart](./isbar3dchart/)([ChartType](../charttype/)) | Igaz értéket ad vissza, ha a chartType a bar3DChart alttípusok egyike (3D oszlopok vagy sávok). |
| static **bool** [IsChartTypeArea](./ischarttypearea/)([ChartType](../charttype/)) | Igaz értéket ad vissza, ha a chartType az Area alttípusok egyike. Az alttípuskészlet megfelel a PowerPoint megfelelő készletének (lásd a \"Change Chart Type\" párbeszédablakot a PowerPointban): [ChartType::Area](../charttype/), [ChartType::PercentsStackedArea](../charttype/), [ChartType::PercentsStackedArea3D](../charttype/), [ChartType::StackedArea](../charttype/), [ChartType::StackedArea3D](../charttype/), [ChartType::Area3D](../charttype/). |
| static **bool** [IsChartTypeBar](./ischarttypebar/)([ChartType](../charttype/)) | Igaz értéket ad vissza, ha a chartType a Bar alttípusok egyike. Az alttípuskészlet megfelel a PowerPoint megfelelő készletének (lásd a \"Change Chart Type\" párbeszédablakot a PowerPointban): [ChartType::ClusteredBar](../charttype/), [ChartType::ClusteredBar3D](../charttype/), [ChartType::PercentsStackedBar](../charttype/), [ChartType::PercentsStackedBar3D](../charttype/), [ChartType::StackedBar](../charttype/), [ChartType::StackedBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/), [ChartType::StackedHorizontalCone](../charttype/), [ChartType::StackedHorizontalCylinder](../charttype/), [ChartType::StackedHorizontalPyramid](../charttype/), [ChartType::PercentsStackedHorizontalCone](../charttype/), [ChartType::PercentsStackedHorizontalCylinder](../charttype/), [ChartType::PercentsStackedHorizontalPyramid](../charttype/). |
| static **bool** [IsChartTypeBubble](./ischarttypebubble/)([ChartType](../charttype/)) | Igaz értéket ad vissza, ha a chartType a Bubble alttípusok egyike. Az alttípuskészlet megfelel a PowerPoint megfelelő készletének (lásd a \"Change Chart Type\" párbeszédablakot a PowerPointban): [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/). |
| static **bool** [IsChartTypeColumn](./ischarttypecolumn/)([ChartType](../charttype/)) | Igaz értéket ad vissza, ha a chartType a [Column](../../aspose.slides/column/) alttípusok egyike. Az alttípuskészlet megfelel a PowerPoint megfelelő készletének (lásd a \"Change Chart Type\" párbeszédablakot a PowerPointban): [ChartType::ClusteredColumn](../charttype/), [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/), [ChartType::PercentsStackedColumn](../charttype/), [ChartType::PercentsStackedColumn3D](../charttype/), [ChartType::PercentsStackedCone](../charttype/), [ChartType::PercentsStackedCylinder](../charttype/), [ChartType::PercentsStackedPyramid](../charttype/), [ChartType::StackedColumn](../charttype/), [ChartType::StackedColumn3D](../charttype/), [ChartType::StackedCone](../charttype/), [ChartType::StackedCylinder](../charttype/), [ChartType::StackedPyramid](../charttype/), [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/). |
| static **bool** [IsChartTypeDoughnut](./ischarttypedoughnut/)([ChartType](../charttype/)) | Igaz értéket ad vissza, ha a chartType a Doughnut alttípusok egyike. Az alttípuskészlet megfelel a PowerPoint megfelelő készletének (lásd a \"Change Chart Type\" párbeszédablakot a PowerPointban): [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/). |
| static **bool** [IsChartTypeLine](./ischarttypeline/)([ChartType](../charttype/)) | Igaz értéket ad vissza, ha a chartType a Line alttípusok egyike. Az alttípuskészlet megfelel a PowerPoint megfelelő készletének (lásd a \"Change Chart Type\" párbeszédablakot a PowerPointban): [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/), [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/), [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/), [ChartType::Line3D](../charttype/). |
| static **bool** [IsChartTypePie](./ischarttypepie/)([ChartType](../charttype/)) | Igaz értéket ad vissza, ha a chartType a Pie alttípusok egyike. Az alttípuskészlet megfelel a PowerPoint megfelelő készletének (lásd a \"Change Chart Type\" párbeszédablakot a PowerPointban): [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). |
| static **bool** [IsChartTypeRadar](./ischarttyperadar/)([ChartType](../charttype/)) | Igaz értéket ad vissza, ha a chartType a Radar alttípusok egyike. Az alttípuskészlet megfelel a PowerPoint megfelelő készletének (lásd a \"Change Chart Type\" párbeszédablakot a PowerPointban): [ChartType::FilledRadar](../charttype/), [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/). |
| static **bool** [IsChartTypeScatter](./ischarttypescatter/)([ChartType](../charttype/)) | Igaz értéket ad vissza, ha a chartType a Scatter alttípusok egyike. Az alttípuskészlet megfelel a PowerPoint megfelelő készletének (lásd a \"Change Chart Type\" párbeszédablakot a PowerPointban): [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/). |
| static **bool** [IsChartTypeStock](./ischarttypestock/)([ChartType](../charttype/)) | Igaz értéket ad vissza, ha a chartType a Stock alttípusok egyike. Az alttípuskészlet megfelel a PowerPoint megfelelő készletének (lásd a \"Change Chart Type\" párbeszédablakot a PowerPointban): [ChartType::HighLowClose](../charttype/), [ChartType::OpenHighLowClose](../charttype/), [ChartType::VolumeHighLowClose](../charttype/), [ChartType::VolumeOpenHighLowClose](../charttype/). |
| static **bool** [IsChartTypeSurface](./ischarttypesurface/)([ChartType](../charttype/)) | Igaz értéket ad vissza, ha a chartType a Surface alttípusok egyike. Az alttípuskészlet megfelel a PowerPoint megfelelő készletének (lásd a \"Change Chart Type\" párbeszédablakot a PowerPointban): [ChartType::Surface3D](../charttype/), [ChartType::WireframeSurface3D](../charttype/), [ChartType::Contour](../charttype/), [ChartType::WireframeContour](../charttype/). |
| static **bool** [IsErrorBarsXAllowed](./iserrorbarsxallowed/)([ChartType](../charttype/)) | Visszaadja, hogy a megadott sorozattípushoz engedélyezettek-e az X hibasávok. |
| static **bool** [IsErrorBarsYAllowed](./iserrorbarsyallowed/)([ChartType](../charttype/)) | Visszaadja, hogy a megadott sorozattípushoz engedélyezettek-e az Y hibasávok. |
| static **bool** [IsSeriesUsesBubbleSizeCoordinate](./isseriesusesbubblesizecoordinate/)([ChartType](../charttype/)) | Visszaadja, hogy a megadott sorozattípusnál használhatók-e a buborékméret koordinátái. |
| static **bool** [IsSeriesUsesValueCoordinate](./isseriesusesvaluecoordinate/)([ChartType](../charttype/)) | Visszaadja, hogy a megadott sorozattípus értékkordinátákat használ-e. |
| static **bool** [IsSeriesUsesXValueCoordinate](./isseriesusesxvaluecoordinate/)([ChartType](../charttype/)) | Visszaadja, hogy a megadott sorozattípus X értékkordinátákat használ-e. |
| static **bool** [IsSeriesUsesYValueCoordinate](./isseriesusesyvaluecoordinate/)([ChartType](../charttype/)) | Visszaadja, hogy a megadott sorozattípus Y értékkordinátákat használ-e. |
## Lásd még

* Névtere [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)