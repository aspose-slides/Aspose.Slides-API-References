---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/combinableseriestypesgroup/
---

## CombinableSeriesTypesGroup class

 Enumeration of groups of combinable series types.
 Each element relates to group of types of chart series that can persist simultaneously in one ChartSeriesGroup.
 For example: ChartType.PercentsStackedArea series cannot be simultaneously with ChartType.StackedArea series 
 in one ChartSeriesGroup. But two or more ChartType.PercentsStackedArea can be in one ChartSeriesGroup 
 simultaneously (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). And ChartType.Line series can be 
 with ChartType.LineWithMarkers series simultaneously in one CombinableSeriesTypesGroup.LineChart_Line 
 ChartSeriesGroup.
 

## Constants

| Name | Value | Description |
| --- | --- | --- |
| AreaChart_Area | 4 | Groups this set of series types: { ChartType.Area } |
| AreaChart_Area3D | 24 | Groups this set of series types: { ChartType.Area3D } |
| AreaChart_PercentsStackedArea | 5 | Groups this set of series types: { ChartType.PercentsStackedArea } |
| AreaChart_PercentsStackedArea3D | 26 | Groups this set of series types: { ChartType.PercentsStackedArea3D } |
| AreaChart_StackedArea | 6 | Groups this set of series types: { ChartType.StackedArea } |
| AreaChart_StackedArea3D | 25 | Groups this set of series types: { ChartType.StackedArea3D } |
| Bar3DChart_HorizClustered | 39 | Groups this set of series types: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | Groups this set of series types: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | 45 | Groups this set of series types: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | Groups this set of series types: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | Groups this set of series types: { ChartType.PercentsStackedHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | 40 | Groups this set of series types: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | 41 | Groups this set of series types: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | 42 | Groups this set of series types: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | 43 | Groups this set of series types: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_Vert | 29 | Groups this set of series types: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | 30 | Groups this set of series types: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | Groups this set of series types: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | 32 | Groups this set of series types: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | Groups this set of series types: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | Groups this set of series types: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | 35 | Groups this set of series types: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | 36 | Groups this set of series types: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | 37 | Groups this set of series types: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | 38 | Groups this set of series types: { ChartType.StackedPyramid } |
| BarChart_HorizClustered | 7 | Groups this set of series types: { ChartType.ClusteredBar } |
| BarChart_HorizPercentsStacked | 9 | Groups this set of series types: { ChartType.PercentsStackedBar } |
| BarChart_HorizStacked | 8 | Groups this set of series types: { ChartType.StackedBar } |
| BarChart_VertClustered | 10 | Groups this set of series types: { ChartType.ClusteredColumn } |
| BarChart_VertPercentsStacked | 12 | Groups this set of series types: { ChartType.PercentsStackedColumn } |
| BarChart_VertStacked | 11 | Groups this set of series types: { ChartType.StackedColumn } |
| BarOfPieChart | 0 | Groups this set of series types: { ChartType.BarOfPie } |
| BoxAndWhiskerChart | 55 | Groups this set of series types: { ChartType.BoxAndWhisker } |
| BubbleChart | 52 | Groups this set of series types: { ChartType.Bubble, ChartType.BubbleWith3D } |
| DoughnutChart | 2 | Groups this set of series types: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| FilledRadarChart | 17 | Groups this set of series types: { ChartType.FilledRadar } |
| FunnelChart | 57 | Groups this set of series types: { ChartType.Funnel } |
| HistogramChart | 53 | Groups this set of series types: { ChartType.Histogram } |
| Line3DChart | 27 | Groups this set of series types: { ChartType.Line3D } |
| LineChart_Line | 13 | Groups this set of series types: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_PercentsStackedLine | 15 | Groups this set of series types: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| LineChart_StackedLine | 14 | Groups this set of series types: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| MapChart | 59 | Groups this set of series types: { ChartType.Map } |
| ParetoLineChart | 54 | Groups this set of series types: { ChartType.ParetoLine } |
| Pie3DChart | 28 | Groups this set of series types: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| PieChart | 3 | Groups this set of series types: { ChartType.Pie, ChartType.ExplodedPie } |
| PieOfPieChart | 1 | Groups this set of series types: { ChartType.PieOfPie } |
| RadarChart | 16 | Groups this set of series types: { ChartType.Radar, ChartType.RadarWithMarkers } |
| ScatterSmoothMarker | 23 | Groups this set of series types: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| ScatterStraightMarker | 22 | Groups this set of series types: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| StockHighLowClose | 18 | Groups this set of series types: { ChartType.HighLowClose } |
| StockOpenHighLowClose | 19 | Groups this set of series types: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | 20 | Groups this set of series types: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | 21 | Groups this set of series types: { ChartType.VolumeOpenHighLowClose } |
| SunburstChart | 60 | Groups this set of series types: { ChartType.Sunburst } |
| SurfaceChart_Contour | 48 | Groups this set of series types: { ChartType.Contour } |
| SurfaceChart_Surface3D | 50 | Groups this set of series types: { ChartType.Surface3D } |
| SurfaceChart_WireframeContour | 49 | Groups this set of series types: { ChartType.WireframeContour } |
| SurfaceChart_WireframeSurface3D | 51 | Groups this set of series types: { ChartType.WireframeSurface3D } |
| TreemapChart | 58 | Groups this set of series types: { ChartType.Treemap } |
| WaterfallChart | 56 | Groups this set of series types: { ChartType.Waterfall } |

