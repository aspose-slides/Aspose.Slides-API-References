---
title: ChartTypeCharacterizer
second_title: Aspose.Slides C++ API 參考手冊
description: 協助根據圖表類型取得關於圖表和系列的其他資訊。
type: docs
weight: 339
url: /zh-hant/aspose.slides.charts/charttypecharacterizer/
---
## ChartTypeCharacterizer 類別


```cpp
class ChartTypeCharacterizer
```

## 方法

| 方法 | 說明 |
| --- | --- |
|  [ChartTypeCharacterizer](./charttypecharacterizer/)() |  |
| static **bool** [HasSeriesTrendLines](./hasseriestrendlines/)([ChartType](../charttype/)) | 傳回是否對指定的系列類型存在趨勢線。 |
| static **bool** [Is2DChart](./is2dchart/)([ChartType](../charttype/)) | 若 *chartType* 為 2D 圖表類型之一，則傳回 true。 |
| static **bool** [Is3DChart](./is3dchart/)([ChartType](../charttype/)) | 若 *chartType* 為 3D 圖表類型之一，則傳回 true。 |
| static **bool** [IsBar3DChart](./isbar3dchart/)([ChartType](../charttype/)) | 若 chartType 為 bar3DChart 子類型之一（3D 欄或列），則傳回 true。 |
| static **bool** [IsChartTypeArea](./ischarttypearea/)([ChartType](../charttype/)) | 若 chartType 為 Area 子類型之一。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType::Area](../charttype/), [ChartType::PercentsStackedArea](../charttype/), [ChartType::PercentsStackedArea3D](../charttype/), [ChartType::StackedArea](../charttype/), [ChartType::StackedArea3D](../charttype/), [ChartType::Area3D](../charttype/)。 |
| static **bool** [IsChartTypeBar](./ischarttypebar/)([ChartType](../charttype/)) | 若 chartType 為 Bar 子類型之一。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType::ClusteredBar](../charttype/), [ChartType::ClusteredBar3D](../charttype/), [ChartType::PercentsStackedBar](../charttype/), [ChartType::PercentsStackedBar3D](../charttype/), [ChartType::StackedBar](../charttype/), [ChartType::StackedBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/), [ChartType::StackedHorizontalCone](../charttype/), [ChartType::StackedHorizontalCylinder](../charttype/), [ChartType::StackedHorizontalPyramid](../charttype/), [ChartType::PercentsStackedHorizontalCone](../charttype/), [ChartType::PercentsStackedHorizontalCylinder](../charttype/), [ChartType::PercentsStackedHorizontalPyramid](../charttype/)。 |
| static **bool** [IsChartTypeBubble](./ischarttypebubble/)([ChartType](../charttype/)) | 若 chartType 為 Bubble 子類型之一。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/)。 |
| static **bool** [IsChartTypeColumn](./ischarttypecolumn/)([ChartType](../charttype/)) | 若 chartType 為 [Column](../../aspose.slides/column/) 子類型之一。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType::ClusteredColumn](../charttype/), [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/), [ChartType::PercentsStackedColumn](../charttype/), [ChartType::PercentsStackedColumn3D](../charttype/), [ChartType::PercentsStackedCone](../charttype/), [ChartType::PercentsStackedCylinder](../charttype/), [ChartType::PercentsStackedPyramid](../charttype/), [ChartType::StackedColumn](../charttype/), [ChartType::StackedColumn3D](../charttype/), [ChartType::StackedCone](../charttype/), [ChartType::StackedCylinder](../charttype/), [ChartType::StackedPyramid](../charttype/), [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/)。 |
| static **bool** [IsChartTypeDoughnut](./ischarttypedoughnut/)([ChartType](../charttype/)) | 若 chartType 為 Doughnut 子類型之一。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/)。 |
| static **bool** [IsChartTypeLine](./ischarttypeline/)([ChartType](../charttype/)) | 若 chartType 為 Line 子類型之一。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/), [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/), [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/), [ChartType::Line3D](../charttype/)。 |
| static **bool** [IsChartTypePie](./ischarttypepie/)([ChartType](../charttype/)) | 若 chartType 為 Pie 子類型之一。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/)。 |
| static **bool** [IsChartTypeRadar](./ischarttyperadar/)([ChartType](../charttype/)) | 若 chartType 為 Radar 子類型之一。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType::FilledRadar](../charttype/), [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/)。 |
| static **bool** [IsChartTypeScatter](./ischarttypescatter/)([ChartType](../charttype/)) | 若 chartType 為 Scatter 子類型之一。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/)。 |
| static **bool** [IsChartTypeStock](./ischarttypestock/)([ChartType](../charttype/)) | 若 chartType 為 Stock 子類型之一。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType::HighLowClose](../charttype/), [ChartType::OpenHighLowClose](../charttype/), [ChartType::VolumeHighLowClose](../charttype/), [ChartType::VolumeOpenHighLowClose](../charttype/)。 |
| static **bool** [IsChartTypeSurface](./ischarttypesurface/)([ChartType](../charttype/)) | 若 chartType 為 Surface 子類型之一。子類型集合對應 PowerPoint 中的相應集合（請參閱 PowerPoint 中的「變更圖表類型」對話方塊）：[ChartType::Surface3D](../charttype/), [ChartType::WireframeSurface3D](../charttype/), [ChartType::Contour](../charttype/), [ChartType::WireframeContour](../charttype/)。 |
| static **bool** [IsErrorBarsXAllowed](./iserrorbarsxallowed/)([ChartType](../charttype/)) | 傳回是否允許在指定的系列類型中使用 X 誤差棒。 |
| static **bool** [IsErrorBarsYAllowed](./iserrorbarsyallowed/)([ChartType](../charttype/)) | 傳回是否允許在指定的系列類型中使用 Y 誤差棒。 |
| static **bool** [IsSeriesUsesBubbleSizeCoordinate](./isseriesusesbubblesizecoordinate/)([ChartType](../charttype/)) | 傳回是否可在指定的系列類型中使用泡沫大小座標。 |
| static **bool** [IsSeriesUsesValueCoordinate](./isseriesusesvaluecoordinate/)([ChartType](../charttype/)) | 傳回指定的系列類型是否使用值座標。 |
| static **bool** [IsSeriesUsesXValueCoordinate](./isseriesusesxvaluecoordinate/)([ChartType](../charttype/)) | 傳回指定的系列類型是否使用 X 值座標。 |
| static **bool** [IsSeriesUsesYValueCoordinate](./isseriesusesyvaluecoordinate/)([ChartType](../charttype/)) | 傳回指定的系列類型是否使用 Y 值座標。 |

## 參見

* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)