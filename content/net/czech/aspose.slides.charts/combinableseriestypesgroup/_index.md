---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes pro .NET – referenční příručka API
description: Výčet skupin kombinovatelných typů řad. Každý prvek se vztahuje ke skupině typů řad grafu, které mohou současně existovat v jedné ChartSeriesGroup. Například řada ChartType.PercentsStackedArea nemůže být současně s řadou ChartType.StackedArea v jedné ChartSeriesGroup. Ale dvě nebo více řad ChartType.PercentsStackedArea mohou být v jedné ChartSeriesGroup současně (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). A řada ChartType.Line může být s řadou ChartType.LineWithMarkers současně v jedné CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
type: docs
weight: 1530
url: /cs/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeration

Výčet skupin kombinovatelných typů řad. Každý prvek se vztahuje ke skupině typů řad grafu, které mohou současně existovat v jedné ChartSeriesGroup. Například řada ChartType.PercentsStackedArea nemůže být zároveň s řadou ChartType.StackedArea v jedné ChartSeriesGroup. Ale dvě nebo více řad ChartType.PercentsStackedArea mohou být v jedné ChartSeriesGroup současně (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). A řada ChartType.Line může být s řadou ChartType.LineWithMarkers současně v jedné CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

```csharp
public enum CombinableSeriesTypesGroup
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| AreaChart_Area | `4` | Skupinuje tuto sadu typů řad: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Skupinuje tuto sadu typů řad: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Skupinuje tuto sadu typů řad: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Skupinuje tuto sadu typů řad: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Skupinuje tuto sadu typů řad: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Skupinuje tuto sadu typů řad: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Skupinuje tuto sadu typů řad: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Skupinuje tuto sadu typů řad: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Skupinuje tuto sadu typů řad: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Skupinuje tuto sadu typů řad: { ChartType.Line3D } |
| StockHighLowClose | `18` | Skupinuje tuto sadu typů řad: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Skupinuje tuto sadu typů řad: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Skupinuje tuto sadu typů řad: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Skupinuje tuto sadu typů řad: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Skupinuje tuto sadu typů řad: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Skupinuje tuto sadu typů řad: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Skupinuje tuto sadu typů řad: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Skupinuje tuto sadu typů řad: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Skupinuje tuto sadu typů řad: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Skupinuje tuto sadu typů řad: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Skupinuje tuto sadu typů řad: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Skupinuje tuto sadu typů řad: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Skupinuje tuto sadu typů řad: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Skupinuje tuto sadu typů řad: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Skupinuje tuto sadu typů řad: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Skupinuje tuto sadu typů řad: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Skupinuje tuto sadu typů řad: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Skupinuje tuto sadu typů řad: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Skupinuje tuto sadu typů řad: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Skupinuje tuto sadu typů řad: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Skupinuje tuto sadu typů řad: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Skupinuje tuto sadu typů řad: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Skupinuje tuto sadu typů řad: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Skupinuje tuto sadu typů řad: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Skupinuje tuto sadu typů řad: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Skupinuje tuto sadu typů řad: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Skupinuje tuto sadu typů řad: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Skupinuje tuto sadu typů řad: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Skupinuje tuto sadu typů řad: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Skupinuje tuto sadu typů řad: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Skupinuje tuto sadu typů řad: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Skupinuje tuto sadu typů řad: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Skupinuje tuto sadu typů řad: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Skupinuje tuto sadu typů řad: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Skupinuje tuto sadu typů řad: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Skupinuje tuto sadu typů řad: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Skupinuje tuto sadu typů řad: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Skupinuje tuto sadu typů řad: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Skupinuje tuto sadu typů řad: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Skupinuje tuto sadu typů řad: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Skupinuje tuto sadu typů řad: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Skupinuje tuto sadu typů řad: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Skupinuje tuto sadu typů řad: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Skupinuje tuto sadu typů řad: { ChartType.Histogram } |
| ParetoLineChart | `54` | Skupinuje tuto sadu typů řad: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Skupinuje tuto sadu typů řad: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Skupinuje tuto sadu typů řad: { ChartType.Waterfall } |
| FunnelChart | `57` | Skupinuje tuto sadu typů řad: { ChartType.Funnel } |
| TreemapChart | `58` | Skupinuje tuto sadu typů řad: { ChartType.Treemap } |
| MapChart | `59` | Skupinuje tuto sadu typů řad: { ChartType.Map } |
| SunburstChart | `60` | Skupinuje tuto sadu typů řad: { ChartType.Sunburst } |

### Viz také

* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestava [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->