---  
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes for .NET API Reference  
description: 可组合系列类型的枚举。每个元素都与可以在一个 ChartSeriesGroup 中同时存在的图表系列类型组相关。例如，ChartType.PercentsStackedArea 系列不能与 ChartType.StackedArea 系列在一个 ChartSeriesGroup 中同时存在。但是两个或多个 ChartType.PercentsStackedArea 可以同时存在于一个 ChartSeriesGroup 中（CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea）。并且 ChartType.Line 系列可以与 ChartType.LineWithMarkers 系列在一个 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup 中同时存在。
type: docs  
weight: 1450  
url: /zh/aspose.slides.charts/combinableseriestypesgroup/
---  
  
## CombinableSeriesTypesGroup enumeration  
  
可组合系列类型的枚举。每个元素都与可以在一个 ChartSeriesGroup 中同时存在的图表系列类型组相关。例如：ChartType.PercentsStackedArea 系列不能与 ChartType.StackedArea 系列在一个 ChartSeriesGroup 中同时存在。但是两个或多个 ChartType.PercentsStackedArea 可以同时存在于一个 ChartSeriesGroup 中（CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea）。并且 ChartType.Line 系列可以与 ChartType.LineWithMarkers 系列在一个 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup 中同时存在。  
  
```csharp  
public enum CombinableSeriesTypesGroup  
```  
  
### Values  
  
