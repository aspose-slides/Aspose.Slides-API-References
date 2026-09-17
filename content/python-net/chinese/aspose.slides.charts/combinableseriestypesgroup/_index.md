---
title: CombinableSeriesTypesGroup enumeration
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup 枚举

可组合系列类型组的枚举。
            每个元素对应一组可以在同一个 ChartSeriesGroup 中同时存在的图表系列类型。
            例如：ChartType.PercentsStackedArea 系列不能与 ChartType.StackedArea 系列在同一个 ChartSeriesGroup 中同时存在。 
            但两个或更多的 ChartType.PercentsStackedArea 可以在同一个 ChartSeriesGroup 中同时存在（CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea）。 并且 ChartType.Line 系列可以与 ChartType.LineWithMarkers 系列在同一个 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup 中同时存在。

CombinableSeriesTypesGroup 类型公开以下成员：

## 字段

| 字段 | 描述 |
| :- | :- |
| AREA_CHART_AREA | 对以下系列类型进行分组：<br/>            { ChartType.Area } |
| AREA_CHART_PERCENTS_STACKED_AREA | 对以下系列类型进行分组：<br/>            { ChartType.PercentsStackedArea } |
| AREA_CHART_STACKED_AREA | 对以下系列类型进行分组：<br/>            { ChartType.StackedArea } |
| AREA_CHART_AREA_3D | 对以下系列类型进行分组：<br/>            { ChartType.Area3D } |
| AREA_CHART_STACKED_AREA_3D | 对以下系列类型进行分组：<br/>            { ChartType.StackedArea3D } |
| AREA_CHART_PERCENTS_STACKED_AREA_3D | 对以下系列类型进行分组：<br/>            { ChartType.PercentsStackedArea3D } |
| LINE_CHART_LINE | 对以下系列类型进行分组：<br/>            { ChartType.Line, ChartType.LineWithMarkers } |
| LINE_CHART_STACKED_LINE | 对以下系列类型进行分组：<br/>            { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LINE_CHART_PERCENTS_STACKED_LINE | 对以下系列类型进行分组：<br/>            { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| LINE_3D_CHART | 对以下系列类型进行分组：<br/>            { ChartType.Line3D } |
| STOCK_HIGH_LOW_CLOSE | 对以下系列类型进行分组：<br/>            { ChartType.HighLowClose } |
| STOCK_OPEN_HIGH_LOW_CLOSE | 对以下系列类型进行分组：<br/>            { ChartType.OpenHighLowClose } |
| STOCK_VOLUME_HIGH_LOW_CLOSE | 对以下系列类型进行分组：<br/>            { ChartType.VolumeHighLowClose } |
| STOCK_VOLUME_OPEN_HIGH_LOW_CLOSE | 对以下系列类型进行分组：<br/>            { ChartType.VolumeOpenHighLowClose } |
| RADAR_CHART | 对以下系列类型进行分组：<br/>            { ChartType.Radar, ChartType.RadarWithMarkers } |
| FILLED_RADAR_CHART | 对以下系列类型进行分组：<br/>            { ChartType.FilledRadar } |
| SCATTER_STRAIGHT_MARKER | 对以下系列类型进行分组：<br/>            { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| SCATTER_SMOOTH_MARKER | 对以下系列类型进行分组：<br/>            { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PIE_CHART | 对以下系列类型进行分组：<br/>            { ChartType.Pie, ChartType.ExplodedPie } |
| PIE_3D_CHART | 对以下系列类型进行分组：<br/>            { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DOUGHNUT_CHART | 对以下系列类型进行分组：<br/>            { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BAR_CHART_VERT_CLUSTERED | 对以下系列类型进行分组：<br/>            { ChartType.ClusteredColumn } |
| BAR_CHART_VERT_STACKED | 对以下系列类型进行分组：<br/>            { ChartType.StackedColumn } |
| BAR_CHART_VERT_PERCENTS_STACKED | 对以下系列类型进行分组：<br/>            { ChartType.PercentsStackedColumn } |
| BAR_CHART_HORIZ_CLUSTERED | 对以下系列类型进行分组：<br/>            { ChartType.ClusteredBar } |
| BAR_CHART_HORIZ_STACKED | 对以下系列类型进行分组：<br/>            { ChartType.StackedBar } |
| BAR_CHART_HORIZ_PERCENTS_STACKED | 对以下系列类型进行分组：<br/>            { ChartType.PercentsStackedBar } |
| BAR_3D_CHART_VERT | 对以下系列类型进行分组：<br/>            { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| BAR_3D_CHART_VERT_CLUSTERED | 对以下系列类型进行分组：<br/>            { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_COLUMN_3D | 对以下系列类型进行分组：<br/>            { ChartType.PercentsStackedColumn3D } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CONE | 对以下系列类型进行分组：<br/>            { ChartType.PercentsStackedCone } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CYLINDER | 对以下系列类型进行分组：<br/>            { ChartType.PercentsStackedCylinder } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_PYRAMID | 对以下系列类型进行分组：<br/>            { ChartType.PercentsStackedPyramid } |
| BAR_3D_CHART_VERT_STACKED_COLUMN_3D | 对以下系列类型进行分组：<br/>            { ChartType.StackedColumn3D } |
| BAR_3D_CHART_VERT_STACKED_CONE | 对以下系列类型进行分组：<br/>            { ChartType.StackedCone } |
| BAR_3D_CHART_VERT_STACKED_CYLINDER | 对以下系列类型进行分组：<br/>            { ChartType.StackedCylinder } |
| BAR_3D_CHART_VERT_STACKED_PYRAMID | 对以下系列类型进行分组：<br/>            { ChartType.StackedPyramid } |
| BAR_3D_CHART_HORIZ_CLUSTERED | 对以下系列类型进行分组：<br/>            { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_STACKED_BAR_3D | 对以下系列类型进行分组：<br/>            { ChartType.StackedBar3D } |
| BAR_3D_CHART_HORIZ_STACKED_CONE | 对以下系列类型进行分组：<br/>            { ChartType.StackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_STACKED_CYLINDER | 对以下系列类型进行分组：<br/>            { ChartType.StackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_STACKED_PYRAMID | 对以下系列类型进行分组：<br/>            { ChartType.StackedHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_BAR_3D | 对以下系列类型进行分组：<br/>            { ChartType.PercentsStackedBar3D } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CONE | 对以下系列类型进行分组：<br/>            { ChartType.PercentsStackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CYLINDER | 对以下系列类型进行分组：<br/>            { ChartType.PercentsStackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_PYRAMID | 对以下系列类型进行分组：<br/>            { ChartType.PercentsStackedHorizontalPyramid } |
| BAR_OF_PIE_CHART | 对以下系列类型进行分组：<br/>            { ChartType.BarOfPie } |
| PIE_OF_PIE_CHART | 对以下系列类型进行分组：<br/>            { ChartType.PieOfPie } |
| SURFACE_CHART_CONTOUR | 对以下系列类型进行分组：<br/>            { ChartType.Contour } |
| SURFACE_CHART_WIREFRAME_CONTOUR | 对以下系列类型进行分组：<br/>            { ChartType.WireframeContour } |
| SURFACE_CHART_SURFACE_3D | 对以下系列类型进行分组：<br/>            { ChartType.Surface3D } |
| SURFACE_CHART_WIREFRAME_SURFACE_3D | 对以下系列类型进行分组：<br/>            { ChartType.WireframeSurface3D } |
| BUBBLE_CHART | 对以下系列类型进行分组：<br/>            { ChartType.Bubble, ChartType.BubbleWith3D } |
| HISTOGRAM_CHART | 对以下系列类型进行分组：<br/>            { ChartType.Histogram } |
| PARETO_LINE_CHART | 对以下系列类型进行分组：<br/>            { ChartType.ParetoLine } |
| BOX_AND_WHISKER_CHART | 对以下系列类型进行分组：<br/>            { ChartType.BoxAndWhisker } |
| WATERFALL_CHART | 对以下系列类型进行分组：<br/>            { ChartType.Waterfall } |
| FUNNEL_CHART | 对以下系列类型进行分组：<br/>            { ChartType.Funnel } |
| TREEMAP_CHART | 对以下系列类型进行分组：<br/>            { ChartType.Treemap } |
| MAP_CHART | 对以下系列类型进行分组：<br/>            { ChartType.Map } |
| SUNBURST_CHART | 对以下系列类型进行分组：<br/>            { ChartType.Sunburst } |

### 另请参见
* 模块 [`aspose.slides.charts`](/slides/python-net/zh/aspose.slides.charts)
* 库 [`Aspose.Slides`](/slides/python-net)