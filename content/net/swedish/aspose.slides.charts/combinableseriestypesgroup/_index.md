---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes för .NET API-referens
description: Enumeration av grupper av kombinerbara serietyper. Varje element hänför sig till en grupp av typer av diagramserier som kan finnas samtidigt i en ChartSeriesGroup. Till exempel kan ChartType.PercentsStackedArea series inte vara samtidigt med ChartType.StackedArea series i en ChartSeriesGroup. Men två eller fler ChartType.PercentsStackedArea kan vara i en ChartSeriesGroup samtidigt CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. Och ChartType.Line series kan vara med ChartType.LineWithMarkers series samtidigt i en CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
type: docs
weight: 1510
url: /sv/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeration

Enumeration av grupper av kombinerbara serietyper. Varje element hänför sig till en grupp av typer av diagramserier som kan existera samtidigt i en ChartSeriesGroup. Till exempel: ChartType.PercentsStackedArea-serier kan inte vara samtidigt med ChartType.StackedArea-serier i en ChartSeriesGroup. Men två eller fler ChartType.PercentsStackedArea kan vara i en ChartSeriesGroup samtidigt (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Och ChartType.Line-serier kan vara med ChartType.LineWithMarkers-serier samtidigt i en CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

```csharp
public enum CombinableSeriesTypesGroup
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| AreaChart_Area | `4` | Grupperar denna uppsättning serietyper: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Grupperar denna uppsättning serietyper: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Grupperar denna uppsättning serietyper: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Grupperar denna uppsättning serietyper: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Grupperar denna uppsättning serietyper: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Grupperar denna uppsättning serietyper: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Grupperar denna uppsättning serietyper: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Grupperar denna uppsättning serietyper: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Grupperar denna uppsättning serietyper: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Grupperar denna uppsättning serietyper: { ChartType.Line3D } |
| StockHighLowClose | `18` | Grupperar denna uppsättning serietyper: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Grupperar denna uppsättning serietyper: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Grupperar denna uppsättning serietyper: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Grupperar denna uppsättning serietyper: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Grupperar denna uppsättning serietyper: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Grupperar denna uppsättning serietyper: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Grupperar denna uppsättning serietyper: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Grupperar denna uppsättning serietyper: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Grupperar denna uppsättning serietyper: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Grupperar denna uppsättning serietyper: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Grupperar denna uppsättning serietyper: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Grupperar denna uppsättning serietyper: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Grupperar denna uppsättning serietyper: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Grupperar denna uppsättning serietyper: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Grupperar denna uppsättning serietyper: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Grupperar denna uppsättning serietyper: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Grupperar denna uppsättning serietyper: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Grupperar denna uppsättning serietyper: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Grupperar denna uppsättning serietyper: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Grupperar denna uppsättning serietyper: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Grupperar denna uppsättning serietyper: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Grupperar denna uppsättning serietyper: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Grupperar denna uppsättning serietyper: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Grupperar denna uppsättning serietyper: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Grupperar denna uppsättning serietyper: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Grupperar denna uppsättning serietyper: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Grupperar denna uppsättning serietyper: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Grupperar denna uppsättning serietyper: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Grupperar denna uppsättning serietyper: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Grupperar denna uppsättning serietyper: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Grupperar denna uppsättning serietyper: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Grupperar denna uppsättning serietyper: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Grupperar denna uppsättning serietyper: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Grupperar denna uppsättning serietyper: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Grupperar denna uppsättning serietyper: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Grupperar denna uppsättning serietyper: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Grupperar denna uppsättning serietyper: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Grupperar denna uppsättning serietyper: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Grupperar denna uppsättning serietyper: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Grupperar denna uppsättning serietyper: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Grupperar denna uppsättning serietyper: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Grupperar denna uppsättning serietyper: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Grupperar denna uppsättning serietyper: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Grupperar denna uppsättning serietyper: { ChartType.Histogram } |
| ParetoLineChart | `54` | Grupperar denna uppsättning serietyper: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Grupperar denna uppsättning serietyper: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Grupperar denna uppsättning serietyper: { ChartType.Waterfall } |
| FunnelChart | `57` | Grupperar denna uppsättning serietyper: { ChartType.Funnel } |
| TreemapChart | `58` | Grupperar denna uppsättning serietyper: { ChartType.Treemap } |
| MapChart | `59` | Grupperar denna uppsättning serietyper: { ChartType.Map } |
| SunburstChart | `60` | Grupperar denna uppsättning serietyper: { ChartType.Sunburst } |

### Se även

* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->