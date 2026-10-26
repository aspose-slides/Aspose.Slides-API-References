---
title: CombinableSeriesTypesGroup enumeration
second_title: Aspose.Slides para Python mediante la API .NET
description: 
type: docs
url: /es/aspose.slides.charts/combinableseriestypesgroup/
---
## Enumeración CombinableSeriesTypesGroup

Enumeración de grupos de tipos de series combinables.  
            Cada elemento se relaciona con un grupo de tipos de series de gráfico que pueden persistir simultáneamente en un ChartSeriesGroup.  
            Por ejemplo: la serie ChartType.PercentsStackedArea no puede estar simultáneamente con la serie ChartType.StackedArea en un ChartSeriesGroup. Pero dos o más ChartType.PercentsStackedArea pueden estar en un ChartSeriesGroup simultáneamente (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Y la serie ChartType.Line puede estar con la serie ChartType.LineWithMarkers simultáneamente en un CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

El tipo CombinableSeriesTypesGroup expone los siguientes miembros:

## Campos

| Campo | Descripción |
| :- | :- |
| AREA_CHART_AREA | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Area } |
| AREA_CHART_PERCENTS_STACKED_AREA | Agrupa este conjunto de tipos de series:<br/>            { ChartType.PercentsStackedArea } |
| AREA_CHART_STACKED_AREA | Agrupa este conjunto de tipos de series:<br/>            { ChartType.StackedArea } |
| AREA_CHART_AREA_3D | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Area3D } |
| AREA_CHART_STACKED_AREA_3D | Agrupa este conjunto de tipos de series:<br/>            { ChartType.StackedArea3D } |
| AREA_CHART_PERCENTS_STACKED_AREA_3D | Agrupa este conjunto de tipos de series:<br/>            { ChartType.PercentsStackedArea3D } |
| LINE_CHART_LINE | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Line, ChartType.LineWithMarkers } |
| LINE_CHART_STACKED_LINE | Agrupa este conjunto de tipos de series:<br/>            { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LINE_CHART_PERCENTS_STACKED_LINE | Agrupa este conjunto de tipos de series:<br/>            { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| LINE_3D_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Line3D } |
| STOCK_HIGH_LOW_CLOSE | Agrupa este conjunto de tipos de series:<br/>            { ChartType.HighLowClose } |
| STOCK_OPEN_HIGH_LOW_CLOSE | Agrupa este conjunto de tipos de series:<br/>            { ChartType.OpenHighLowClose } |
| STOCK_VOLUME_HIGH_LOW_CLOSE | Agrupa este conjunto de tipos de series:<br/>            { ChartType.VolumeHighLowClose } |
| STOCK_VOLUME_OPEN_HIGH_LOW_CLOSE | Agrupa este conjunto de tipos de series:<br/>            { ChartType.VolumeOpenHighLowClose } |
| RADAR_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Radar, ChartType.RadarWithMarkers } |
| FILLED_RADAR_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.FilledRadar } |
| SCATTER_STRAIGHT_MARKER | Agrupa este conjunto de tipos de series:<br/>            { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| SCATTER_SMOOTH_MARKER | Agrupa este conjunto de tipos de series:<br/>            { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PIE_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Pie, ChartType.ExplodedPie } |
| PIE_3D_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DOUGHNUT_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BAR_CHART_VERT_CLUSTERED | Agrupa este conjunto de tipos de series:<br/>            { ChartType.ClusteredColumn } |
| BAR_CHART_VERT_STACKED | Agrupa este conjunto de tipos de series:<br/>            { ChartType.StackedColumn } |
| BAR_CHART_VERT_PERCENTS_STACKED | Agrupa este conjunto de tipos de series:<br/>            { ChartType.PercentsStackedColumn } |
| BAR_CHART_HORIZ_CLUSTERED | Agrupa este conjunto de tipos de series:<br/>            { ChartType.ClusteredBar } |
| BAR_CHART_HORIZ_STACKED | Agrupa este conjunto de tipos de series:<br/>            { ChartType.StackedBar } |
| BAR_CHART_HORIZ_PERCENTS_STACKED | Agrupa este conjunto de tipos de series:<br/>            { ChartType.PercentsStackedBar } |
| BAR_3D_CHART_VERT | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| BAR_3D_CHART_VERT_CLUSTERED | Agrupa este conjunto de tipos de series:<br/>            { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_COLUMN_3D | Agrupa este conjunto de tipos de series:<br/>            { ChartType.PercentsStackedColumn3D } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CONE | Agrupa este conjunto de tipos de series:<br/>            { ChartType.PercentsStackedCone } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CYLINDER | Agrupa este conjunto de tipos de series:<br/>            { ChartType.PercentsStackedCylinder } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_PYRAMID | Agrupa este conjunto de tipos de series:<br/>            { ChartType.PercentsStackedPyramid } |
| BAR_3D_CHART_VERT_STACKED_COLUMN_3D | Agrupa este conjunto de tipos de series:<br/>            { ChartType.StackedColumn3D } |
| BAR_3D_CHART_VERT_STACKED_CONE | Agrupa este conjunto de tipos de series:<br/>            { ChartType.StackedCone } |
| BAR_3D_CHART_VERT_STACKED_CYLINDER | Agrupa este conjunto de tipos de series:<br/>            { ChartType.StackedCylinder } |
| BAR_3D_CHART_VERT_STACKED_PYRAMID | Agrupa este conjunto de tipos de series:<br/>            { ChartType.StackedPyramid } |
| BAR_3D_CHART_HORIZ_CLUSTERED | Agrupa este conjunto de tipos de series:<br/>            { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_STACKED_BAR_3D | Agrupa este conjunto de tipos de series:<br/>            { ChartType.StackedBar3D } |
| BAR_3D_CHART_HORIZ_STACKED_CONE | Agrupa este conjunto de tipos de series:<br/>            { ChartType.StackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_STACKED_CYLINDER | Agrupa este conjunto de tipos de series:<br/>            { ChartType.StackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_STACKED_PYRAMID | Agrupa este conjunto de tipos de series:<br/>            { ChartType.StackedHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_BAR_3D | Agrupa este conjunto de tipos de series:<br/>            { ChartType.PercentsStackedBar3D } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CONE | Agrupa este conjunto de tipos de series:<br/>            { ChartType.PercentsStackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CYLINDER | Agrupa este conjunto de tipos de series:<br/>            { ChartType.PercentsStackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_PYRAMID | Agrupa este conjunto de tipos de series:<br/>            { ChartType.PercentsStackedHorizontalPyramid } |
| BAR_OF_PIE_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.BarOfPie } |
| PIE_OF_PIE_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.PieOfPie } |
| SURFACE_CHART_CONTOUR | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Contour } |
| SURFACE_CHART_WIREFRAME_CONTOUR | Agrupa este conjunto de tipos de series:<br/>            { ChartType.WireframeContour } |
| SURFACE_CHART_SURFACE_3D | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Surface3D } |
| SURFACE_CHART_WIREFRAME_SURFACE_3D | Agrupa este conjunto de tipos de series:<br/>            { ChartType.WireframeSurface3D } |
| BUBBLE_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Bubble, ChartType.BubbleWith3D } |
| HISTOGRAM_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Histogram } |
| PARETO_LINE_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.ParetoLine } |
| BOX_AND_WHISKER_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.BoxAndWhisker } |
| WATERFALL_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Waterfall } |
| FUNNEL_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Funnel } |
| TREEMAP_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Treemap } |
| MAP_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Map } |
| SUNBURST_CHART | Agrupa este conjunto de tipos de series:<br/>            { ChartType.Sunburst } |


### Ver también
* módulo [`aspose.slides.charts`](/slides/python-net/es/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)