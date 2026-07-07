---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes for .NET API 參考文件
description: 列舉可組合系列類型的群組。每個元素對應於可同時存在於同一 ChartSeriesGroup 中的一組圖表系列類型。例如 ChartType.PercentsStackedArea 系列無法與 ChartType.StackedArea 系列同時出現在同一 ChartSeriesGroup 中。但兩個或以上的 ChartType.PercentsStackedArea 可以同時位於同一 ChartSeriesGroup（CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea）。且 ChartType.Line 系列可以與 ChartType.LineWithMarkers 系列同時出現在同一 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup 中。
type: docs
weight: 1530
url: /zh-hant/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup 列舉

組合系列類型的群組列舉。每個成員對應於可同時存在於同一 ChartSeriesGroup 中的一組圖表系列類型。例如：ChartType.PercentsStackedArea 系列無法與 ChartType.StackedArea 系列同時出現在同一 ChartSeriesGroup 中。但兩個或以上的 ChartType.PercentsStackedArea 可以同時位於同一 ChartSeriesGroup（CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea）。且 ChartType.Line 系列可與 ChartType.LineWithMarkers 系列同時出現在同一 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup 中。

```csharp
public enum CombinableSeriesTypesGroup
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| AreaChart_Area | `4` | 將此系列類型集合分組：{ ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | 將此系列類型集合分組：{ ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | 將此系列類型集合分組：{ ChartType.StackedArea } |
| AreaChart_Area3D | `24` | 將此系列類型集合分組：{ ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | 將此系列類型集合分組：{ ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | 將此系列類型集合分組：{ ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | 將此系列類型集合分組：{ ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | 將此系列類型集合分組：{ ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | 將此系列類型集合分組：{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | 將此系列類型集合分組：{ ChartType.Line3D } |
| StockHighLowClose | `18` | 將此系列類型集合分組：{ ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | 將此系列類型集合分組：{ ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | 將此系列類型集合分組：{ ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | 將此系列類型集合分組：{ ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | 將此系列類型集合分組：{ ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | 將此系列類型集合分組：{ ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | 將此系列類型集合分組：{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | 將此系列類型集合分組：{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | 將此系列類型集合分組：{ ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | 將此系列類型集合分組：{ ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | 將此系列類型集合分組：{ ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | 將此系列類型集合分組：{ ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | 將此系列類型集合分組：{ ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | 將此系列類型集合分組：{ ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | 將此系列類型集合分組：{ ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | 將此系列類型集合分組：{ ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | 將此系列類型集合分組：{ ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | 將此系列類型集合分組：{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | 將此系列類型集合分組：{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | 將此系列類型集合分組：{ ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | 將此系列類型集合分組：{ ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | 將此系列類型集合分組：{ ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | 將此系列類型集合分組：{ ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | 將此系列類型集合分組：{ ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | 將此系列類型集合分組：{ ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | 將此系列類型集合分組：{ ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | 將此系列類型集合分組：{ ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | 將此系列類型集合分組：{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | 將此系列類型集合分組：{ ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | 將此系列類型集合分組：{ ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | 將此系列類型集合分組：{ ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | 將此系列類型集合分組：{ ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | 將此系列類型集合分組：{ ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | 將此系列類型集合分組：{ ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | 將此系列類型集合分組：{ ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | 將此系列類型集合分組：{ ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | 將此系列類型集合分組：{ ChartType.BarOfPie } |
| PieOfPieChart | `1` | 將此系列類型集合分組：{ ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | 將此系列類型集合分組：{ ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | 將此系列類型集合分組：{ ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | 將此系列類型集合分組：{ ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | 將此系列類型集合分組：{ ChartType.WireframeSurface3D } |
| BubbleChart | `52` | 將此系列類型集合分組：{ ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | 將此系列類型集合分組：{ ChartType.Histogram } |
| ParetoLineChart | `54` | 將此系列類型集合分組：{ ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | 將此系列類型集合分組：{ ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | 將此系列類型集合分組：{ ChartType.Waterfall } |
| FunnelChart | `57` | 將此系列類型集合分組：{ ChartType.Funnel } |
| TreemapChart | `58` | 將此系列類型集合分組：{ ChartType.Treemap } |
| MapChart | `59` | 將此系列類型集合分組：{ ChartType.Map } |
| SunburstChart | `60` | 將此系列類型集合分組：{ ChartType.Sunburst } |

### 另請參考

* 命名空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->