---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides für .NET-API-Referenz
description: Aufzählung von Gruppen kombinierbarer Reihentypen. Jedes Element bezieht sich auf eine Gruppe von Arten von Diagrammreihen die gleichzeitig in einer ChartSeriesGroup bestehen können. Zum Beispiel ChartType.PercentsStackedAreaReihen können nicht gleichzeitig mit ChartType.StackedAreaReihen in einer ChartSeriesGroup sein. Aber zwei oder mehr ChartType.PercentsStackedArea können gleichzeitig in einer ChartSeriesGroup sein CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. Und ChartType.LineSerien können mit ChartType.LineWithMarkersSerien gleichzeitig in einer CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup. sein.
type: docs
weight: 1410
url: /de/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeration

Aufzählung von Gruppen kombinierbarer Reihentypen. Jedes Element bezieht sich auf eine Gruppe von Arten von Diagrammreihen, die gleichzeitig in einer ChartSeriesGroup bestehen können. Zum Beispiel: ChartType.PercentsStackedArea-Reihen können nicht gleichzeitig mit ChartType.StackedArea-Reihen in einer ChartSeriesGroup sein. Aber zwei oder mehr ChartType.PercentsStackedArea können gleichzeitig in einer ChartSeriesGroup sein (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Und ChartType.Line-Serien können mit ChartType.LineWithMarkers-Serien gleichzeitig in einer CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup. sein.

```csharp
public enum CombinableSeriesTypesGroup
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| AreaChart_Area | `4` | Gruppiert diesen Satz von Reihentypen: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Gruppiert diesen Satz von Reihentypen: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Gruppiert diesen Satz von Reihentypen: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Gruppiert diesen Satz von Reihentypen: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Gruppiert diesen Satz von Reihentypen: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Gruppiert diesen Satz von Reihentypen: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Gruppiert diesen Satz von Reihentypen: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Gruppiert diesen Satz von Reihentypen: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Gruppiert diesen Satz von Reihentypen: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Gruppiert diesen Satz von Reihentypen: { ChartType.Line3D } |
| StockHighLowClose | `18` | Gruppiert diesen Satz von Reihentypen: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Gruppiert diesen Satz von Reihentypen: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Gruppiert diesen Satz von Reihentypen: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Gruppiert diesen Satz von Reihentypen: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Gruppiert diesen Satz von Reihentypen: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Gruppiert diesen Satz von Reihentypen: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Gruppiert diesen Satz von Reihentypen: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Gruppiert diesen Satz von Reihentypen: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Gruppiert diesen Satz von Reihentypen: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Gruppiert diesen Satz von Reihentypen: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Gruppiert diesen Satz von Reihentypen: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Gruppiert diesen Satz von Reihentypen: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Gruppiert diesen Satz von Reihentypen: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Gruppiert diesen Satz von Reihentypen: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Gruppiert diesen Satz von Reihentypen: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Gruppiert diesen Satz von Reihentypen: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Gruppiert diesen Satz von Reihentypen: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Gruppiert diesen Satz von Reihentypen: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Gruppiert diesen Satz von Reihentypen: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Gruppiert diesen Satz von Reihentypen: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Gruppiert diesen Satz von Reihentypen: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Gruppiert diesen Satz von Reihentypen: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Gruppiert diesen Satz von Reihentypen: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Gruppiert diesen Satz von Reihentypen: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Gruppiert diesen Satz von Reihentypen: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Gruppiert diesen Satz von Reihentypen: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Gruppiert diesen Satz von Reihentypen: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Gruppiert diesen Satz von Reihentypen: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Gruppiert diesen Satz von Reihentypen: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Gruppiert diesen Satz von Reihentypen: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Gruppiert diesen Satz von Reihentypen: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Gruppiert diesen Satz von Reihentypen: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Gruppiert diesen Satz von Reihentypen: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Gruppiert diesen Satz von Reihentypen: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Gruppiert diesen Satz von Reihentypen: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Gruppiert diesen Satz von Reihentypen: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Gruppiert diesen Satz von Reihentypen: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Gruppiert diesen Satz von Reihentypen: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Gruppiert diesen Satz von Reihentypen: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Gruppiert diesen Satz von Reihentypen: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Gruppiert diesen Satz von Reihentypen: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Gruppiert diesen Satz von Reihentypen: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Gruppiert diesen Satz von Reihentypen: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Gruppiert diesen Satz von Reihentypen: { ChartType.Histogram } |
| ParetoLineChart | `54` | Gruppiert diesen Satz von Reihentypen: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Gruppiert diesen Satz von Reihentypen: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Gruppiert diesen Satz von Reihentypen: { ChartType.Waterfall } |
| FunnelChart | `57` | Gruppiert diesen Satz von Reihentypen: { ChartType.Funnel } |
| TreemapChart | `58` | Gruppiert diesen Satz von Reihentypen: { ChartType.Treemap } |
| MapChart | `59` | Gruppiert diesen Satz von Reihentypen: { ChartType.Map } |
| SunburstChart | `60` | Gruppiert diesen Satz von Reihentypen: { ChartType.Sunburst } |

### Siehe auch

* namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
