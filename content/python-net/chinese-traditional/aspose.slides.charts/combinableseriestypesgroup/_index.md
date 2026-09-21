---
title: CombinableSeriesTypesGroup enumeration
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup 列舉

列舉可組合系列類型的群組。  
每個元素與一組可同時存在於同一 ChartSeriesGroup 中的圖表系列類型相關。  
例如：ChartType.PercentsStackedArea 系列無法與 ChartType.StackedArea 系列同時出現在同一 ChartSeriesGroup 中。  
但兩個或以上的 ChartType.PercentsStackedArea 可以同時位於同一 ChartSeriesGroup 中 (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea)。  
且 ChartType.Line 系列可以與 ChartType.LineWithMarkers 系列同時位於同一 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup 中。

CombinableSeriesTypesGroup 類型公開以下成員：

## 欄位

| 欄位 | 說明 |
| :- | :- |
| AREA_CHART_AREA | 將此系列類型集合分組：<br/>            { ChartType.Area } |
| AREA_CHART_PERCENTS_STACKED_AREA | 將此系列類型集合分組：<br/>            { ChartType.PercentsStackedArea } |
| AREA_CHART_STACKED_AREA | 將此系列類型集合分組：<br/>            { ChartType.StackedArea } |
| AREA_CHART_AREA_3D | 將此系列類型集合分組：<br/>            { ChartType.Area3D } |
| AREA_CHART_STACKED_AREA_3D | 將此系列類型集合分組：<br/>            { ChartType.StackedArea3D } |
| AREA_CHART_PERCENTS_STACKED_AREA_3D | 將此系列類型集合分組：<br/>            { ChartType.PercentsStackedArea3D } |
| LINE_CHART_LINE | 將此系列類型集合分組：<br/>            { ChartType.Line, ChartType.LineWithMarkers } |
| LINE_CHART_STACKED_LINE | 將此系列類型集合分組：<br/>            { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LINE_CHART_PERCENTS_STACKED_LINE | 將此系列類型集合分組：<br/>            { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| LINE_3D_CHART | 將此系列類型集合分組：<br/>            { ChartType.Line3D } |
| STOCK_HIGH_LOW_CLOSE | 將此系列類型集合分組：<br/>            { ChartType.HighLowClose } |
| STOCK_OPEN_HIGH_LOW_CLOSE | 將此系列類型集合分組：<br/>            { ChartType.OpenHighLowClose } |
| STOCK_VOLUME_HIGH_LOW_CLOSE | 將此系列類型集合分組：<br/>            { ChartType.VolumeHighLowClose } |
| STOCK_VOLUME_OPEN_HIGH_LOW_CLOSE | 將此系列類型集合分組：<br/>            { ChartType.VolumeOpenHighLowClose } |
| RADAR_CHART | 將此系列類型集合分組：<br/>            { ChartType.Radar, ChartType.RadarWithMarkers } |
| FILLED_RADAR_CHART | 將此系列類型集合分組：<br/>            { ChartType.FilledRadar } |
| SCATTER_STRAIGHT_MARKER | 將此系列類型集合分組：<br/>            { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| SCATTER_SMOOTH_MARKER | 將此系列類型集合分組：<br/>            { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PIE_CHART | 將此系列類型集合分組：<br/>            { ChartType.Pie, ChartType.ExplodedPie } |
| PIE_3D_CHART | 將此系列類型集合分組：<br/>            { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DOUGHNUT_CHART | 將此系列類型集合分組：<br/>            { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BAR_CHART_VERT_CLUSTERED | 將此系列類型集合分組：<br/>            { ChartType.ClusteredColumn } |
| BAR_CHART_VERT_STACKED | 將此系列類型集合分組：<br/>            { ChartType.StackedColumn } |
| BAR_CHART_VERT_PERCENTS_STACKED | 將此系列類型集合分組：<br/>            { ChartType.PercentsStackedColumn } |
| BAR_CHART_HORIZ_CLUSTERED | 將此系列類型集合分組：<br/>            { ChartType.ClusteredBar } |
| BAR_CHART_HORIZ_STACKED | 將此系列類型集合分組：<br/>            { ChartType.StackedBar } |
| BAR_CHART_HORIZ_PERCENTS_STACKED | 將此系列類型集合分組：<br/>            { ChartType.PercentsStackedBar } |
| BAR_3D_CHART_VERT | 將此系列類型集合分組：<br/>            { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| BAR_3D_CHART_VERT_CLUSTERED | 將此系列類型集合分組：<br/>            { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_COLUMN_3D | 將此系列類型集合分組：<br/>            { ChartType.PercentsStackedColumn3D } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CONE | 將此系列類型集合分組：<br/>            { ChartType.PercentsStackedCone } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CYLINDER | 將此系列類型集合分組：<br/>            { ChartType.PercentsStackedCylinder } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_PYRAMID | 將此系列類型集合分組：<br/>            { ChartType.PercentsStackedPyramid } |
| BAR_3D_CHART_VERT_STACKED_COLUMN_3D | 將此系列類型集合分組：<br/>            { ChartType.StackedColumn3D } |
| BAR_3D_CHART_VERT_STACKED_CONE | 將此系列類型集合分組：<br/>            { ChartType.StackedCone } |
| BAR_3D_CHART_VERT_STACKED_CYLINDER | 將此系列類型集合分組：<br/>            { ChartType.StackedCylinder } |
| BAR_3D_CHART_VERT_STACKED_PYRAMID | 將此系列類型集合分組：<br/>            { ChartType.StackedPyramid } |
| BAR_3D_CHART_HORIZ_CLUSTERED | 將此系列類型集合分組：<br/>            { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_STACKED_BAR_3D | 將此系列類型集合分組：<br/>            { ChartType.StackedBar3D } |
| BAR_3D_CHART_HORIZ_STACKED_CONE | 將此系列類型集合分組：<br/>            { ChartType.StackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_STACKED_CYLINDER | 將此系列類型集合分組：<br/>            { ChartType.StackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_STACKED_PYRAMID | 將此系列類型集合分組：<br/>            { ChartType.StackedHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_BAR_3D | 將此系列類型集合分組：<br/>            { ChartType.PercentsStackedBar3D } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CONE | 將此系列類型集合分組：<br/>            { ChartType.PercentsStackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CYLINDER | 將此系列類型集合分組：<br/>            { ChartType.PercentsStackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_PYRAMID | 將此系列類型集合分組：<br/>            { ChartType.PercentsStackedHorizontalPyramid } |
| BAR_OF_PIE_CHART | 將此系列類型集合分組：<br/>            { ChartType.BarOfPie } |
| PIE_OF_PIE_CHART | 將此系列類型集合分組：<br/>            { ChartType.PieOfPie } |
| SURFACE_CHART_CONTOUR | 將此系列類型集合分組：<br/>            { ChartType.Contour } |
| SURFACE_CHART_WIREFRAME_CONTOUR | 將此系列類型集合分組：<br/>            { ChartType.WireframeContour } |
| SURFACE_CHART_SURFACE_3D | 將此系列類型集合分組：<br/>            { ChartType.Surface3D } |
| SURFACE_CHART_WIREFRAME_SURFACE_3D | 將此系列類型集合分組：<br/>            { ChartType.WireframeSurface3D } |
| BUBBLE_CHART | 將此系列類型集合分組：<br/>            { ChartType.Bubble, ChartType.BubbleWith3D } |
| HISTOGRAM_CHART | 將此系列類型集合分組：<br/>            { ChartType.Histogram } |
| PARETO_LINE_CHART | 將此系列類型集合分組：<br/>            { ChartType.ParetoLine } |
| BOX_AND_WHISKER_CHART | 將此系列類型集合分組：<br/>            { ChartType.BoxAndWhisker } |
| WATERFALL_CHART | 將此系列類型集合分組：<br/>            { ChartType.Waterfall } |
| FUNNEL_CHART | 將此系列類型集合分組：<br/>            { ChartType.Funnel } |
| TREEMAP_CHART | 將此系列類型集合分組：<br/>            { ChartType.Treemap } |
| MAP_CHART | 將此系列類型集合分組：<br/>            { ChartType.Map } |
| SUNBURST_CHART | 將此系列類型集合分組：<br/>            { ChartType.Sunburst } |


### 另請參閱
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)