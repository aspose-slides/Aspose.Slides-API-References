---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes für .NET API-Referenz
description: Enumeration von Gruppen kombinierbarer Serien-Typen. Jedes Element bezieht sich auf eine Gruppe von Diagramm-Serientypen, die gleichzeitig in einer ChartSeriesGroup bestehen können. Zum Beispiel können ChartType.PercentsStackedArea-Serien nicht gleichzeitig mit ChartType.StackedArea-Serien in einer ChartSeriesGroup vorkommen. Aber zwei oder mehr ChartType.PercentsStackedArea-Serien können gleichzeitig in einer ChartSeriesGroup sein (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Und ChartType.Line-Serien können gleichzeitig mit ChartType.LineWithMarkers-Serien in einer CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup verwendet werden.
type: docs
weight: 1530
url: /de/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup Aufzählung

Aufzählung von Gruppen kombinierbarer Serien-Typen. Jedes Element bezieht sich auf eine Gruppe von Diagramm-Serientypen, die gleichzeitig in einer ChartSeriesGroup bestehen können. Zum Beispiel: ChartType.PercentsStackedArea-Serien können nicht gleichzeitig mit ChartType.StackedArea-Serien in einer ChartSeriesGroup vorkommen. Aber zwei oder mehr ChartType.PercentsStackedArea-Serien können gleichzeitig in einer ChartSeriesGroup sein (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Und ChartType.Line-Serien können gleichzeitig mit ChartType.LineWithMarkers-Serien in einer CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup verwendet werden.

```csharp
public enum CombinableSeriesTypesGroup
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| AreaChart_Area | `4` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Gruppiert diesen Satz von Serien-Typen: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Gruppiert diesen Satz von Serien-Typen: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Gruppiert diesen Satz von Serien-Typen: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Gruppiert diesen Satz von Serien-Typen: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Gruppiert diesen Satz von Serien-Typen: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Gruppiert diesen Satz von Serien-Typen: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Line3D } |
| StockHighLowClose | `18` | Gruppiert diesen Satz von Serien-Typen: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Gruppiert diesen Satz von Serien-Typen: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Gruppiert diesen Satz von Serien-Typen: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Gruppiert diesen Satz von Serien-Typen: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Gruppiert diesen Satz von Serien-Typen: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Gruppiert diesen Satz von Serien-Typen: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Gruppiert diesen Satz von Serien-Typen: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Gruppiert diesen Satz von Serien-Typen: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Gruppiert diesen Satz von Serien-Typen: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Gruppiert diesen Satz von Serien-Typen: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Gruppiert diesen Satz von Serien-Typen: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Gruppiert diesen Satz von Serien-Typen: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Gruppiert diesen Satz von Serien-Typen: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Gruppiert diesen Satz von Serien-Typen: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Gruppiert diesen Satz von Serien-Typen: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Gruppiert diesen Satz von Serien-Typen: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Gruppiert diesen Satz von Serien-Typen: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Gruppiert diesen Satz von Serien-Typen: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Gruppiert diesen Satz von Serien-Typen: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Gruppiert diesen Satz von Serien-Typen: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Gruppiert diesen Satz von Serien-Typen: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Gruppiert diesen Satz von Serien-Typen: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Gruppiert diesen Satz von Serien-Typen: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Gruppiert diesen Satz von Serien-Typen: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Gruppiert diesen Satz von Serien-Typen: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Gruppiert diesen Satz von Serien-Typen: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Gruppiert diesen Satz von Serien-Typen: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Gruppiert diesen Satz von Serien-Typen: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Gruppiert diesen Satz von Serien-Typen: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Gruppiert diesen Satz von Serien-Typen: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Gruppiert diesen Satz von Serien-Typen: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Gruppiert diesen Satz von Serien-Typen: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Gruppiert diesen Satz von Serien-Typen: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Gruppiert diesen Satz von Serien-Typen: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Gruppiert diesen Satz von Serien-Typen: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Histogram } |
| ParetoLineChart | `54` | Gruppiert diesen Satz von Serien-Typen: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Gruppiert diesen Satz von Serien-Typen: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Waterfall } |
| FunnelChart | `57` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Funnel } |
| TreemapChart | `58` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Treemap } |
| MapChart | `59` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Map } |
| SunburstChart | `60` | Gruppiert diesen Satz von Serien-Typen: { ChartType.Sunburst } |

### Siehe auch

* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->