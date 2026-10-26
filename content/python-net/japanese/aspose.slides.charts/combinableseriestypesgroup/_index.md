---
title: CombinableSeriesTypesGroup enumeration
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup 列挙

組み合わせ可能なシリーズタイプのグループの列挙です。  
各要素は、1つの ChartSeriesGroup 内で同時に存在できるチャートシリーズのタイプのグループに対応します。  
例として、ChartType.PercentsStackedArea 系列は ChartType.StackedArea 系列と同時に 1つの ChartSeriesGroup 内に存在できません。ただし、ChartType.PercentsStackedArea を 2 つ以上同時に 1つの ChartSeriesGroup に含めることは可能です (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea)。また、ChartType.Line 系列は ChartType.LineWithMarkers 系列と同時に 1つの CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup に含めることができます。

CombinableSeriesTypesGroup 型は次のメンバーを公開します：

## フィールド

| Field | Description |
| :- | :- |
| AREA_CHART_AREA | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Area } |
| AREA_CHART_PERCENTS_STACKED_AREA | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.PercentsStackedArea } |
| AREA_CHART_STACKED_AREA | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.StackedArea } |
| AREA_CHART_AREA_3D | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Area3D } |
| AREA_CHART_STACKED_AREA_3D | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.StackedArea3D } |
| AREA_CHART_PERCENTS_STACKED_AREA_3D | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.PercentsStackedArea3D } |
| LINE_CHART_LINE | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Line, ChartType.LineWithMarkers } |
| LINE_CHART_STACKED_LINE | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LINE_CHART_PERCENTS_STACKED_LINE | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| LINE_3D_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Line3D } |
| STOCK_HIGH_LOW_CLOSE | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.HighLowClose } |
| STOCK_OPEN_HIGH_LOW_CLOSE | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.OpenHighLowClose } |
| STOCK_VOLUME_HIGH_LOW_CLOSE | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.VolumeHighLowClose } |
| STOCK_VOLUME_OPEN_HIGH_LOW_CLOSE | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.VolumeOpenHighLowClose } |
| RADAR_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Radar, ChartType.RadarWithMarkers } |
| FILLED_RADAR_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.FilledRadar } |
| SCATTER_STRAIGHT_MARKER | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| SCATTER_SMOOTH_MARKER | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PIE_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Pie, ChartType.ExplodedPie } |
| PIE_3D_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DOUGHNUT_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BAR_CHART_VERT_CLUSTERED | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.ClusteredColumn } |
| BAR_CHART_VERT_STACKED | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.StackedColumn } |
| BAR_CHART_VERT_PERCENTS_STACKED | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.PercentsStackedColumn } |
| BAR_CHART_HORIZ_CLUSTERED | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.ClusteredBar } |
| BAR_CHART_HORIZ_STACKED | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.StackedBar } |
| BAR_CHART_HORIZ_PERCENTS_STACKED | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.PercentsStackedBar } |
| BAR_3D_CHART_VERT | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| BAR_3D_CHART_VERT_CLUSTERED | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_COLUMN_3D | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.PercentsStackedColumn3D } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CONE | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.PercentsStackedCone } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CYLINDER | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.PercentsStackedCylinder } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_PYRAMID | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.PercentsStackedPyramid } |
| BAR_3D_CHART_VERT_STACKED_COLUMN_3D | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.StackedColumn3D } |
| BAR_3D_CHART_VERT_STACKED_CONE | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.StackedCone } |
| BAR_3D_CHART_VERT_STACKED_CYLINDER | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.StackedCylinder } |
| BAR_3D_CHART_VERT_STACKED_PYRAMID | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.StackedPyramid } |
| BAR_3D_CHART_HORIZ_CLUSTERED | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_STACKED_BAR_3D | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.StackedBar3D } |
| BAR_3D_CHART_HORIZ_STACKED_CONE | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.StackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_STACKED_CYLINDER | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.StackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_STACKED_PYRAMID | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.StackedHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_BAR_3D | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.PercentsStackedBar3D } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CONE | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.PercentsStackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CYLINDER | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.PercentsStackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_PYRAMID | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.PercentsStackedHorizontalPyramid } |
| BAR_OF_PIE_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.BarOfPie } |
| PIE_OF_PIE_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.PieOfPie } |
| SURFACE_CHART_CONTOUR | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Contour } |
| SURFACE_CHART_WIREFRAME_CONTOUR | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.WireframeContour } |
| SURFACE_CHART_SURFACE_3D | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Surface3D } |
| SURFACE_CHART_WIREFRAME_SURFACE_3D | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.WireframeSurface3D } |
| BUBBLE_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Bubble, ChartType.BubbleWith3D } |
| HISTOGRAM_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Histogram } |
| PARETO_LINE_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.ParetoLine } |
| BOX_AND_WHISKER_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.BoxAndWhisker } |
| WATERFALL_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Waterfall } |
| FUNNEL_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Funnel } |
| TREEMAP_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Treemap } |
| MAP_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Map } |
| SUNBURST_CHART | このシリーズタイプのセットをグループ化します:<br/>            { ChartType.Sunburst } |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)