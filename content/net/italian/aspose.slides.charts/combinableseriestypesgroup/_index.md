---
title: CombinableSeriesTypesGroup
second_title: Riferimento API Aspose.Sildes per .NET
description: Enumerazione dei gruppi di tipi di serie combinabili. Ogni elemento si riferisce a un gruppo di tipi di serie di grafico che possono persistere simultaneamente in un ChartSeriesGroup. Per esempio, le serie ChartType.PercentsStackedArea non possono essere simultaneamente con le serie ChartType.StackedArea in un ChartSeriesGroup. Ma due o più serie ChartType.PercentsStackedArea possono essere in un ChartSeriesGroup simultaneamente CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. E le serie ChartType.Line possono essere con le serie ChartType.LineWithMarkers simultaneamente in un CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
type: docs
weight: 1510
url: /it/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumerazione

Enumerazione dei gruppi di tipi di serie combinabili. Ogni elemento si riferisce a un gruppo di tipi di serie di grafico che possono persistere simultaneamente in un ChartSeriesGroup. Per esempio: le serie ChartType.PercentsStackedArea non possono essere simultaneamente con le serie ChartType.StackedArea in un ChartSeriesGroup. Ma due o più serie ChartType.PercentsStackedArea possono essere in un ChartSeriesGroup contemporaneamente (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). E le serie ChartType.Line possono essere con le serie ChartType.LineWithMarkers simultaneamente in un CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

```csharp
public enum CombinableSeriesTypesGroup
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| AreaChart_Area | `4` | Raggruppa questo insieme di tipi di serie: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Raggruppa questo insieme di tipi di serie: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Raggruppa questo insieme di tipi di serie: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Raggruppa questo insieme di tipi di serie: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Raggruppa questo insieme di tipi di serie: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Raggruppa questo insieme di tipi di serie: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Raggruppa questo insieme di tipi di serie: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Raggruppa questo insieme di tipi di serie: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Raggruppa questo insieme di tipi di serie: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Raggruppa questo insieme di tipi di serie: { ChartType.Line3D } |
| StockHighLowClose | `18` | Raggruppa questo insieme di tipi di serie: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Raggruppa questo insieme di tipi di serie: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Raggruppa questo insieme di tipi di serie: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Raggruppa questo insieme di tipi di serie: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Raggruppa questo insieme di tipi di serie: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Raggruppa questo insieme di tipi di serie: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Raggruppa questo insieme di tipi di serie: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Raggruppa questo insieme di tipi di serie: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Raggruppa questo insieme di tipi di serie: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Raggruppa questo insieme di tipi di serie: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Raggruppa questo insieme di tipi di serie: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Raggruppa questo insieme di tipi di serie: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Raggruppa questo insieme di tipi di serie: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Raggruppa questo insieme di tipi di serie: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Raggruppa questo insieme di tipi di serie: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Raggruppa questo insieme di tipi di serie: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Raggruppa questo insieme di tipi di serie: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Raggruppa questo insieme di tipi di serie: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Raggruppa questo insieme di tipi di serie: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Raggruppa questo insieme di tipi di serie: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Raggruppa questo insieme di tipi di serie: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Raggruppa questo insieme di tipi di serie: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Raggruppa questo insieme di tipi di serie: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Raggruppa questo insieme di tipi di serie: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Raggruppa questo insieme di tipi di serie: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Raggruppa questo insieme di tipi di serie: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Raggruppa questo insieme di tipi di serie: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Raggruppa questo insieme di tipi di serie: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Raggruppa questo insieme di tipi di serie: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Raggruppa questo insieme di tipi di serie: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Raggruppa questo insieme di tipi di serie: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Raggruppa questo insieme di tipi di serie: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Raggruppa questo insieme di tipi di serie: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Raggruppa questo insieme di tipi di serie: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Raggruppa questo insieme di tipi di serie: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Raggruppa questo insieme di tipi di serie: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Raggruppa questo insieme di tipi di serie: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Raggruppa questo insieme di tipi di serie: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Raggruppa questo insieme di tipi di serie: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Raggruppa questo insieme di tipi di serie: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Raggruppa questo insieme di tipi di serie: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Raggruppa questo insieme di tipi di serie: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Raggruppa questo insieme di tipi di serie: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Raggruppa questo insieme di tipi di serie: { ChartType.Histogram } |
| ParetoLineChart | `54` | Raggruppa questo insieme di tipi di serie: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Raggruppa questo insieme di tipi di serie: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Raggruppa questo insieme di tipi di serie: { ChartType.Waterfall } |
| FunnelChart | `57` | Raggruppa questo insieme di tipi di serie: { ChartType.Funnel } |
| TreemapChart | `58` | Raggruppa questo insieme di tipi di serie: { ChartType.Treemap } |
| MapChart | `59` | Raggruppa questo insieme di tipi di serie: { ChartType.Map } |
| SunburstChart | `60` | Raggruppa questo insieme di tipi di serie: { ChartType.Sunburst } |

### Vedi anche

* spazio dei nomi [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->