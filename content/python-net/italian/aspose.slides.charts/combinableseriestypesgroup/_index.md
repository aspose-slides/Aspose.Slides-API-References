---
title: CombinableSeriesTypesGroup enumeration
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumerazione

Enumerazione dei gruppi di tipi di serie combinabili.
Ogni elemento si riferisce a un gruppo di tipi di serie di grafico che possono coesistere simultaneamente in un ChartSeriesGroup.
Ad esempio: le serie ChartType.PercentsStackedArea non possono essere simultaneamente con le serie ChartType.StackedArea in un ChartSeriesGroup. Ma due o più serie ChartType.PercentsStackedArea possono trovarsi in un ChartSeriesGroup contemporaneamente (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). E le serie ChartType.Line possono essere con le serie ChartType.LineWithMarkers simultaneamente in un CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

Il tipo CombinableSeriesTypesGroup espone i seguenti membri:

## Campi

| Campo | Descrizione |
| :- | :- |
| AREA_CHART_AREA | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Area } |
| AREA_CHART_PERCENTS_STACKED_AREA | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.PercentsStackedArea } |
| AREA_CHART_STACKED_AREA | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.StackedArea } |
| AREA_CHART_AREA_3D | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Area3D } |
| AREA_CHART_STACKED_AREA_3D | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.StackedArea3D } |
| AREA_CHART_PERCENTS_STACKED_AREA_3D | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.PercentsStackedArea3D } |
| LINE_CHART_LINE | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Line, ChartType.LineWithMarkers } |
| LINE_CHART_STACKED_LINE | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LINE_CHART_PERCENTS_STACKED_LINE | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| LINE_3D_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Line3D } |
| STOCK_HIGH_LOW_CLOSE | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.HighLowClose } |
| STOCK_OPEN_HIGH_LOW_CLOSE | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.OpenHighLowClose } |
| STOCK_VOLUME_HIGH_LOW_CLOSE | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.VolumeHighLowClose } |
| STOCK_VOLUME_OPEN_HIGH_LOW_CLOSE | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.VolumeOpenHighLowClose } |
| RADAR_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Radar, ChartType.RadarWithMarkers } |
| FILLED_RADAR_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.FilledRadar } |
| SCATTER_STRAIGHT_MARKER | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| SCATTER_SMOOTH_MARKER | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PIE_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Pie, ChartType.ExplodedPie } |
| PIE_3D_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DOUGHNUT_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BAR_CHART_VERT_CLUSTERED | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.ClusteredColumn } |
| BAR_CHART_VERT_STACKED | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.StackedColumn } |
| BAR_CHART_VERT_PERCENTS_STACKED | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.PercentsStackedColumn } |
| BAR_CHART_HORIZ_CLUSTERED | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.ClusteredBar } |
| BAR_CHART_HORIZ_STACKED | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.StackedBar } |
| BAR_CHART_HORIZ_PERCENTS_STACKED | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.PercentsStackedBar } |
| BAR_3D_CHART_VERT | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| BAR_3D_CHART_VERT_CLUSTERED | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_COLUMN_3D | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.PercentsStackedColumn3D } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CONE | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.PercentsStackedCone } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CYLINDER | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.PercentsStackedCylinder } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_PYRAMID | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.PercentsStackedPyramid } |
| BAR_3D_CHART_VERT_STACKED_COLUMN_3D | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.StackedColumn3D } |
| BAR_3D_CHART_VERT_STACKED_CONE | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.StackedCone } |
| BAR_3D_CHART_VERT_STACKED_CYLINDER | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.StackedCylinder } |
| BAR_3D_CHART_VERT_STACKED_PYRAMID | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.StackedPyramid } |
| BAR_3D_CHART_HORIZ_CLUSTERED | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_STACKED_BAR_3D | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.StackedBar3D } |
| BAR_3D_CHART_HORIZ_STACKED_CONE | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.StackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_STACKED_CYLINDER | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.StackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_STACKED_PYRAMID | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.StackedHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_BAR_3D | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.PercentsStackedBar3D } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CONE | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.PercentsStackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CYLINDER | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.PercentsStackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_PYRAMID | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.PercentsStackedHorizontalPyramid } |
| BAR_OF_PIE_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.BarOfPie } |
| PIE_OF_PIE_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.PieOfPie } |
| SURFACE_CHART_CONTOUR | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Contour } |
| SURFACE_CHART_WIREFRAME_CONTOUR | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.WireframeContour } |
| SURFACE_CHART_SURFACE_3D | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Surface3D } |
| SURFACE_CHART_WIREFRAME_SURFACE_3D | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.WireframeSurface3D } |
| BUBBLE_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Bubble, ChartType.BubbleWith3D } |
| HISTOGRAM_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Histogram } |
| PARETO_LINE_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.ParetoLine } |
| BOX_AND_WHISKER_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.BoxAndWhisker } |
| WATERFALL_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Waterfall } |
| FUNNEL_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Funnel } |
| TREEMAP_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Treemap } |
| MAP_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Map } |
| SUNBURST_CHART | Raggruppa questo insieme di tipi di serie:<br/>            { ChartType.Sunburst } |

### Vedi anche
* modulo [`aspose.slides.charts`](/slides/python-net/it/aspose.slides.charts)
* libreria [`Aspose.Slides`](/slides/python-net)