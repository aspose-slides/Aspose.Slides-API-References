---
title: CombinableSeriesTypesGroup enumeration
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup výčet

Výčet skupin kombinovatelných typů řad.

Každý prvek se vztahuje ke skupině typů řad grafu, které mohou současně existovat v jednom ChartSeriesGroup.
            Například řada ChartType.PercentsStackedArea nemůže být současně s řadou ChartType.StackedArea
            v jednom ChartSeriesGroup. Ale dvě nebo více řad ChartType.PercentsStackedArea mohou být v jednom ChartSeriesGroup
            současně (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). A řada ChartType.Line může být
            se řadou ChartType.LineWithMarkers současně v jednom CombinableSeriesTypesGroup.LineChart_Line
            ChartSeriesGroup.

Typ CombinableSeriesTypesGroup obsahuje následující členy:

## Pole

| Pole | Popis |
| :- | :- |
| AREA_CHART_AREA | Skupina tohoto souboru typů řad:<br/>            { ChartType.Area } |
| AREA_CHART_PERCENTS_STACKED_AREA | Skupina tohoto souboru typů řad:<br/>            { ChartType.PercentsStackedArea } |
| AREA_CHART_STACKED_AREA | Skupina tohoto souboru typů řad:<br/>            { ChartType.StackedArea } |
| AREA_CHART_AREA_3D | Skupina tohoto souboru typů řad:<br/>            { ChartType.Area3D } |
| AREA_CHART_STACKED_AREA_3D | Skupina tohoto souboru typů řad:<br/>            { ChartType.StackedArea3D } |
| AREA_CHART_PERCENTS_STACKED_AREA_3D | Skupina tohoto souboru typů řad:<br/>            { ChartType.PercentsStackedArea3D } |
| LINE_CHART_LINE | Skupina tohoto souboru typů řad:<br/>            { ChartType.Line, ChartType.LineWithMarkers } |
| LINE_CHART_STACKED_LINE | Skupina tohoto souboru typů řad:<br/>            { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LINE_CHART_PERCENTS_STACKED_LINE | Skupina tohoto souboru typů řad:<br/>            { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| LINE_3D_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.Line3D } |
| STOCK_HIGH_LOW_CLOSE | Skupina tohoto souboru typů řad:<br/>            { ChartType.HighLowClose } |
| STOCK_OPEN_HIGH_LOW_CLOSE | Skupina tohoto souboru typů řad:<br/>            { ChartType.OpenHighLowClose } |
| STOCK_VOLUME_HIGH_LOW_CLOSE | Skupina tohoto souboru typů řad:<br/>            { ChartType.VolumeHighLowClose } |
| STOCK_VOLUME_OPEN_HIGH_LOW_CLOSE | Skupina tohoto souboru typů řad:<br/>            { ChartType.VolumeOpenHighLowClose } |
| RADAR_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.Radar, ChartType.RadarWithMarkers } |
| FILLED_RADAR_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.FilledRadar } |
| SCATTER_STRAIGHT_MARKER | Skupina tohoto souboru typů řad:<br/>            { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| SCATTER_SMOOTH_MARKER | Skupina tohoto souboru typů řad:<br/>            { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PIE_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.Pie, ChartType.ExplodedPie } |
| PIE_3D_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DOUGHNUT_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BAR_CHART_VERT_CLUSTERED | Skupina tohoto souboru typů řad:<br/>            { ChartType.ClusteredColumn } |
| BAR_CHART_VERT_STACKED | Skupina tohoto souboru typů řad:<br/>            { ChartType.StackedColumn } |
| BAR_CHART_VERT_PERCENTS_STACKED | Skupina tohoto souboru typů řad:<br/>            { ChartType.PercentsStackedColumn } |
| BAR_CHART_HORIZ_CLUSTERED | Skupina tohoto souboru typů řad:<br/>            { ChartType.ClusteredBar } |
| BAR_CHART_HORIZ_STACKED | Skupina tohoto souboru typů řad:<br/>            { ChartType.StackedBar } |
| BAR_CHART_HORIZ_PERCENTS_STACKED | Skupina tohoto souboru typů řad:<br/>            { ChartType.PercentsStackedBar } |
| BAR_3D_CHART_VERT | Skupina tohoto souboru typů řad:<br/>            { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| BAR_3D_CHART_VERT_CLUSTERED | Skupina tohoto souboru typů řad:<br/>            { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_COLUMN_3D | Skupina tohoto souboru typů řad:<br/>            { ChartType.PercentsStackedColumn3D } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CONE | Skupina tohoto souboru typů řad:<br/>            { ChartType.PercentsStackedCone } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CYLINDER | Skupina tohoto souboru typů řad:<br/>            { ChartType.PercentsStackedCylinder } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_PYRAMID | Skupina tohoto souboru typů řad:<br/>            { ChartType.PercentsStackedPyramid } |
| BAR_3D_CHART_VERT_STACKED_COLUMN_3D | Skupina tohoto souboru typů řad:<br/>            { ChartType.StackedColumn3D } |
| BAR_3D_CHART_VERT_STACKED_CONE | Skupina tohoto souboru typů řad:<br/>            { ChartType.StackedCone } |
| BAR_3D_CHART_VERT_STACKED_CYLINDER | Skupina tohoto souboru typů řad:<br/>            { ChartType.StackedCylinder } |
| BAR_3D_CHART_VERT_STACKED_PYRAMID | Skupina tohoto souboru typů řad:<br/>            { ChartType.StackedPyramid } |
| BAR_3D_CHART_HORIZ_CLUSTERED | Skupina tohoto souboru typů řad:<br/>            { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_STACKED_BAR_3D | Skupina tohoto souboru typů řad:<br/>            { ChartType.StackedBar3D } |
| BAR_3D_CHART_HORIZ_STACKED_CONE | Skupina tohoto souboru typů řad:<br/>            { ChartType.StackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_STACKED_CYLINDER | Skupina tohoto souboru typů řad:<br/>            { ChartType.StackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_STACKED_PYRAMID | Skupina tohoto souboru typů řad:<br/>            { ChartType.StackedHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_BAR_3D | Skupina tohoto souboru typů řad:<br/>            { ChartType.PercentsStackedBar3D } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CONE | Skupina tohoto souboru typů řad:<br/>            { ChartType.PercentsStackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CYLINDER | Skupina tohoto souboru typů řad:<br/>            { ChartType.PercentsStackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_PYRAMID | Skupina tohoto souboru typů řad:<br/>            { ChartType.PercentsStackedHorizontalPyramid } |
| BAR_OF_PIE_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.BarOfPie } |
| PIE_OF_PIE_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.PieOfPie } |
| SURFACE_CHART_CONTOUR | Skupina tohoto souboru typů řad:<br/>            { ChartType.Contour } |
| SURFACE_CHART_WIREFRAME_CONTOUR | Skupina tohoto souboru typů řad:<br/>            { ChartType.WireframeContour } |
| SURFACE_CHART_SURFACE_3D | Skupina tohoto souboru typů řad:<br/>            { ChartType.Surface3D } |
| SURFACE_CHART_WIREFRAME_SURFACE_3D | Skupina tohoto souboru typů řad:<br/>            { ChartType.WireframeSurface3D } |
| BUBBLE_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.Bubble, ChartType.BubbleWith3D } |
| HISTOGRAM_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.Histogram } |
| PARETO_LINE_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.ParetoLine } |
| BOX_AND_WHISKER_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.BoxAndWhisker } |
| WATERFALL_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.Waterfall } |
| FUNNEL_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.Funnel } |
| TREEMAP_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.Treemap } |
| MAP_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.Map } |
| SUNBURST_CHART | Skupina tohoto souboru typů řad:<br/>            { ChartType.Sunburst } |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)