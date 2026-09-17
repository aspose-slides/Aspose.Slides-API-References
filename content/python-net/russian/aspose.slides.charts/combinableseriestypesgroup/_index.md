---
title: CombinableSeriesTypesGroup enumeration
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup перечисление

Перечисление групп совместимых типов рядов.  
Каждый элемент относится к группе типов рядов диаграммы, которые могут существовать одновременно в одном ChartSeriesGroup.  
Например: серии ChartType.PercentsStackedArea не могут одновременно находиться с серией ChartType.StackedArea в одном ChartSeriesGroup. Однако две или более серии ChartType.PercentsStackedArea могут находиться в одном ChartSeriesGroup одновременно (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). И серии ChartType.Line могут находиться вместе с сериями ChartType.LineWithMarkers одновременно в одном CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

Тип CombinableSeriesTypesGroup раскрывает следующие члены:

## Поля

| Поле | Описание |
| :- | :- |
| AREA_CHART_AREA | Группирует этот набор типов рядов:<br/>            { ChartType.Area } |
| AREA_CHART_PERCENTS_STACKED_AREA | Группирует этот набор типов рядов:<br/>            { ChartType.PercentsStackedArea } |
| AREA_CHART_STACKED_AREA | Группирует этот набор типов рядов:<br/>            { ChartType.StackedArea } |
| AREA_CHART_AREA_3D | Группирует этот набор типов рядов:<br/>            { ChartType.Area3D } |
| AREA_CHART_STACKED_AREA_3D | Группирует этот набор типов рядов:<br/>            { ChartType.StackedArea3D } |
| AREA_CHART_PERCENTS_STACKED_AREA_3D | Группирует этот набор типов рядов:<br/>            { ChartType.PercentsStackedArea3D } |
| LINE_CHART_LINE | Группирует этот набор типов рядов:<br/>            { ChartType.Line, ChartType.LineWithMarkers } |
| LINE_CHART_STACKED_LINE | Группирует этот набор типов рядов:<br/>            { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LINE_CHART_PERCENTS_STACKED_LINE | Группирует этот набор типов рядов:<br/>            { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| LINE_3D_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.Line3D } |
| STOCK_HIGH_LOW_CLOSE | Группирует этот набор типов рядов:<br/>            { ChartType.HighLowClose } |
| STOCK_OPEN_HIGH_LOW_CLOSE | Группирует этот набор типов рядов:<br/>            { ChartType.OpenHighLowClose } |
| STOCK_VOLUME_HIGH_LOW_CLOSE | Группирует этот набор типов рядов:<br/>            { ChartType.VolumeHighLowClose } |
| STOCK_VOLUME_OPEN_HIGH_LOW_CLOSE | Группирует этот набор типов рядов:<br/>            { ChartType.VolumeOpenHighLowClose } |
| RADAR_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.Radar, ChartType.RadarWithMarkers } |
| FILLED_RADAR_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.FilledRadar } |
| SCATTER_STRAIGHT_MARKER | Группирует этот набор типов рядов:<br/>            { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| SCATTER_SMOOTH_MARKER | Группирует этот набор типов рядов:<br/>            { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PIE_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.Pie, ChartType.ExplodedPie } |
| PIE_3D_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DOUGHNUT_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BAR_CHART_VERT_CLUSTERED | Группирует этот набор типов рядов:<br/>            { ChartType.ClusteredColumn } |
| BAR_CHART_VERT_STACKED | Группирует этот набор типов рядов:<br/>            { ChartType.StackedColumn } |
| BAR_CHART_VERT_PERCENTS_STACKED | Группирует этот набор типов рядов:<br/>            { ChartType.PercentsStackedColumn } |
| BAR_CHART_HORIZ_CLUSTERED | Группирует этот набор типов рядов:<br/>            { ChartType.ClusteredBar } |
| BAR_CHART_HORIZ_STACKED | Группирует этот набор типов рядов:<br/>            { ChartType.StackedBar } |
| BAR_CHART_HORIZ_PERCENTS_STACKED | Группирует этот набор типов рядов:<br/>            { ChartType.PercentsStackedBar } |
| BAR_3D_CHART_VERT | Группирует этот набор типов рядов:<br/>            { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| BAR_3D_CHART_VERT_CLUSTERED | Группирует этот набор типов рядов:<br/>            { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_COLUMN_3D | Группирует этот набор типов рядов:<br/>            { ChartType.PercentsStackedColumn3D } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CONE | Группирует этот набор типов рядов:<br/>            { ChartType.PercentsStackedCone } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CYLINDER | Группирует этот набор типов рядов:<br/>            { ChartType.PercentsStackedCylinder } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_PYRAMID | Группирует этот набор типов рядов:<br/>            { ChartType.PercentsStackedPyramid } |
| BAR_3D_CHART_VERT_STACKED_COLUMN_3D | Группирует этот набор типов рядов:<br/>            { ChartType.StackedColumn3D } |
| BAR_3D_CHART_VERT_STACKED_CONE | Группирует этот набор типов рядов:<br/>            { ChartType.StackedCone } |
| BAR_3D_CHART_VERT_STACKED_CYLINDER | Группирует этот набор типов рядов:<br/>            { ChartType.StackedCylinder } |
| BAR_3D_CHART_VERT_STACKED_PYRAMID | Группирует этот набор типов рядов:<br/>            { ChartType.StackedPyramid } |
| BAR_3D_CHART_HORIZ_CLUSTERED | Группирует этот набор типов рядов:<br/>            { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_STACKED_BAR_3D | Группирует этот набор типов рядов:<br/>            { ChartType.StackedBar3D } |
| BAR_3D_CHART_HORIZ_STACKED_CONE | Группирует этот набор типов рядов:<br/>            { ChartType.StackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_STACKED_CYLINDER | Группирует этот набор типов рядов:<br/>            { ChartType.StackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_STACKED_PYRAMID | Группирует этот набор типов рядов:<br/>            { ChartType.StackedHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_BAR_3D | Группирует этот набор типов рядов:<br/>            { ChartType.PercentsStackedBar3D } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CONE | Группирует этот набор типов рядов:<br/>            { ChartType.PercentsStackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CYLINDER | Группирует этот набор типов рядов:<br/>            { ChartType.PercentsStackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_PYRAMID | Группирует этот набор типов рядов:<br/>            { ChartType.PercentsStackedHorizontalPyramid } |
| BAR_OF_PIE_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.BarOfPie } |
| PIE_OF_PIE_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.PieOfPie } |
| SURFACE_CHART_CONTOUR | Группирует этот набор типов рядов:<br/>            { ChartType.Contour } |
| SURFACE_CHART_WIREFRAME_CONTOUR | Группирует этот набор типов рядов:<br/>            { ChartType.WireframeContour } |
| SURFACE_CHART_SURFACE_3D | Группирует этот набор типов рядов:<br/>            { ChartType.Surface3D } |
| SURFACE_CHART_WIREFRAME_SURFACE_3D | Группирует этот набор типов рядов:<br/>            { ChartType.WireframeSurface3D } |
| BUBBLE_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.Bubble, ChartType.BubbleWith3D } |
| HISTOGRAM_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.Histogram } |
| PARETO_LINE_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.ParetoLine } |
| BOX_AND_WHISKER_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.BoxAndWhisker } |
| WATERFALL_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.Waterfall } |
| FUNNEL_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.Funnel } |
| TREEMAP_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.Treemap } |
| MAP_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.Map } |
| SUNBURST_CHART | Группирует этот набор типов рядов:<br/>            { ChartType.Sunburst } |

### См. также
* module [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)