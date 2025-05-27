---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes for .NET API Referenz
description: Aufzählung von Gruppen kombinierbarer Serientypen. Jedes Element bezieht sich auf eine Gruppe von Typen von Diagrammserien, die gleichzeitig in einer ChartSeriesGroup bestehen können. Zum Beispiel kann die Serie ChartType.PercentsStackedArea nicht gleichzeitig mit der Serie ChartType.StackedArea in einer ChartSeriesGroup sein. Aber zwei oder mehr ChartType.PercentsStackedArea können gleichzeitig in einer ChartSeriesGroup CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea sein. Und die ChartType.Line-Serie kann gleichzeitig mit der ChartType.LineWithMarkers-Serie in einer CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup sein.
type: docs
weight: 1450
url: /de/aspose.slides.charts/combinableseriestypesgroup/
---

## CombinableSeriesTypesGroup Aufzählung

Aufzählung von Gruppen kombinierbarer Serientypen. Jedes Element bezieht sich auf eine Gruppe von Typen von Diagrammserien, die gleichzeitig in einer ChartSeriesGroup bestehen können. Zum Beispiel: Die Serie ChartType.PercentsStackedArea kann nicht gleichzeitig mit der Serie ChartType.StackedArea in einer ChartSeriesGroup sein. Aber zwei oder mehr ChartType.PercentsStackedArea können gleichzeitig in einer ChartSeriesGroup (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea) sein. Und die ChartType.Line-Serie kann gleichzeitig mit der ChartType.LineWithMarkers-Serie in einer CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup sein.

```csharp
public enum CombinableSeriesTypesGroup
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| AreaChart_Area | `4` | Gruppiert dieses Set von Serientypen: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Gruppiert dieses Set von Serientypen: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Gruppiert dieses Set von Serientypen: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Gruppiert dieses Set von Serientypen: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Gruppiert dieses Set von Serientypen: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Gruppiert dieses Set von Serientypen: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Gruppiert dieses Set von Serientypen: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Gruppiert dieses Set von Serientypen: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Gruppiert dieses Set von Serientypen: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Gruppiert dieses Set von Serientypen: { ChartType.Line3D } |
| StockHighLowClose | `18` | Gruppiert dieses Set von Serientypen: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Gruppiert dieses Set von Serientypen: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Gruppiert dieses Set von Serientypen: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Gruppiert dieses Set von Serientypen: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Gruppiert dieses Set von Serientypen: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Gruppiert dieses Set von Serientypen: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Gruppiert dieses Set von Serientypen: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Gruppiert dieses Set von Serientypen: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Gruppiert dieses Set von Serientypen: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Gruppiert dieses Set von Serientypen: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Gruppiert dieses Set von Serientypen: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Gruppiert dieses Set von Serientypen: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Gruppiert dieses Set von Serientypen: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Gruppiert dieses Set von Serientypen: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Gruppiert dieses Set von Serientypen: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Gruppiert dieses Set von Serientypen: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Gruppiert dieses Set von Serientypen: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Gruppiert dieses Set von Serientypen: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Gruppiert dieses Set von Serientypen: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Gruppiert dieses Set von Serientypen: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Gruppiert dieses Set von Serientypen: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Gruppiert dieses Set von Serientypen: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Gruppiert dieses Set von Serientypen: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Gruppiert dieses Set von Serientypen: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Gruppiert dieses Set von Serientypen: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Gruppiert dieses Set von Serientypen: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Gruppiert dieses Set von Serientypen: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Gruppiert dieses Set von Serientypen: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Gruppiert dieses Set von Serientypen: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Gruppiert dieses Set von Serientypen: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Gruppiert dieses Set von Serientypen: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Gruppiert dieses Set von Serientypen: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Gruppiert dieses Set von Serientypen: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Gruppiert dieses Set von Serientypen: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Gruppiert dieses Set von Serientypen: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Gruppiert dieses Set von Serientypen: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Gruppiert dieses Set von Serientypen: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Gruppiert dieses Set von Serientypen: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Gruppiert dieses Set von Serientypen: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Gruppiert dieses Set von Serientypen: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Gruppiert dieses Set von Serientypen: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Gruppiert dieses Set von Serientypen: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Gruppiert dieses Set von Serientypen: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Gruppiert dieses Set von Serientypen: { ChartType.Histogram } |
| ParetoLineChart | `54` | Gruppiert dieses Set von Serientypen: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Gruppiert dieses Set von Serientypen: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Gruppiert dieses Set von Serientypen: { ChartType.Waterfall } |
| FunnelChart | `57` | Gruppiert dieses Set von Serientypen: { ChartType.Funnel } |
| TreemapChart | `58` | Gruppiert dieses Set von Serientypen: { ChartType.Treemap } |
| MapChart | `59` | Gruppiert dieses Set von Serientypen: { ChartType.Map } |
| SunburstChart | `60` | Gruppiert dieses Set von Serientypen: { ChartType.Sunburst } |

### Siehe Auch

* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->