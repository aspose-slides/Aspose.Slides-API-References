---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes for .NET API リファレンス
description: 組み合わせ可能な系列タイプのグループを列挙した列挙体です。各要素は、1つの ChartSeriesGroup 内で同時に存在できるチャート系列のタイプのグループに対応します。たとえば、ChartType.PercentsStackedArea 系列は同じ ChartSeriesGroup 内で ChartType.StackedArea 系列と同時に存在できません。ただし、ChartType.PercentsStackedArea 系列が 2 つ以上あれば、1つの ChartSeriesGroup 内で同時に存在できます（CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea）。また、ChartType.Line 系列は ChartType.LineWithMarkers 系列と同時に 1つの CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup 内に配置できます。
type: docs
weight: 1530
url: /ja/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup 列挙体

組み合わせ可能な系列タイプのグループの列挙です。各要素は、1つの ChartSeriesGroup 内で同時に存在できるチャート系列のタイプのグループに対応します。例えば、ChartType.PercentsStackedArea 系列は ChartType.StackedArea 系列と同じ ChartSeriesGroup に同時に配置できません。ただし、ChartType.PercentsStackedArea 系列は複数あれば同じ ChartSeriesGroup に同時に配置できます（CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea）。また、ChartType.Line 系列は ChartType.LineWithMarkers 系列と同じ CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup に同時に配置できます。

```csharp
public enum CombinableSeriesTypesGroup
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| AreaChart_Area | `4` | この系列タイプのセットをグループ化します: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | この系列タイプのセットをグループ化します: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | この系列タイプのセットをグループ化します: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | この系列タイプのセットをグループ化します: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | この系列タイプのセットをグループ化します: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | この系列タイプのセットをグループ化します: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | この系列タイプのセットをグループ化します: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | この系列タイプのセットをグループ化します: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | この系列タイプのセットをグループ化します: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | この系列タイプのセットをグループ化します: { ChartType.Line3D } |
| StockHighLowClose | `18` | この系列タイプのセットをグループ化します: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | この系列タイプのセットをグループ化します: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | この系列タイプのセットをグループ化します: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | この系列タイプのセットをグループ化します: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | この系列タイプのセットをグループ化します: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | この系列タイプのセットをグループ化します: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | この系列タイプのセットをグループ化します: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | この系列タイプのセットをグループ化します: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | この系列タイプのセットをグループ化します: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | この系列タイプのセットをグループ化します: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | この系列タイプのセットをグループ化します: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | この系列タイプのセットをグループ化します: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | この系列タイプのセットをグループ化します: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | この系列タイプのセットをグループ化します: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | この系列タイプのセットをグループ化します: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | この系列タイプのセットをグループ化します: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | この系列タイプのセットをグループ化します: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | この系列タイプのセットをグループ化します: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | この系列タイプのセットをグループ化します: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | この系列タイプのセットをグループ化します: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | この系列タイプのセットをグループ化します: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | この系列タイプのセットをグループ化します: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | この系列タイプのセットをグループ化します: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | この系列タイプのセットをグループ化します: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | この系列タイプのセットをグループ化します: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | この系列タイプのセットをグループ化します: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | この系列タイプのセットをグループ化します: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | この系列タイプのセットをグループ化します: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | この系列タイプのセットをグループ化します: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | この系列タイプのセットをグループ化します: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | この系列タイプのセットをグループ化します: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | この系列タイプのセットをグループ化します: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | この系列タイプのセットをグループ化します: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | この系列タイプのセットをグループ化します: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | この系列タイプのセットをグループ化します: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | この系列タイプのセットをグループ化します: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | この系列タイプのセットをグループ化します: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | この系列タイプのセットをグループ化します: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | この系列タイプのセットをグループ化します: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | この系列タイプのセットをグループ化します: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | この系列タイプのセットをグループ化します: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | この系列タイプのセットをグループ化します: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | この系列タイプのセットをグループ化します: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | この系列タイプのセットをグループ化します: { ChartType.Histogram } |
| ParetoLineChart | `54` | この系列タイプのセットをグループ化します: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | この系列タイプのセットをグループ化します: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | この系列タイプのセットをグループ化します: { ChartType.Waterfall } |
| FunnelChart | `57` | この系列タイプのセットをグループ化します: { ChartType.Funnel } |
| TreemapChart | `58` | この系列タイプのセットをグループ化します: { ChartType.Treemap } |
| MapChart | `59` | この系列タイプのセットをグループ化します: { ChartType.Map } |
| SunburstChart | `60` | この系列タイプのセットをグループ化します: { ChartType.Sunburst } |

### 参照

* 名前空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->