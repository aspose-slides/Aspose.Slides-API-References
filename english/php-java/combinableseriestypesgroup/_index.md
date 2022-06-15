---
title: CombinableSeriesTypesGroup
type: docs
weight: 0
url: /php-java/combinableseriestypesgroup/
---

# CombinableSeriesTypesGroup class

 Enumeration of groups of combinable series types.
 Each element relates to group of types of chart series that can persist simultaneously in one ChartSeriesGroup.
 For example: ChartType.PercentsStackedArea series cannot be simultaneously with ChartType.StackedArea series 
 in one ChartSeriesGroup. But two or more ChartType.PercentsStackedArea can be in one ChartSeriesGroup 
 simultaneously (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). And ChartType.Line series can be 
 with ChartType.LineWithMarkers series simultaneously in one CombinableSeriesTypesGroup.LineChart_Line 
 ChartSeriesGroup.
 

## Constants

| name | description |
| --- | --- |
| AreaChart_Area | Groups this set of series types: { ChartType.Area } |
| AreaChart_Area3D | Groups this set of series types: { ChartType.Area3D } |
| AreaChart_PercentsStackedArea | Groups this set of series types: { ChartType.PercentsStackedArea } |
| AreaChart_PercentsStackedArea3D | Groups this set of series types: { ChartType.PercentsStackedArea3D } |
| AreaChart_StackedArea | Groups this set of series types: { ChartType.StackedArea } |
| AreaChart_StackedArea3D | Groups this set of series types: { ChartType.StackedArea3D } |
| Bar3DChart_HorizClustered | Groups this set of series types: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | Groups this set of series types: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | Groups this set of series types: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | Groups this set of series types: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | Groups this set of series types: { ChartType.PercentsStackedHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | Groups this set of series types: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | Groups this set of series types: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | Groups this set of series types: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | Groups this set of series types: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_Vert | Groups this set of series types: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | Groups this set of series types: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | Groups this set of series types: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | Groups this set of series types: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | Groups this set of series types: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | Groups this set of series types: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | Groups this set of series types: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | Groups this set of series types: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | Groups this set of series types: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | Groups this set of series types: { ChartType.StackedPyramid } |
| BarChart_HorizClustered | Groups this set of series types: { ChartType.ClusteredBar } |
| BarChart_HorizPercentsStacked | Groups this set of series types: { ChartType.PercentsStackedBar } |
| BarChart_HorizStacked | Groups this set of series types: { ChartType.StackedBar } |
| BarChart_VertClustered | Groups this set of series types: { ChartType.ClusteredColumn } |
| BarChart_VertPercentsStacked | Groups this set of series types: { ChartType.PercentsStackedColumn } |
| BarChart_VertStacked | Groups this set of series types: { ChartType.StackedColumn } |
| BarOfPieChart | Groups this set of series types: { ChartType.BarOfPie } |
| BoxAndWhiskerChart | Groups this set of series types: { ChartType.BoxAndWhisker } |
| BubbleChart | Groups this set of series types: { ChartType.Bubble, ChartType.BubbleWith3D } |
| DoughnutChart | Groups this set of series types: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| FilledRadarChart | Groups this set of series types: { ChartType.FilledRadar } |
| FunnelChart | Groups this set of series types: { ChartType.Funnel } |
| HistogramChart | Groups this set of series types: { ChartType.Histogram } |
| Line3DChart | Groups this set of series types: { ChartType.Line3D } |
| LineChart_Line | Groups this set of series types: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_PercentsStackedLine | Groups this set of series types: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| LineChart_StackedLine | Groups this set of series types: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| MapChart | Groups this set of series types: { ChartType.Map } |
| ParetoLineChart | Groups this set of series types: { ChartType.ParetoLine } |
| Pie3DChart | Groups this set of series types: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| PieChart | Groups this set of series types: { ChartType.Pie, ChartType.ExplodedPie } |
| PieOfPieChart | Groups this set of series types: { ChartType.PieOfPie } |
| RadarChart | Groups this set of series types: { ChartType.Radar, ChartType.RadarWithMarkers } |
| ScatterSmoothMarker | Groups this set of series types: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| ScatterStraightMarker | Groups this set of series types: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| StockHighLowClose | Groups this set of series types: { ChartType.HighLowClose } |
| StockOpenHighLowClose | Groups this set of series types: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | Groups this set of series types: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | Groups this set of series types: { ChartType.VolumeOpenHighLowClose } |
| SunburstChart | Groups this set of series types: { ChartType.Sunburst } |
| SurfaceChart_Contour | Groups this set of series types: { ChartType.Contour } |
| SurfaceChart_Surface3D | Groups this set of series types: { ChartType.Surface3D } |
| SurfaceChart_WireframeContour | Groups this set of series types: { ChartType.WireframeContour } |
| SurfaceChart_WireframeSurface3D | Groups this set of series types: { ChartType.WireframeSurface3D } |
| TreemapChart | Groups this set of series types: { ChartType.Treemap } |
| WaterfallChart | Groups this set of series types: { ChartType.Waterfall } |

