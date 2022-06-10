---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides for .NET API 参考
description: 可组合系列类型组的枚举 每个元素都与一组图表系列类型相关这些图表系列可以同时存在于一个 ChartSeriesGroup 中 例如ChartType.PercentsStackedArea 系列不能与 ChartType.StackedArea 系列 在一个 ChartSeriesGroup 中同时出现但是两个或多个 ChartType.PercentsStackedArea 可以同时在一个 ChartSeriesGroup 中CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea并且 ChartType.Line 系列可以是 和 ChartType.LineWithMarkers 系列同时在一个 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup 中
type: docs
weight: 1390
url: /zh/net/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeration

可组合系列类型组的枚举。 每个元素都与一组图表系列类型相关，这些图表系列可以同时存在于一个 ChartSeriesGroup 中。 例如:ChartType.PercentsStackedArea 系列不能与 ChartType.StackedArea 系列 在一个 ChartSeriesGroup 中同时出现。但是两个或多个 ChartType.PercentsStackedArea 可以同时在一个 ChartSeriesGroup 中（CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea）。并且 ChartType.Line 系列可以是 和 ChartType.LineWithMarkers 系列同时在一个 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup 中。

```csharp
public enum CombinableSeriesTypesGroup
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| AreaChart_Area | `4` | 对这组系列类型进行分组: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | 对这组系列类型进行分组: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | 对这组系列类型进行分组: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | 对这组系列类型进行分组: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | 对这组系列类型进行分组: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | 对这组系列类型进行分组: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | 对这组系列类型进行分组: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | 对这组系列类型进行分组: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | 对这组系列类型进行分组: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | 对这组系列类型进行分组: { ChartType.Line3D } |
| StockHighLowClose | `18` | 对这组系列类型进行分组: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | 对这组系列类型进行分组: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | 对这组系列类型进行分组: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | 对这组系列类型进行分组: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | 对这组系列类型进行分组: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | 将这组系列类型分组: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | 对这组系列类型进行分组: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | 将这组系列类型分组: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | 对这组系列类型进行分组: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | 对这组系列类型进行分组: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | 对这组系列类型进行分组: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | 对这组系列类型进行分组: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | 对这组系列类型进行分组: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | 对这组系列类型进行分组: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | 对这组系列类型进行分组: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | 对这组系列类型进行分组: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | 对这组系列类型进行分组: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | 对这组系列类型进行分组: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | 对这组系列类型进行分组: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | 对这组系列类型进行分组: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | 对这组系列类型进行分组: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | 对这组系列类型进行分组: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | 对这组系列类型进行分组: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | 对这组系列类型进行分组: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | 对这组系列类型进行分组: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | 对这组系列类型进行分组: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | 对这组系列类型进行分组: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | 对这组系列类型进行分组: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | 对这组系列类型进行分组: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | 对这组系列类型进行分组: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | 对这组系列类型进行分组: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | 将这组系列类型分组: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | 将这组系列类型分组: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | 对这组系列类型进行分组: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | 对这组系列类型进行分组: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | 对这组系列类型进行分组: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | 对这组系列类型进行分组: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | 对这组系列类型进行分组: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | 对这组系列类型进行分组: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | 对这组系列类型进行分组: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | 对这组系列类型进行分组: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | 对这组系列类型进行分组: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | 对这组系列类型进行分组: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | 对这组系列类型进行分组: { ChartType.Histogram } |
| ParetoLineChart | `54` | 对这组系列类型进行分组: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | 对这组系列类型进行分组: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | 将这组系列类型分组: { ChartType.Waterfall } |
| FunnelChart | `57` | 对这组系列类型进行分组: { ChartType.Funnel } |
| TreemapChart | `58` | 对这组系列类型进行分组: { ChartType.Treemap } |
| MapChart | `59` | 对这组系列类型进行分组: { ChartType.Map } |
| SunburstChart | `60` | 对这组系列类型进行分组: { ChartType.Sunburst } |

### 也可以看看

* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
