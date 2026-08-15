---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides for C++ API 參考文件
description: "可組合系列類型群組的列舉。每個元素對應於圖表系列類型的群組，這些系列可以同時存在於一個 ChartSeriesGroup 中。例如：ChartType::PercentsStackedArea 系列無法與 ChartType::StackedArea 系列同時出現在同一個 ChartSeriesGroup 中。但兩個或更多 ChartType::PercentsStackedArea 可以同時位於同一個 ChartSeriesGroup 中 (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea)。且 ChartType::Line 系列可以與 ChartType::LineWithMarkers 系列同時出現在同一個 CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup 中。"
type: docs
weight: 1496
url: /zh-hant/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup 列舉


列舉可組合系列類型的群組。每個元素對應於一組圖表系列類型，這些類型可以同時存在於一個 [ChartSeriesGroup](../chartseriesgroup/) 中。例如：[ChartType::PercentsStackedArea](../charttype/) 系列無法與 [ChartType::StackedArea](../charttype/) 系列同時出現在同一個 [ChartSeriesGroup](../chartseriesgroup/) 中。但兩個或更多 [ChartType::PercentsStackedArea](../charttype/) 可以同時位於同一個 [ChartSeriesGroup](../chartseriesgroup/) 中（[CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)）。且 [ChartType::Line](../charttype/) 系列可以與 [ChartType::LineWithMarkers](../charttype/) 系列同時出現在同一個 [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/) 中。

```cpp
enum class CombinableSeriesTypesGroup
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| AreaChart_Area | 4 | 將此系列類型集合分組：{ [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | 將此系列類型集合分組：{ [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | 將此系列類型集合分組：{ [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | 將此系列類型集合分組：{ [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | 將此系列類型集合分組：{ [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | 將此系列類型集合分組：{ [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | 將此系列類型集合分組：{ [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | 將此系列類型集合分組：{ [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | 將此系列類型集合分組：{ [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | 將此系列類型集合分組：{ [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | 將此系列類型集合分組：{ [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | 將此系列類型集合分組：{ [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | 將此系列類型集合分組：{ [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | 將此系列類型集合分組：{ [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | 將此系列類型集合分組：{ [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | 將此系列類型集合分組：{ [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | 將此系列類型集合分組：{ [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | 將此系列類型集合分組：{ [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | 將此系列類型集合分組：{ [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | 將此系列類型集合分組：{ [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | 將此系列類型集合分組：{ [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | 將此系列類型集合分組：{ [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | 將此系列類型集合分組：{ [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | 將此系列類型集合分組：{ [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | 將此系列類型集合分組：{ [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | 將此系列類型集合分組：{ [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | 將此系列類型集合分組：{ [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | 將此系列類型集合分組：{ [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | 將此系列類型集合分組：{ [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | 將此系列類型集合分組：{ [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | 將此系列類型集合分組：{ [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | 將此系列類型集合分組：{ [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | 將此系列類型集合分組：{ [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | 將此系列類型集合分組：{ [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | 將此系列類型集合分組：{ [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | 將此系列類型集合分組：{ [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | 將此系列類型集合分組：{ [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | 將此系列類型集合分組：{ [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | 將此系列類型集合分組：{ [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | 將此系列類型集合分組：{ [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | 將此系列類型集合分組：{ [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | 將此系列類型集合分組：{ [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | 將此系列類型集合分組：{ [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | 將此系列類型集合分組：{ [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | 將此系列類型集合分組：{ [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | 將此系列類型集合分組：{ [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | 將此系列類型集合分組：{ [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | 將此系列類型集合分組：{ [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | 將此系列類型集合分組：{ [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | 將此系列類型集合分組：{ [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | 將此系列類型集合分組：{ [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | 將此系列類型集合分組：{ [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | 將此系列類型集合分組：{ [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | 將此系列類型集合分組：{ [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | 將此系列類型集合分組：{ [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | 將此系列類型集合分組：{ [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | 將此系列類型集合分組：{ [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | 將此系列類型集合分組：{ [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | 將此系列類型集合分組：{ [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | 將此系列類型集合分組：{ [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | 將此系列類型集合分組：{ [ChartType::Sunburst](../charttype/) } |

## 另見

* 命名空間 [Aspose::Slides::Charts](../)
* 函式庫 [Aspose.Slides](../../)