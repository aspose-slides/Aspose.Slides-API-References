---
title: CombinableSeriesTypesGroup enumeration
second_title: Aspose.Slides dla Pythona przy pomocy .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeracja

Enumeracja grup kombinowalnych typów serii.
            Każdy element odnosi się do grupy typów serii wykresu, które mogą współistnieć jednocześnie w jednej ChartSeriesGroup.
            Na przykład: seria ChartType.PercentsStackedArea nie może być jednocześnie z serią ChartType.StackedArea w jednej ChartSeriesGroup. 
            Jednak dwie lub więcej serii ChartType.PercentsStackedArea mogą znajdować się w jednej ChartSeriesGroup jednocześnie (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). 
            A seria ChartType.Line może być jednocześnie z serią ChartType.LineWithMarkers w jednej CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

Typ CombinableSeriesTypesGroup udostępnia następujące elementy:

## Pola

| Pole | Opis |
| :- | :- |
| AREA_CHART_AREA | Grupuje ten zestaw typów serii:<br/>            { ChartType.Area } |
| AREA_CHART_PERCENTS_STACKED_AREA | Grupuje ten zestaw typów serii:<br/>            { ChartType.PercentsStackedArea } |
| AREA_CHART_STACKED_AREA | Grupuje ten zestaw typów serii:<br/>            { ChartType.StackedArea } |
| AREA_CHART_AREA_3D | Grupuje ten zestaw typów serii:<br/>            { ChartType.Area3D } |
| AREA_CHART_STACKED_AREA_3D | Grupuje ten zestaw typów serii:<br/>            { ChartType.StackedArea3D } |
| AREA_CHART_PERCENTS_STACKED_AREA_3D | Grupuje ten zestaw typów serii:<br/>            { ChartType.PercentsStackedArea3D } |
| LINE_CHART_LINE | Grupuje ten zestaw typów serii:<br/>            { ChartType.Line, ChartType.LineWithMarkers } |
| LINE_CHART_STACKED_LINE | Grupuje ten zestaw typów serii:<br/>            { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LINE_CHART_PERCENTS_STACKED_LINE | Grupuje ten zestaw typów serii:<br/>            { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| LINE_3D_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.Line3D } |
| STOCK_HIGH_LOW_CLOSE | Grupuje ten zestaw typów serii:<br/>            { ChartType.HighLowClose } |
| STOCK_OPEN_HIGH_LOW_CLOSE | Grupuje ten zestaw typów serii:<br/>            { ChartType.OpenHighLowClose } |
| STOCK_VOLUME_HIGH_LOW_CLOSE | Grupuje ten zestaw typów serii:<br/>            { ChartType.VolumeHighLowClose } |
| STOCK_VOLUME_OPEN_HIGH_LOW_CLOSE | Grupuje ten zestaw typów serii:<br/>            { ChartType.VolumeOpenHighLowClose } |
| RADAR_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.Radar, ChartType.RadarWithMarkers } |
| FILLED_RADAR_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.FilledRadar } |
| SCATTER_STRAIGHT_MARKER | Grupuje ten zestaw typów serii:<br/>            { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| SCATTER_SMOOTH_MARKER | Grupuje ten zestaw typów serii:<br/>            { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PIE_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.Pie, ChartType.ExplodedPie } |
| PIE_3D_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DOUGHNUT_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BAR_CHART_VERT_CLUSTERED | Grupuje ten zestaw typów serii:<br/>            { ChartType.ClusteredColumn } |
| BAR_CHART_VERT_STACKED | Grupuje ten zestaw typów serii:<br/>            { ChartType.StackedColumn } |
| BAR_CHART_VERT_PERCENTS_STACKED | Grupuje ten zestaw typów serii:<br/>            { ChartType.PercentsStackedColumn } |
| BAR_CHART_HORIZ_CLUSTERED | Grupuje ten zestaw typów serii:<br/>            { ChartType.ClusteredBar } |
| BAR_CHART_HORIZ_STACKED | Grupuje ten zestaw typów serii:<br/>            { ChartType.StackedBar } |
| BAR_CHART_HORIZ_PERCENTS_STACKED | Grupuje ten zestaw typów serii:<br/>            { ChartType.PercentsStackedBar } |
| BAR_3D_CHART_VERT | Grupuje ten zestaw typów serii:<br/>            { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| BAR_3D_CHART_VERT_CLUSTERED | Grupuje ten zestaw typów serii:<br/>            { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_COLUMN_3D | Grupuje ten zestaw typów serii:<br/>            { ChartType.PercentsStackedColumn3D } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CONE | Grupuje ten zestaw typów serii:<br/>            { ChartType.PercentsStackedCone } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CYLINDER | Grupuje ten zestaw typów serii:<br/>            { ChartType.PercentsStackedCylinder } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_PYRAMID | Grupuje ten zestaw typów serii:<br/>            { ChartType.PercentsStackedPyramid } |
| BAR_3D_CHART_VERT_STACKED_COLUMN_3D | Grupuje ten zestaw typów serii:<br/>            { ChartType.StackedColumn3D } |
| BAR_3D_CHART_VERT_STACKED_CONE | Grupuje ten zestaw typów serii:<br/>            { ChartType.StackedCone } |
| BAR_3D_CHART_VERT_STACKED_CYLINDER | Grupuje ten zestaw typów serii:<br/>            { ChartType.StackedCylinder } |
| BAR_3D_CHART_VERT_STACKED_PYRAMID | Grupuje ten zestaw typów serii:<br/>            { ChartType.StackedPyramid } |
| BAR_3D_CHART_HORIZ_CLUSTERED | Grupuje ten zestaw typów serii:<br/>            { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_STACKED_BAR_3D | Grupuje ten zestaw typów serii:<br/>            { ChartType.StackedBar3D } |
| BAR_3D_CHART_HORIZ_STACKED_CONE | Grupuje ten zestaw typów serii:<br/>            { ChartType.StackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_STACKED_CYLINDER | Grupuje ten zestaw typów serii:<br/>            { ChartType.StackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_STACKED_PYRAMID | Grupuje ten zestaw typów serii:<br/>            { ChartType.StackedHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_BAR_3D | Grupuje ten zestaw typów serii:<br/>            { ChartType.PercentsStackedBar3D } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CONE | Grupuje ten zestaw typów serii:<br/>            { ChartType.PercentsStackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CYLINDER | Grupuje ten zestaw typów serii:<br/>            { ChartType.PercentsStackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_PYRAMID | Grupuje ten zestaw typów serii:<br/>            { ChartType.PercentsStackedHorizontalPyramid } |
| BAR_OF_PIE_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.BarOfPie } |
| PIE_OF_PIE_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.PieOfPie } |
| SURFACE_CHART_CONTOUR | Grupuje ten zestaw typów serii:<br/>            { ChartType.Contour } |
| SURFACE_CHART_WIREFRAME_CONTOUR | Grupuje ten zestaw typów serii:<br/>            { ChartType.WireframeContour } |
| SURFACE_CHART_SURFACE_3D | Grupuje ten zestaw typów serii:<br/>            { ChartType.Surface3D } |
| SURFACE_CHART_WIREFRAME_SURFACE_3D | Grupuje ten zestaw typów serii:<br/>            { ChartType.WireframeSurface3D } |
| BUBBLE_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.Bubble, ChartType.BubbleWith3D } |
| HISTOGRAM_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.Histogram } |
| PARETO_LINE_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.ParetoLine } |
| BOX_AND_WHISKER_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.BoxAndWhisker } |
| WATERFALL_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.Waterfall } |
| FUNNEL_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.Funnel } |
| TREEMAP_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.Treemap } |
| MAP_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.Map } |
| SUNBURST_CHART | Grupuje ten zestaw typów serii:<br/>            { ChartType.Sunburst } |

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)