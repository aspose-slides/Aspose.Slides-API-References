---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides for C++ API リファレンス
description: "結合可能な系列タイプのグループの列挙です。各要素は、1つの ChartSeriesGroup 内で同時に存在できるチャート系列タイプのグループに対応します。例えば、ChartType::PercentsStackedArea 系列は、1つの ChartSeriesGroup 内で ChartType::StackedArea 系列と同時に存在できません。しかし、2 つ以上の ChartType::PercentsStackedArea は、1つの ChartSeriesGroup 内で同時に配置できます（CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea）。また、ChartType::Line 系列は ChartType::LineWithMarkers 系列と同時に 1つの CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup 内に配置できます。"
type: docs
weight: 1496
url: /ja/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup 列挙型

結合可能な系列タイプのグループの列挙です。各要素は、1つの [ChartSeriesGroup](../chartseriesgroup/) 内で同時に存在できるチャート系列タイプのグループに対応します。例として、[ChartType::PercentsStackedArea](../charttype/) 系列は 1つの [ChartSeriesGroup](../chartseriesgroup/) 内で [ChartType::StackedArea](../charttype/) 系列と同時に存在できません。しかし、2つ以上の [ChartType::PercentsStackedArea](../charttype/) は 1つの [ChartSeriesGroup](../chartseriesgroup/) 内で同時に配置できます（[CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)）。また、[ChartType::Line](../charttype/) 系列は [ChartType::LineWithMarkers](../charttype/) 系列と同時に 1つの [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/) に配置できます。

```cpp
enum class CombinableSeriesTypesGroup
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| AreaChart_Area | 4 | このシリーズタイプのセットをグループ化: { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | このシリーズタイプのセットをグループ化: { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | このシリーズタイプのセットをグループ化: { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | このシリーズタイプのセットをグループ化: { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | このシリーズタイプのセットをグループ化: { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | このシリーズタイプのセットをグループ化: { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | このシリーズタイプのセットをグループ化: { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | このシリーズタイプのセットをグループ化: { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | このシリーズタイプのセットをグループ化: { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | このシリーズタイプのセットをグループ化: { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | このシリーズタイプのセットをグループ化: { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | このシリーズタイプのセットをグループ化: { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | このシリーズタイプのセットをグループ化: { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | このシリーズタイプのセットをグループ化: { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | このシリーズタイプのセットをグループ化: { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | このシリーズタイプのセットをグループ化: { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | このシリーズタイプのセットをグループ化: { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | このシリーズタイプのセットをグループ化: { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | このシリーズタイプのセットをグループ化: { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | このシリーズタイプのセットをグループ化: { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | このシリーズタイプのセットをグループ化: { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | このシリーズタイプのセットをグループ化: { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | このシリーズタイプのセットをグループ化: { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | このシリーズタイプのセットをグループ化: { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | このシリーズタイプのセットをグループ化: { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | このシリーズタイプのセットをグループ化: { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | このシリーズタイプのセットをグループ化: { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | このシリーズタイプのセットをグループ化: { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | このシリーズタイプのセットをグループ化: { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | このシリーズタイプのセットをグループ化: { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | このシリーズタイプのセットをグループ化: { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | このシリーズタイプのセットをグループ化: { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | このシリーズタイプのセットをグループ化: { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | このシリーズタイプのセットをグループ化: { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | このシリーズタイプのセットをグループ化: { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | このシリーズタイプのセットをグループ化: { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | このシリーズタイプのセットをグループ化: { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | このシリーズタイプのセットをグループ化: { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | このシリーズタイプのセットをグループ化: { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | このシリーズタイプのセットをグループ化: { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | このシリーズタイプのセットをグループ化: { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | このシリーズタイプのセットをグループ化: { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | このシリーズタイプのセットをグループ化: { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | このシリーズタイプのセットをグループ化: { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | このシリーズタイプのセットをグループ化: { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | このシリーズタイプのセットをグループ化: { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | このシリーズタイプのセットをグループ化: { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | このシリーズタイプのセットをグループ化: { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | このシリーズタイプのセットをグループ化: { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | このシリーズタイプのセットをグループ化: { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | このシリーズタイプのセットをグループ化: { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | このシリーズタイプのセットをグループ化: { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | このシリーズタイプのセットをグループ化: { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | このシリーズタイプのセットをグループ化: { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | このシリーズタイプのセットをグループ化: { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | このシリーズタイプのセットをグループ化: { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | このシリーズタイプのセットをグループ化: { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | このシリーズタイプのセットをグループ化: { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | このシリーズタイプのセットをグループ化: { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | このシリーズタイプのセットをグループ化: { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | このシリーズタイプのセットをグループ化: { [ChartType::Sunburst](../charttype/) } |

## 参照

* 名前空間 [Aspose::Slides::Charts](../)
* ライブラリ [Aspose.Slides](../../)