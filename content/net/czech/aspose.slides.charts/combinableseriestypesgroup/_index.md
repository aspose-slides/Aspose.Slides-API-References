---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes pro .NET API Reference
description: Výčet skupin kombinovatelných typů řad. Každý prvek se vztahuje ke skupině typů řad grafu, které mohou současně existovat v jednom ChartSeriesGroup. Například řada ChartType.PercentsStackedArea nemůže být současně s řadou ChartType.StackedArea v jednom ChartSeriesGroup. Ale dvě nebo více řad ChartType.PercentsStackedArea mohou být v jednom ChartSeriesGroup současně CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. A řada ChartType.Line může být se řadou ChartType.LineWithMarkers současně v jednom CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
type: docs
weight: 1510
url: /cs/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumerace

Výčet skupin kombinovatelných typů řad. Každý prvek se vztahuje ke skupině typů řad grafu, které mohou současně existovat v jednom ChartSeriesGroup. Například: řada ChartType.PercentsStackedArea nemůže být současně s řadou ChartType.StackedArea v jednom ChartSeriesGroup. Ale dvě nebo více řad ChartType.PercentsStackedArea mohou být v jednom ChartSeriesGroup současně (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). A řada ChartType.Line může být s řadou ChartType.LineWithMarkers současně v jednom CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

```csharp
public enum CombinableSeriesTypesGroup
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| AreaChart_Area | `4` | Skupina tohoto souboru typů řad: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Skupina tohoto souboru typů řad: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Skupina tohoto souboru typů řad: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Skupina tohoto souboru typů řad: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Skupina tohoto souboru typů řad: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Skupina tohoto souboru typů řad: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Skupina tohoto souboru typů řad: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Skupina tohoto souboru typů řad: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Skupina tohoto souboru typů řad: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Skupina tohoto souboru typů řad: { ChartType.Line3D } |
| StockHighLowClose | `18` | Skupina tohoto souboru typů řad: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Skupina tohoto souboru typů řad: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Skupina tohoto souboru typů řad: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Skupina tohoto souboru typů řad: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Skupina tohoto souboru typů řad: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Skupina tohoto souboru typů řad: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Skupina tohoto souboru typů řad: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Skupina tohoto souboru typů řad: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Skupina tohoto souboru typů řad: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Skupina tohoto souboru typů řad: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Skupina tohoto souboru typů řad: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Skupina tohoto souboru typů řad: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Skupina tohoto souboru typů řad: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Skupina tohoto souboru typů řad: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Skupina tohoto souboru typů řad: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Skupina tohoto souboru typů řad: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Skupina tohoto souboru typů řad: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Skupina tohoto souboru typů řad: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Skupina tohoto souboru typů řad: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Skupina tohoto souboru typů řad: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Skupina tohoto souboru typů řad: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Skupina tohoto souboru typů řad: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Skupina tohoto souboru typů řad: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Skupina tohoto souboru typů řad: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Skupina tohoto souboru typů řad: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Skupina tohoto souboru typů řad: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Skupina tohoto souboru typů řad: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Skupina tohoto souboru typů řad: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Skupina tohoto souboru typů řad: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Skupina tohoto souboru typů řad: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Skupina tohoto souboru typů řad: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Skupina tohoto souboru typů řad: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Skupina tohoto souboru typů řad: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Skupina tohoto souboru typů řad: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Skupina tohoto souboru typů řad: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Skupina tohoto souboru typů řad: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Skupina tohoto souboru typů řad: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Skupina tohoto souboru typů řad: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Skupina tohoto souboru typů řad: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Skupina tohoto souboru typů řad: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Skupina tohoto souboru typů řad: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Skupina tohoto souboru typů řad: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Skupina tohoto souboru typů řad: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Skupina tohoto souboru typů řad: { ChartType.Histogram } |
| ParetoLineChart | `54` | Skupina tohoto souboru typů řad: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Skupina tohoto souboru typů řad: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Skupina tohoto souboru typů řad: { ChartType.Waterfall } |
| FunnelChart | `57` | Skupina tohoto souboru typů řad: { ChartType.Funnel } |
| TreemapChart | `58` | Skupina tohoto souboru typů řad: { ChartType.Treemap } |
| MapChart | `59` | Skupina tohoto souboru typů řad: { ChartType.Map } |
| SunburstChart | `60` | Skupina tohoto souboru typů řad: { ChartType.Sunburst } |

### Viz také

* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->