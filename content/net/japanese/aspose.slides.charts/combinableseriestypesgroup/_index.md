---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes for .NET API リファレンス
description: 組み合わせ可能なシリーズタイプのグループの列挙です。各要素は、1つの ChartSeriesGroup 内で同時に保持できるチャートシリーズのタイプのグループに対応します。例えば、ChartType.PercentsStackedArea シリーズは、1つの ChartSeriesGroup 内で ChartType.StackedArea シリーズと同時に存在できません。しかし、2 つ以上の ChartType.PercentsStackedArea は、1つの ChartSeriesGroup 内で同時に存在できます（CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea）。また、ChartType.Line シリーズは ChartType.LineWithMarkers シリーズと同時に 1つの CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup に存在できます。
type: docs
weight: 1540
url: /ja/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup 列挙体

組み合わせ可能なシリーズタイプのグループの列挙です。各要素は、1つの ChartSeriesGroup 内で同時に存在できるチャートシリーズのタイプのグループに対応します。例として、ChartType.PercentsStackedArea シリーズは、1つの ChartSeriesGroup 内で ChartType.StackedArea シリーズと同時に存在できません。しかし、2つ以上の ChartType.PercentsStackedArea は、1つの ChartSeriesGroup 内で同時に存在できます（CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea）。また、ChartType.Line シリーズは、ChartType.LineWithMarkers シリーズと同時に 1つの CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup 内に存在できます。

```csharp
public enum CombinableSeriesTypesGroup
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| AreaChart_Area | `4` | このシリーズタイプの集合をグループ化します: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | このシリーズタイプの集合をグループ化します: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | このシリーズタイプの集合をグループ化します: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | このシリーズタイプの集合をグループ化します: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | このシリーズタイプの集合をグループ化します: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | このシリーズタイプの集合をグループ化します: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | このシリーズタイプの集合をグループ化します: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | このシリーズタイプの集合をグループ化します: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | このシリーズタイプの集合をグループ化します: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | このシリーズタイプの集合をグループ化します: { ChartType.Line3D } |
| StockHighLowClose | `18` | このシリーズタイプの集合をグループ化します: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | このシリーズタイプの集合をグループ化します: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | このシリーズタイプの集合をグループ化します: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | このシリーズタイプの集合をグループ化します: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | このシリーズタイプの集合をグループ化します: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | このシリーズタイプの集合をグループ化します: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | このシリーズタイプの集合をグループ化します: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | このシリーズタイプの集合をグループ化します: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | このシリーズタイプの集合をグループ化します: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | このシリーズタイプの集合をグループ化します: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | このシリーズタイプの集合をグループ化します: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | このシリーズタイプの集合をグループ化します: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | このシリーズタイプの集合をグループ化します: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | このシリーズタイプの集合をグループ化します: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | このシリーズタイプの集合をグループ化します: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | このシリーズタイプの集合をグループ化します: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | このシリーズタイプの集合をグループ化します: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | このシリーズタイプの集合をグループ化します: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | このシリーズタイプの集合をグループ化します: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | このシリーズタイプの集合をグループ化します: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | このシリーズタイプの集合をグループ化します: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | このシリーズタイプの集合をグループ化します: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | このシリーズタイプの集合をグループ化します: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | このシリーズタイプの集合をグループ化します: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | このシリーズタイプの集合をグループ化します: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | このシリーズタイプの集合をグループ化します: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | このシリーズタイプの集合をグループ化します: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | このシリーズタイプの集合をグループ化します: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | このシリーズタイプの集合をグループ化します: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | このシリーズタイプの集合をグループ化します: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | このシリーズタイプの集合をグループ化します: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | このシリーズタイプの集合をグループ化します: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | このシリーズタイプの集合をグループ化します: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | このシリーズタイプの集合をグループ化します: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | このシリーズタイプの集合をグループ化します: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | このシリーズタイプの集合をグループ化します: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | このシリーズタイプの集合をグループ化します: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | このシリーズタイプの集合をグループ化します: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | このシリーズタイプの集合をグループ化します: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | このシリーズタイプの集合をグループ化します: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | このシリーズタイプの集合をグループ化します: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | このシリーズタイプの集合をグループ化します: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | このシリーズタイプの集合をグループ化します: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | このシリーズタイプの集合をグループ化します: { ChartType.Histogram } |
| ParetoLineChart | `54` | このシリーズタイプの集合をグループ化します: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | このシリーズタイプの集合をグループ化します: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | このシリーズタイプの集合をグループ化します: { ChartType.Waterfall } |
| FunnelChart | `57` | このシリーズタイプの集合をグループ化します: { ChartType.Funnel } |
| TreemapChart | `58` | このシリーズタイプの集合をグループ化します: { ChartType.Treemap } |
| MapChart | `59` | このシリーズタイプの集合をグループ化します: { ChartType.Map } |
| SunburstChart | `60` | このシリーズタイプの集合をグループ化します: { ChartType.Sunburst } |

### 参照

* 名前空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->