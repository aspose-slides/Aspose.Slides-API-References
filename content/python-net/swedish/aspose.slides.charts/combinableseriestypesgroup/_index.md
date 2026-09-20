---
title: CombinableSeriesTypesGroup enumeration
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup uppräkning

Uppräkning av grupper av kombinerbara serietyper.
            Varje element relaterar till en grupp av typer av diagramserier som kan finnas samtidigt i en ChartSeriesGroup.
            Till exempel: ChartType.PercentsStackedArea serier kan inte vara samtidigt med ChartType.StackedArea serier 
            i en ChartSeriesGroup. Men två eller fler ChartType.PercentsStackedArea kan vara i en ChartSeriesGroup 
            samtidigt (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Och ChartType.Line serier kan vara 
            med ChartType.LineWithMarkers serier samtidigt i en CombinableSeriesTypesGroup.LineChart_Line 
            ChartSeriesGroup.

The CombinableSeriesTypesGroup type exposes the following members:

## Fält

| Fält | Beskrivning |
| :- | :- |
| AREA_CHART_AREA | Grupperar detta set av serietyper:<br/>            { ChartType.Area } |
| AREA_CHART_PERCENTS_STACKED_AREA | Grupperar detta set av serietyper:<br/>            { ChartType.PercentsStackedArea } |
| AREA_CHART_STACKED_AREA | Grupperar detta set av serietyper:<br/>            { ChartType.StackedArea } |
| AREA_CHART_AREA_3D | Grupperar detta set av serietyper:<br/>            { ChartType.Area3D } |
| AREA_CHART_STACKED_AREA_3D | Grupperar detta set av serietyper:<br/>            { ChartType.StackedArea3D } |
| AREA_CHART_PERCENTS_STACKED_AREA_3D | Grupperar detta set av serietyper:<br/>            { ChartType.PercentsStackedArea3D } |
| LINE_CHART_LINE | Grupperar detta set av serietyper:<br/>            { ChartType.Line, ChartType.LineWithMarkers } |
| LINE_CHART_STACKED_LINE | Grupperar detta set av serietyper:<br/>            { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LINE_CHART_PERCENTS_STACKED_LINE | Grupperar detta set av serietyper:<br/>            { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| LINE_3D_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.Line3D } |
| STOCK_HIGH_LOW_CLOSE | Grupperar detta set av serietyper:<br/>            { ChartType.HighLowClose } |
| STOCK_OPEN_HIGH_LOW_CLOSE | Grupperar detta set av serietyper:<br/>            { ChartType.OpenHighLowClose } |
| STOCK_VOLUME_HIGH_LOW_CLOSE | Grupperar detta set av serietyper:<br/>            { ChartType.VolumeHighLowClose } |
| STOCK_VOLUME_OPEN_HIGH_LOW_CLOSE | Grupperar detta set av serietyper:<br/>            { ChartType.VolumeOpenHighLowClose } |
| RADAR_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.Radar, ChartType.RadarWithMarkers } |
| FILLED_RADAR_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.FilledRadar } |
| SCATTER_STRAIGHT_MARKER | Grupperar detta set av serietyper:<br/>            { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| SCATTER_SMOOTH_MARKER | Grupperar detta set av serietyper:<br/>            { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PIE_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.Pie, ChartType.ExplodedPie } |
| PIE_3D_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DOUGHNUT_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BAR_CHART_VERT_CLUSTERED | Grupperar detta set av serietyper:<br/>            { ChartType.ClusteredColumn } |
| BAR_CHART_VERT_STACKED | Grupperar detta set av serietyper:<br/>            { ChartType.StackedColumn } |
| BAR_CHART_VERT_PERCENTS_STACKED | Grupperar detta set av serietyper:<br/>            { ChartType.PercentsStackedColumn } |
| BAR_CHART_HORIZ_CLUSTERED | Grupperar detta set av serietyper:<br/>            { ChartType.ClusteredBar } |
| BAR_CHART_HORIZ_STACKED | Grupperar detta set av serietyper:<br/>            { ChartType.StackedBar } |
| BAR_CHART_HORIZ_PERCENTS_STACKED | Grupperar detta set av serietyper:<br/>            { ChartType.PercentsStackedBar } |
| BAR_3D_CHART_VERT | Grupperar detta set av serietyper:<br/>            { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| BAR_3D_CHART_VERT_CLUSTERED | Grupperar detta set av serietyper:<br/>            { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_COLUMN_3D | Grupperar detta set av serietyper:<br/>            { ChartType.PercentsStackedColumn3D } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CONE | Grupperar detta set av serietyper:<br/>            { ChartType.PercentsStackedCone } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CYLINDER | Grupperar detta set av serietyper:<br/>            { ChartType.PercentsStackedCylinder } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_PYRAMID | Grupperar detta set av serietyper:<br/>            { ChartType.PercentsStackedPyramid } |
| BAR_3D_CHART_VERT_STACKED_COLUMN_3D | Grupperar detta set av serietyper:<br/>            { ChartType.StackedColumn3D } |
| BAR_3D_CHART_VERT_STACKED_CONE | Grupperar detta set av serietyper:<br/>            { ChartType.StackedCone } |
| BAR_3D_CHART_VERT_STACKED_CYLINDER | Grupperar detta set av serietyper:<br/>            { ChartType.StackedCylinder } |
| BAR_3D_CHART_VERT_STACKED_PYRAMID | Grupperar detta set av serietyper:<br/>            { ChartType.StackedPyramid } |
| BAR_3D_CHART_HORIZ_CLUSTERED | Grupperar detta set av serietyper:<br/>            { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_STACKED_BAR_3D | Grupperar detta set av serietyper:<br/>            { ChartType.StackedBar3D } |
| BAR_3D_CHART_HORIZ_STACKED_CONE | Grupperar detta set av serietyper:<br/>            { ChartType.StackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_STACKED_CYLINDER | Grupperar detta set av serietyper:<br/>            { ChartType.StackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_STACKED_PYRAMID | Grupperar detta set av serietyper:<br/>            { ChartType.StackedHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_BAR_3D | Grupperar detta set av serietyper:<br/>            { ChartType.PercentsStackedBar3D } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CONE | Grupperar detta set av serietyper:<br/>            { ChartType.PercentsStackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CYLINDER | Grupperar detta set av serietyper:<br/>            { ChartType.PercentsStackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_PYRAMID | Grupperar detta set av serietyper:<br/>            { ChartType.PercentsStackedHorizontalPyramid } |
| BAR_OF_PIE_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.BarOfPie } |
| PIE_OF_PIE_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.PieOfPie } |
| SURFACE_CHART_CONTOUR | Grupperar detta set av serietyper:<br/>            { ChartType.Contour } |
| SURFACE_CHART_WIREFRAME_CONTOUR | Grupperar detta set av serietyper:<br/>            { ChartType.WireframeContour } |
| SURFACE_CHART_SURFACE_3D | Grupperar detta set av serietyper:<br/>            { ChartType.Surface3D } |
| SURFACE_CHART_WIREFRAME_SURFACE_3D | Grupperar detta set av serietyper:<br/>            { ChartType.WireframeSurface3D } |
| BUBBLE_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.Bubble, ChartType.BubbleWith3D } |
| HISTOGRAM_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.Histogram } |
| PARETO_LINE_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.ParetoLine } |
| BOX_AND_WHISKER_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.BoxAndWhisker } |
| WATERFALL_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.Waterfall } |
| FUNNEL_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.Funnel } |
| TREEMAP_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.Treemap } |
| MAP_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.Map } |
| SUNBURST_CHART | Grupperar detta set av serietyper:<br/>            { ChartType.Sunburst } |

### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)