---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides for C++ API 参考
description: "可组合系列类型组的枚举。每个元素对应于可以在同一 ChartSeriesGroup 中同时存在的一组图表系列类型。例如：ChartType::PercentsStackedArea 系列不能与 ChartType::StackedArea 系列同时出现在同一个 ChartSeriesGroup 中。但两个或更多 ChartType::PercentsStackedArea 可以在同一个 ChartSeriesGroup 中同时出现（CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea）。并且 ChartType::Line 系列可以与 ChartType::LineWithMarkers 系列在同一个 CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup 中同时出现。"
type: docs
weight: 1496
url: /zh/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup 枚举

可组合系列类型组的枚举。每个元素对应于可以在同一个[ChartSeriesGroup](../chartseriesgroup/)中同时存在的一组图表系列类型。例如：[ChartType::PercentsStackedArea](../charttype/) 系列不能与 [ChartType::StackedArea](../charttype/) 系列在同一个 [ChartSeriesGroup](../chartseriesgroup/) 中同时出现。但两个或更多 [ChartType::PercentsStackedArea](../charttype/) 可以在同一个 [ChartSeriesGroup](../chartseriesgroup/) 中同时出现（[CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)）。并且 [ChartType::Line](../charttype/) 系列可以与 [ChartType::LineWithMarkers](../charttype/) 系列在同一个 [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/) 中同时出现。

```cpp
enum class CombinableSeriesTypesGroup
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| AreaChart_Area | 4 | 将此系列类型集合分组为：{ [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | 将此系列类型集合分组为：{ [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | 将此系列类型集合分组为：{ [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | 将此系列类型集合分组为：{ [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | 将此系列类型集合分组为：{ [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | 将此系列类型集合分组为：{ [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | 将此系列类型集合分组为：{ [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | 将此系列类型集合分组为：{ [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | 将此系列类型集合分组为：{ [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | 将此系列类型集合分组为：{ [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | 将此系列类型集合分组为：{ [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | 将此系列类型集合分组为：{ [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | 将此系列类型集合分组为：{ [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | 将此系列类型集合分组为：{ [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | 将此系列类型集合分组为：{ [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | 将此系列类型集合分组为：{ [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | 将此系列类型集合分组为：{ [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | 将此系列类型集合分组为：{ [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | 将此系列类型集合分组为：{ [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | 将此系列类型集合分组为：{ [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | 将此系列类型集合分组为：{ [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | 将此系列类型集合分组为：{ [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | 将此系列类型集合分组为：{ [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | 将此系列类型集合分组为：{ [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | 将此系列类型集合分组为：{ [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | 将此系列类型集合分组为：{ [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | 将此系列类型集合分组为：{ [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | 将此系列类型集合分组为：{ [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | 将此系列类型集合分组为：{ [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | 将此系列类型集合分组为：{ [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | 将此系列类型集合分组为：{ [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | 将此系列类型集合分组为：{ [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | 将此系列类型集合分组为：{ [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | 将此系列类型集合分组为：{ [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | 将此系列类型集合分组为：{ [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | 将此系列类型集合分组为：{ [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | 将此系列类型集合分组为：{ [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | 将此系列类型集合分组为：{ [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | 将此系列类型集合分组为：{ [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | 将此系列类型集合分组为：{ [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | 将此系列类型集合分组为：{ [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | 将此系列类型集合分组为：{ [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | 将此系列类型集合分组为：{ [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | 将此系列类型集合分组为：{ [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | 将此系列类型集合分组为：{ [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | 将此系列类型集合分组为：{ [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | 将此系列类型集合分组为：{ [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | 将此系列类型集合分组为：{ [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | 将此系列类型集合分组为：{ [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | 将此系列类型集合分组为：{ [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | 将此系列类型集合分组为：{ [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | 将此系列类型集合分组为：{ [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | 将此系列类型集合分组为：{ [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | 将此系列类型集合分组为：{ [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | 将此系列类型集合分组为：{ [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | 将此系列类型集合分组为：{ [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | 将此系列类型集合分组为：{ [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | 将此系列类型集合分组为：{ [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | 将此系列类型集合分组为：{ [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | 将此系列类型集合分组为：{ [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | 将此系列类型集合分组为：{ [ChartType::Sunburst](../charttype/) } |

## 另请参阅

* 命名空间 [Aspose::Slides::Charts](../)
* 库 [Aspose.Slides](../../)