| Name | Value | Description |  
| --- | --- | --- |  
| AreaChart_Area | `4` | 组合这一组系列类型：{ ChartType.Area } |  
| AreaChart_PercentsStackedArea | `5` | 组合这一组系列类型：{ ChartType.PercentsStackedArea } |  
| AreaChart_StackedArea | `6` | 组合这一组系列类型：{ ChartType.StackedArea } |  
| AreaChart_Area3D | `24` | 组合这一组系列类型：{ ChartType.Area3D } |  
| AreaChart_StackedArea3D | `25` | 组合这一组系列类型：{ ChartType.StackedArea3D } |  
| AreaChart_PercentsStackedArea3D | `26` | 组合这一组系列类型：{ ChartType.PercentsStackedArea3D } |  
| LineChart_Line | `13` | 组合这一组系列类型：{ ChartType.Line, ChartType.LineWithMarkers } |  
| LineChart_StackedLine | `14` | 组合这一组系列类型：{ ChartType.StackedLine, ChartType.StackedLineWithMarkers } |  
| LineChart_PercentsStackedLine | `15` | 组合这一组系列类型：{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |  
| Line3DChart | `27` | 组合这一组系列类型：{ ChartType.Line3D } |  
| StockHighLowClose | `18` | 组合这一组系列类型：{ ChartType.HighLowClose } |  
| StockOpenHighLowClose | `19` | 组合这一组系列类型：{ ChartType.OpenHighLowClose } |  
| StockVolumeHighLowClose | `20` | 组合这一组系列类型：{ ChartType.VolumeHighLowClose } |  
| StockVolumeOpenHighLowClose | `21` | 组合这一组系列类型：{ ChartType.VolumeOpenHighLowClose } |  
| RadarChart | `16` | 组合这一组系列类型：{ ChartType.Radar, ChartType.RadarWithMarkers } |  
| FilledRadarChart | `17` | 组合这一组系列类型：{ ChartType.FilledRadar } |  
| ScatterStraightMarker | `22` | 组合这一组系列类型：{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |  
| ScatterSmoothMarker | `23` | 组合这一组系列类型：{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |  
| PieChart | `3` | 组合这一组系列类型：{ ChartType.Pie, ChartType.ExplodedPie } |  
| Pie3DChart | `28` | 组合这一组系列类型：{ ChartType.Pie3D, ChartType.ExplodedPie3D } |  
| DoughnutChart | `2` | 组合这一组系列类型：{ ChartType.Doughnut, ChartType.ExplodedDoughnut } |  
| BarChart_VertClustered | `10` | 组合这一组系列类型：{ ChartType.ClusteredColumn } |  
| BarChart_VertStacked | `11` | 组合这一组系列类型：{ ChartType.StackedColumn } |  
| BarChart_VertPercentsStacked | `12` | 组合这一组系列类型：{ ChartType.PercentsStackedColumn } |  
| BarChart_HorizClustered | `7` | 组合这一组系列类型：{ ChartType.ClusteredBar } |  
| BarChart_HorizStacked | `8` | 组合这一组系列类型：{ ChartType.StackedBar } |  
| BarChart_HorizPercentsStacked | `9` | 组合这一组系列类型：{ ChartType.PercentsStackedBar } |  
| Bar3DChart_Vert | `29` | 组合这一组系列类型：{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |  
| Bar3DChart_VertClustered | `30` | 组合这一组系列类型：{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |  
| Bar3DChart_VertPercentsStackedColumn3D | `31` | 组合这一组系列类型：{ ChartType.PercentsStackedColumn3D } |  
| Bar3DChart_VertPercentsStackedCone | `32` | 组合这一组系列类型：{ ChartType.PercentsStackedCone } |  
| Bar3DChart_VertPercentsStackedCylinder | `33` | 组合这一组系列类型：{ ChartType.PercentsStackedCylinder } |  
| Bar3DChart_VertPercentsStackedPyramid | `34` | 组合这一组系列类型：{ ChartType.PercentsStackedPyramid } |  
| Bar3DChart_VertStackedColumn3D | `35` | 组合这一组系列类型：{ ChartType.StackedColumn3D } |  
| Bar3DChart_VertStackedCone | `36` | 组合这一组系列类型：{ ChartType.StackedCone } |  
| Bar3DChart_VertStackedCylinder | `37` | 组合这一组系列类型：{ ChartType.StackedCylinder } |  
| Bar3DChart_VertStackedPyramid | `38` | 组合这一组系列类型：{ ChartType.StackedPyramid } |  
| Bar3DChart_HorizClustered | `39` | 组合这一组系列类型：{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |  
| Bar3DChart_HorizStackedBar3D | `40` | 组合这一组系列类型：{ ChartType.StackedBar3D } |  
| Bar3DChart_HorizStackedCone | `41` | 组合这一组系列类型：{ ChartType.StackedHorizontalCone } |  
| Bar3DChart_HorizStackedCylinder | `42` | 组合这一组系列类型：{ ChartType.StackedHorizontalCylinder } |  
| Bar3DChart_HorizStackedPyramid | `43` | 组合这一组系列类型：{ ChartType.StackedHorizontalPyramid } |  
| Bar3DChart_HorizPercentsStackedBar3D | `44` | 组合这一组系列类型：{ ChartType.PercentsStackedBar3D } |  
| Bar3DChart_HorizPercentsStackedCone | `45` | 组合这一组系列类型：{ ChartType.PercentsStackedHorizontalCone } |  
| Bar3DChart_HorizPercentsStackedCylinder | `46` | 组合这一组系列类型：{ ChartType.PercentsStackedHorizontalCylinder } |  
| Bar3DChart_HorizPercentsStackedPyramid | `47` | 组合这一组系列类型：{ ChartType.PercentsStackedHorizontalPyramid } |  
| BarOfPieChart | `0` | 组合这一组系列类型：{ ChartType.BarOfPie } |  
| PieOfPieChart | `1` | 组合这一组系列类型：{ ChartType.PieOfPie } |  
| SurfaceChart_Contour | `48` | 组合这一组系列类型：{ ChartType.Contour } |  
| SurfaceChart_WireframeContour | `49` | 组合这一组系列类型：{ ChartType.WireframeContour } |  
| SurfaceChart_Surface3D | `50` | 组合这一组系列类型：{ ChartType.Surface3D } |  
| SurfaceChart_WireframeSurface3D | `51` | 组合这一组系列类型：{ ChartType.WireframeSurface3D } |  
| BubbleChart | `52` | 组合这一组系列类型：{ ChartType.Bubble, ChartType.BubbleWith3D } |  
| HistogramChart | `53` | 组合这一组系列类型：{ ChartType.Histogram } |  
| ParetoLineChart | `54` | 组合这一组系列类型：{ ChartType.ParetoLine } |  
| BoxAndWhiskerChart | `55` | 组合这一组系列类型：{ ChartType.BoxAndWhisker } |  
| WaterfallChart | `56` | 组合这一组系列类型：{ ChartType.Waterfall } |  
| FunnelChart | `57` | 组合这一组系列类型：{ ChartType.Funnel } |  
| TreemapChart | `58` | 组合这一组系列类型：{ ChartType.Treemap } |  
| MapChart | `59` | 组合这一组系列类型：{ ChartType.Map } |  
| SunburstChart | `60` | 组合这一组系列类型：{ ChartType.Sunburst } |  
  
### See Also  
  
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)  
* assembly [Aspose.Slides](../../)  
  
<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  