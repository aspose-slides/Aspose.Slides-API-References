---
title: CombinableSeriesTypesGroup enumeration
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeração

Enumeração dos grupos de tipos de séries combináveis.  
Cada elemento relaciona-se a um grupo de tipos de séries de gráfico que podem coexistir simultaneamente em um ChartSeriesGroup.  
Por exemplo: séries ChartType.PercentsStackedArea não podem estar simultaneamente com séries ChartType.StackedArea em um ChartSeriesGroup. Mas duas ou mais séries ChartType.PercentsStackedArea podem estar em um ChartSeriesGroup simultaneamente (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). E séries ChartType.Line podem estar com séries ChartType.LineWithMarkers simultaneamente em um CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

O tipo CombinableSeriesTypesGroup expõe os seguintes membros:

## Campos

| Campo | Descrição |
| :- | :- |
| AREA_CHART_AREA | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Area } |
| AREA_CHART_PERCENTS_STACKED_AREA | Agrupa este conjunto de tipos de série:<br/>            { ChartType.PercentsStackedArea } |
| AREA_CHART_STACKED_AREA | Agrupa este conjunto de tipos de série:<br/>            { ChartType.StackedArea } |
| AREA_CHART_AREA_3D | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Area3D } |
| AREA_CHART_STACKED_AREA_3D | Agrupa este conjunto de tipos de série:<br/>            { ChartType.StackedArea3D } |
| AREA_CHART_PERCENTS_STACKED_AREA_3D | Agrupa este conjunto de tipos de série:<br/>            { ChartType.PercentsStackedArea3D } |
| LINE_CHART_LINE | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Line, ChartType.LineWithMarkers } |
| LINE_CHART_STACKED_LINE | Agrupa este conjunto de tipos de série:<br/>            { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LINE_CHART_PERCENTS_STACKED_LINE | Agrupa este conjunto de tipos de série:<br/>            { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| LINE_3D_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Line3D } |
| STOCK_HIGH_LOW_CLOSE | Agrupa este conjunto de tipos de série:<br/>            { ChartType.HighLowClose } |
| STOCK_OPEN_HIGH_LOW_CLOSE | Agrupa este conjunto de tipos de série:<br/>            { ChartType.OpenHighLowClose } |
| STOCK_VOLUME_HIGH_LOW_CLOSE | Agrupa este conjunto de tipos de série:<br/>            { ChartType.VolumeHighLowClose } |
| STOCK_VOLUME_OPEN_HIGH_LOW_CLOSE | Agrupa este conjunto de tipos de série:<br/>            { ChartType.VolumeOpenHighLowClose } |
| RADAR_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Radar, ChartType.RadarWithMarkers } |
| FILLED_RADAR_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.FilledRadar } |
| SCATTER_STRAIGHT_MARKER | Agrupa este conjunto de tipos de série:<br/>            { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| SCATTER_SMOOTH_MARKER | Agrupa este conjunto de tipos de série:<br/>            { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PIE_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Pie, ChartType.ExplodedPie } |
| PIE_3D_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DOUGHNUT_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BAR_CHART_VERT_CLUSTERED | Agrupa este conjunto de tipos de série:<br/>            { ChartType.ClusteredColumn } |
| BAR_CHART_VERT_STACKED | Agrupa este conjunto de tipos de série:<br/>            { ChartType.StackedColumn } |
| BAR_CHART_VERT_PERCENTS_STACKED | Agrupa este conjunto de tipos de série:<br/>            { ChartType.PercentsStackedColumn } |
| BAR_CHART_HORIZ_CLUSTERED | Agrupa este conjunto de tipos de série:<br/>            { ChartType.ClusteredBar } |
| BAR_CHART_HORIZ_STACKED | Agrupa este conjunto de tipos de série:<br/>            { ChartType.StackedBar } |
| BAR_CHART_HORIZ_PERCENTS_STACKED | Agrupa este conjunto de tipos de série:<br/>            { ChartType.PercentsStackedBar } |
| BAR_3D_CHART_VERT | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| BAR_3D_CHART_VERT_CLUSTERED | Agrupa este conjunto de tipos de série:<br/>            { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_COLUMN_3D | Agrupa este conjunto de tipos de série:<br/>            { ChartType.PercentsStackedColumn3D } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CONE | Agrupa este conjunto de tipos de série:<br/>            { ChartType.PercentsStackedCone } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CYLINDER | Agrupa este conjunto de tipos de série:<br/>            { ChartType.PercentsStackedCylinder } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_PYRAMID | Agrupa este conjunto de tipos de série:<br/>            { ChartType.PercentsStackedPyramid } |
| BAR_3D_CHART_VERT_STACKED_COLUMN_3D | Agrupa este conjunto de tipos de série:<br/>            { ChartType.StackedColumn3D } |
| BAR_3D_CHART_VERT_STACKED_CONE | Agrupa este conjunto de tipos de série:<br/>            { ChartType.StackedCone } |
| BAR_3D_CHART_VERT_STACKED_CYLINDER | Agrupa este conjunto de tipos de série:<br/>            { ChartType.StackedCylinder } |
| BAR_3D_CHART_VERT_STACKED_PYRAMID | Agrupa este conjunto de tipos de série:<br/>            { ChartType.StackedPyramid } |
| BAR_3D_CHART_HORIZ_CLUSTERED | Agrupa este conjunto de tipos de série:<br/>            { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_STACKED_BAR_3D | Agrupa este conjunto de tipos de série:<br/>            { ChartType.StackedBar3D } |
| BAR_3D_CHART_HORIZ_STACKED_CONE | Agrupa este conjunto de tipos de série:<br/>            { ChartType.StackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_STACKED_CYLINDER | Agrupa este conjunto de tipos de série:<br/>            { ChartType.StackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_STACKED_PYRAMID | Agrupa este conjunto de tipos de série:<br/>            { ChartType.StackedHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_BAR_3D | Agrupa este conjunto de tipos de série:<br/>            { ChartType.PercentsStackedBar3D } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CONE | Agrupa este conjunto de tipos de série:<br/>            { ChartType.PercentsStackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CYLINDER | Agrupa este conjunto de tipos de série:<br/>            { ChartType.PercentsStackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_PYRAMID | Agrupa este conjunto de tipos de série:<br/>            { ChartType.PercentsStackedHorizontalPyramid } |
| BAR_OF_PIE_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.BarOfPie } |
| PIE_OF_PIE_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.PieOfPie } |
| SURFACE_CHART_CONTOUR | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Contour } |
| SURFACE_CHART_WIREFRAME_CONTOUR | Agrupa este conjunto de tipos de série:<br/>            { ChartType.WireframeContour } |
| SURFACE_CHART_SURFACE_3D | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Surface3D } |
| SURFACE_CHART_WIREFRAME_SURFACE_3D | Agrupa este conjunto de tipos de série:<br/>            { ChartType.WireframeSurface3D } |
| BUBBLE_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Bubble, ChartType.BubbleWith3D } |
| HISTOGRAM_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Histogram } |
| PARETO_LINE_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.ParetoLine } |
| BOX_AND_WHISKER_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.BoxAndWhisker } |
| WATERFALL_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Waterfall } |
| FUNNEL_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Funnel } |
| TREEMAP_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Treemap } |
| MAP_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Map } |
| SUNBURST_CHART | Agrupa este conjunto de tipos de série:<br/>            { ChartType.Sunburst } |

### Veja Também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)