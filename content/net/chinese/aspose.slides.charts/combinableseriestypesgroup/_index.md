---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes for .NET API 参考
description: 可组合系列类型组的枚举。每个元素对应于可以在同一个 ChartSeriesGroup 中同时存在的一组图表系列类型。例如，ChartType.PercentsStackedArea 系列不能与 ChartType.StackedArea 系列在同一个 ChartSeriesGroup 中同时存在。但两个或多个 ChartType.PercentsStackedArea 可以同时位于同一个 ChartSeriesGroup（CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea）。并且 ChartType.Line 系列可以与 ChartType.LineWithMarkers 系列在同一个 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup 中同时存在。
type: docs
weight: 1530
url: /zh/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup 枚举

可组合系列类型组的枚举。每个元素对应于可以在同一个 ChartSeriesGroup 中同时存在的一组图表系列类型。例如：ChartType.PercentsStackedArea 系列不能与 ChartType.StackedArea 系列在同一个 ChartSeriesGroup 中同时存在。但两个或更多 ChartType.PercentsStackedArea 可以同时位于同一个 ChartSeriesGroup 中（CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea）。并且 ChartType.Line 系列可以与 ChartType.LineWithMarkers 系列在同一个 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup 中同时存在。

```csharp
public enum CombinableSeriesTypesGroup
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| AreaChart_Area | `4` | 对该系列类型集合进行分组：{ ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | 对该系列类型集合进行分组：{ ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | 对该系列类型集合进行分组：{ ChartType.StackedArea } |
| AreaChart_Area3D | `24` | 对该系列类型集合进行分组：{ ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | 对该系列类型集合进行分组：{ ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | 对该系列类型集合进行分组：{ ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | 对该系列类型集合进行分组：{ ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | 对该系列类型集合进行分组：{ ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | 对该系列类型集合进行分组：{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | 对该系列类型集合进行分组：{ ChartType.Line3D } |
| StockHighLowClose | `18` | 对该系列类型集合进行分组：{ ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | 对该系列类型集合进行分组：{ ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | 对该系列类型集合进行分组：{ ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | 对该系列类型集合进行分组：{ ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | 对该系列类型集合进行分组：{ ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | 对该系列类型集合进行分组：{ ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | 对该系列类型集合进行分组：{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | 对该系列类型集合进行分组：{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | 对该系列类型集合进行分组：{ ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | 对该系列类型集合进行分组：{ ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | 对该系列类型集合进行分组：{ ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | 对该系列类型集合进行分组：{ ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | 对该系列类型集合进行分组：{ ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | 对该系列类型集合进行分组：{ ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | 对该系列类型集合进行分组：{ ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | 对该系列类型集合进行分组：{ ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | 对该系列类型集合进行分组：{ ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | 对该系列类型集合进行分组：{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | 对该系列类型集合进行分组：{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | 对该系列类型集合进行分组：{ ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | 对该系列类型集合进行分组：{ ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | 对该系列类型集合进行分组：{ ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | 对该系列类型集合进行分组：{ ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | 对该系列类型集合进行分组：{ ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | 对该系列类型集合进行分组：{ ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | 对该系列类型集合进行分组：{ ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | 对该系列类型集合进行分组：{ ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | 对该系列类型集合进行分组：{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | 对该系列类型集合进行分组：{ ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | 对该系列类型集合进行分组：{ ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | 对该系列类型集合进行分组：{ ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | 对该系列类型集合进行分组：{ ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | 对该系列类型集合进行分组：{ ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | 对该系列类型集合进行分组：{ ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | 对该系列类型集合进行分组：{ ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | 对该系列类型集合进行分组：{ ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | 对该系列类型集合进行分组：{ ChartType.BarOfPie } |
| PieOfPieChart | `1` | 对该系列类型集合进行分组：{ ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | 对该系列类型集合进行分组：{ ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | 对该系列类型集合进行分组：{ ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | 对该系列类型集合进行分组：{ ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | 对该系列类型集合进行分组：{ ChartType.WireframeSurface3D } |
| BubbleChart | `52` | 对该系列类型集合进行分组：{ ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | 对该系列类型集合进行分组：{ ChartType.Histogram } |
| ParetoLineChart | `54` | 对该系列类型集合进行分组：{ ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | 对该系列类型集合进行分组：{ ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | 对该系列类型集合进行分组：{ ChartType.Waterfall } |
| FunnelChart | `57` | 对该系列类型集合进行分组：{ ChartType.Funnel } |
| TreemapChart | `58` | 对该系列类型集合进行分组：{ ChartType.Treemap } |
| MapChart | `59` | 对该系列类型集合进行分组：{ ChartType.Map } |
| SunburstChart | `60` | 对该系列类型集合进行分组：{ ChartType.Sunburst } |

### 另请参见

* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->