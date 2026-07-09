---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes for .NET API 參考
description: 可組合系列類型群組的列舉。每個元素對應於可同時存在於同一 ChartSeriesGroup 中的圖表系列類型群組。例如 ChartType.PercentsStackedArea 系列無法與 ChartType.StackedArea 系列同時存在於同一 ChartSeriesGroup 中。但兩個或多個 ChartType.PercentsStackedArea 可以同時位於同一 ChartSeriesGroup，形式為 CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea。而 ChartType.Line 系列可以與 ChartType.LineWithMarkers 系列同時位於同一 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup 中。
type: docs
weight: 1530
url: /zh-hant/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup 列舉

列舉可組合系列類型的群組。每個元素對應於可同時存在於同一 ChartSeriesGroup 中的圖表系列類型群組。例如：ChartType.PercentsStackedArea 系列無法與 ChartType.StackedArea 系列在同一 ChartSeriesGroup 中同時存在。但兩個或多個 ChartType.PercentsStackedArea 可以同時位於同一 ChartSeriesGroup (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea)。且 ChartType.Line 系列可以與 ChartType.LineWithMarkers 系列同時位於同一 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup 中。

```csharp
public enum CombinableSeriesTypesGroup
```

### Values

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| AreaChart_Area | `4` | 將此組系列類型分組為: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | 將此組系列類型分組為: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | 將此組系列類型分組為: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | 將此組系列類型分組為: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | 將此組系列類型分組為: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | 將此組系列類型分組為: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | 將此組系列類型分組為: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | 將此組系列類型分組為: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | 將此組系列類型分組為: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | 將此組系列類型分組為: { ChartType.Line3D } |
| StockHighLowClose | `18` | 將此組系列類型分組為: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | 將此組系列類型分組為: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | 將此組系列類型分組為: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | 將此組系列類型分組為: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | 將此組系列類型分組為: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | 將此組系列類型分組為: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | 将此組系列類型分組為: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | 将此組系列類型分組為: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | 将此組系列類型分組為: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | 将此組系列類型分組為: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | 将此組系列類型分組為: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | 将此組系列類型分組為: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | 将此組系列類型分組為: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | 将此組系列類型分組為: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | 将此組系列類型分組為: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | 将此組系列類型分組為: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | 将此組系列類型分組為: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | 将此組系列類型分組為: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | 将此組系列類型分組為: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | 将此組系列類型分組為: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | 将此組系列類型分組為: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | 将此組系列類型分組為: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | 将此組系列類型分組為: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | 将此組系列類型分組為: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | 将此組系列類型分組為: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | 将此組系列類型分組為: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | 将此組系列類型分組為: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | 将此組系列類型分組為: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | 将此組系列類型分組為: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | 将此組系列類型分組為: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | 将此組系列類型分組為: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | 将此組系列類型分組為: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | 将此組系列類型分組為: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | 将此組系列類型分組為: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | 将此組系列類型分組為: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | 将此組系列類型分組為: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | 将此組系列類型分組為: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | 将此組系列類型分組為: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | 将此組系列類型分組為: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | 将此組系列類型分組為: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | 将此組系列類型分組為: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | 将此組系列類型分組為: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | 将此組系列類型分組為: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | 将此組系列類型分組為: { ChartType.Histogram } |
| ParetoLineChart | `54` | 将此組系列類型分組為: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | 将此組系列類型分組為: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | 将此組系列類型分組為: { ChartType.Waterfall } |
| FunnelChart | `57` | 将此組系列類型分組為: { ChartType.Funnel } |
| TreemapChart | `58` | 将此組系列類型分組為: { ChartType.Treemap } |
| MapChart | `59` | 将此組系列類型分組為: { ChartType.Map } |
| SunburstChart | `60` | 将此組系列類型分組為: { ChartType.Sunburst } |

### 另請參閱

* 命名空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->