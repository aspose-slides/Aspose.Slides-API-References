---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes für .NET API-Referenz
description: Aufzählung von Gruppen kombinierbarer Serientypen. Jedes Element gehört zu einer Gruppe von Arten von Diagrammserien, die gleichzeitig in einer ChartSeriesGroup bestehen können. Zum Beispiel können die Serie ChartType.PercentsStackedArea nicht gleichzeitig mit der Serie ChartType.StackedArea in einer ChartSeriesGroup vorhanden sein. Aber zwei oder mehr ChartType.PercentsStackedArea können gleichzeitig in einer ChartSeriesGroup CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea sein. Und die Serie ChartType.Line kann gleichzeitig mit der Serie ChartType.LineWithMarkers in einer CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup sein.
type: docs
weight: 1450
url: /de/aspose.slides.charts/combinableseriestypesgroup/
---

## CombinableSeriesTypesGroup Aufzählung

Aufzählung von Gruppen kombinierbarer Serientypen. Jedes Element gehört zu einer Gruppe von Arten von Diagrammserien, die gleichzeitig in einer ChartSeriesGroup bestehen können. Zum Beispiel: Die Serie ChartType.PercentsStackedArea kann nicht gleichzeitig mit der Serie ChartType.StackedArea in einer ChartSeriesGroup vorhanden sein. Aber zwei oder mehr ChartType.PercentsStackedArea können gleichzeitig in einer ChartSeriesGroup sein (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Und die Serie ChartType.Line kann gleichzeitig mit der Serie ChartType.LineWithMarkers in einer CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup sein.

```csharp
public enum CombinableSeriesTypesGroup
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| AreaChart_Area | `4` | Gruppiert diese Menge von Serientypen: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Gruppiert diese Menge von Serientypen: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Gruppiert diese Menge von Serientypen: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Gruppiert diese Menge von Serientypen: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Gruppiert diese Menge von Serientypen: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Gruppiert diese Menge von Serientypen: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Gruppiert diese Menge von Serientypen: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Gruppiert diese Menge von Serientypen: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Gruppiert diese Menge von Serientypen: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Gruppiert diese Menge von Serientypen: { ChartType.Line3D } |
| StockHighLowClose | `18` | Gruppiert diese Menge von Serientypen: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Gruppiert diese Menge von Serientypen: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Gruppiert diese Menge von Serientypen: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Gruppiert diese Menge von Serientypen: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Gruppiert diese Menge von Serientypen: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Gruppiert diese Menge von Serientypen: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Gruppiert diese Menge von Serientypen: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Gruppiert diese Menge von Serientypen: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Gruppiert diese Menge von Serientypen: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Gruppiert diese Menge von Serientypen: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Gruppiert diese Menge von Serientypen: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Gruppiert diese Menge von Serientypen: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Gruppiert diese Menge von Serientypen: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Gruppiert diese Menge von Serientypen: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Gruppiert diese Menge von Serientypen: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Gruppiert diese Menge von Serientypen: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Gruppiert diese Menge von Serientypen: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Gruppiert diese Menge von Serientypen: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Gruppiert diese Menge von Serientypen: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Gruppiert diese Menge von Serientypen: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Gruppiert diese Menge von Serientypen: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Gruppiert diese Menge von Serientypen: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Gruppiert diese Menge von Serientypen: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Gruppiert diese Menge von Serientypen: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Gruppiert diese Menge von Serientypen: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Gruppiert diese Menge von Serientypen: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Gruppiert diese Menge von Serientypen: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Gruppiert diese Menge von Serientypen: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Gruppiert diese Menge von Serientypen: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Gruppiert diese Menge von Serientypen: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Gruppiert diese Menge von Serientypen: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Gruppiert diese Menge von Serientypen: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Gruppiert diese Menge von Serientypen: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Gruppiert diese Menge von Serientypen: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Gruppiert diese Menge von Serientypen: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Gruppiert diese Menge von Serientypen: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Gruppiert diese Menge von Serientypen: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Gruppiert diese Menge von Serientypen: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Gruppiert diese Menge von Serientypen: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Gruppiert diese Menge von Serientypen: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Gruppiert diese Menge von Serientypen: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Gruppiert diese Menge von Serientypen: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Gruppiert diese Menge von Serientypen: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Gruppiert diese Menge von Serientypen: { ChartType.Histogram } |
| ParetoLineChart | `54` | Gruppiert diese Menge von Serientypen: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Gruppiert diese Menge von Serientypen: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Gruppiert diese Menge von Serientypen: { ChartType.Waterfall } |
| FunnelChart | `57` | Gruppiert diese Menge von Serientypen: { ChartType.Funnel } |
| TreemapChart | `58` | Gruppiert diese Menge von Serientypen: { ChartType.Treemap } |
| MapChart | `59` | Gruppiert diese Menge von Serientypen: { ChartType.Map } |
| SunburstChart | `60` | Gruppiert diese Menge von Serientypen: { ChartType.Sunburst } |

### Siehe Auch

* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
