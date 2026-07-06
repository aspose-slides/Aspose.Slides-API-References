---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 조합 가능한 시리즈 유형 그룹의 열거형입니다. 각 요소는 하나의 ChartSeriesGroup 내에서 동시에 존재할 수 있는 차트 시리즈 유형 그룹과 관련됩니다. 예를 들어 ChartType.PercentsStackedArea 시리즈는 하나의 ChartSeriesGroup 내에서 ChartType.StackedArea 시리즈와 동시에 존재할 수 없습니다. 그러나 두 개 이상의 ChartType.PercentsStackedArea 시리즈는 하나의 ChartSeriesGroup에 동시에 존재할 수 있습니다 CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. 또한 ChartType.Line 시리즈는 ChartType.LineWithMarkers 시리즈와 동시에 하나의 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup에 존재할 수 있습니다.
type: docs
weight: 1530
url: /ko/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup 열거형

조합 가능한 시리즈 유형 그룹에 대한 열거형입니다. 각 요소는 하나의 ChartSeriesGroup 내에서 동시에 존재할 수 있는 차트 시리즈 유형 그룹을 나타냅니다. 예를 들어: ChartType.PercentsStackedArea 시리즈는 ChartType.StackedArea 시리즈와 동일한 ChartSeriesGroup에 동시에 존재할 수 없습니다. 그러나 두 개 이상의 ChartType.PercentsStackedArea 시리즈는 동일한 ChartSeriesGroup에 동시에 존재할 수 있습니다 (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). 또한 ChartType.Line 시리즈는 ChartType.LineWithMarkers 시리즈와 동시에 하나의 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup에 존재할 수 있습니다.

```csharp
public enum CombinableSeriesTypesGroup
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| AreaChart_Area | `4` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Line3D } |
| StockHighLowClose | `18` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Histogram } |
| ParetoLineChart | `54` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Waterfall } |
| FunnelChart | `57` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Funnel } |
| TreemapChart | `58` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Treemap } |
| MapChart | `59` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Map } |
| SunburstChart | `60` | 이 시리즈 유형 집합을 그룹화합니다: { ChartType.Sunburst } |

### 추가 보기

* 네임스페이스 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 어셈블리 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->