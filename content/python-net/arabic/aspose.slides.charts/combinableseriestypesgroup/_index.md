---
title: CombinableSeriesTypesGroup enumeration
second_title: Aspose.Slides لـ Python عبر مرجع API الخاص بـ .NET
description: 
type: docs
url: /ar/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup التعداد

تعداد مجموعات أنواع السلاسل القابلة للجمع.  
            كل عنصر يتعلق بمجموعة من أنواع سلاسل المخطط التي يمكن أن تتواجد في وقت واحد داخل مجموعة ChartSeriesGroup واحدة.  
            على سبيل المثال: لا يمكن أن تكون سلسلة ChartType.PercentsStackedArea متزامنة مع سلسلة ChartType.StackedArea في مجموعة ChartSeriesGroup واحدة. ولكن يمكن أن تكون سلسلتان أو أكثر من ChartType.PercentsStackedArea في مجموعة ChartSeriesGroup واحدة في نفس الوقت (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). ويمكن أن تكون سلسلة ChartType.Line مع سلسلة ChartType.LineWithMarkers في نفس الوقت داخل مجموعة CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

نوع CombinableSeriesTypesGroup يعرّف الأعضاء التاليين:

## الحقول

| الحقل | الوصف |
| :- | :- |
| AREA_CHART_AREA | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Area } |
| AREA_CHART_PERCENTS_STACKED_AREA | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.PercentsStackedArea } |
| AREA_CHART_STACKED_AREA | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.StackedArea } |
| AREA_CHART_AREA_3D | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Area3D } |
| AREA_CHART_STACKED_AREA_3D | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.StackedArea3D } |
| AREA_CHART_PERCENTS_STACKED_AREA_3D | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.PercentsStackedArea3D } |
| LINE_CHART_LINE | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Line, ChartType.LineWithMarkers } |
| LINE_CHART_STACKED_LINE | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LINE_CHART_PERCENTS_STACKED_LINE | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| LINE_3D_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Line3D } |
| STOCK_HIGH_LOW_CLOSE | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.HighLowClose } |
| STOCK_OPEN_HIGH_LOW_CLOSE | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.OpenHighLowClose } |
| STOCK_VOLUME_HIGH_LOW_CLOSE | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.VolumeHighLowClose } |
| STOCK_VOLUME_OPEN_HIGH_LOW_CLOSE | تجمّع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.VolumeOpenHighLowClose } |
| RADAR_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Radar, ChartType.RadarWithMarkers } |
| FILLED_RADAR_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.FilledRadar } |
| SCATTER_STRAIGHT_MARKER | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| SCATTER_SMOOTH_MARKER | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PIE_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Pie, ChartType.ExplodedPie } |
| PIE_3D_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DOUGHNUT_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BAR_CHART_VERT_CLUSTERED | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.ClusteredColumn } |
| BAR_CHART_VERT_STACKED | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.StackedColumn } |
| BAR_CHART_VERT_PERCENTS_STACKED | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.PercentsStackedColumn } |
| BAR_CHART_HORIZ_CLUSTERED | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.ClusteredBar } |
| BAR_CHART_HORIZ_STACKED | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.StackedBar } |
| BAR_CHART_HORIZ_PERCENTS_STACKED | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.PercentsStackedBar } |
| BAR_3D_CHART_VERT | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| BAR_3D_CHART_VERT_CLUSTERED | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_COLUMN_3D | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.PercentsStackedColumn3D } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CONE | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.PercentsStackedCone } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CYLINDER | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.PercentsStackedCylinder } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_PYRAMID | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.PercentsStackedPyramid } |
| BAR_3D_CHART_VERT_STACKED_COLUMN_3D | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.StackedColumn3D } |
| BAR_3D_CHART_VERT_STACKED_CONE | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.StackedCone } |
| BAR_3D_CHART_VERT_STACKED_CYLINDER | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.StackedCylinder } |
| BAR_3D_CHART_VERT_STACKED_PYRAMID | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.StackedPyramid } |
| BAR_3D_CHART_HORIZ_CLUSTERED | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_STACKED_BAR_3D | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.StackedBar3D } |
| BAR_3D_CHART_HORIZ_STACKED_CONE | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.StackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_STACKED_CYLINDER | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.StackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_STACKED_PYRAMID | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.StackedHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_BAR_3D | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.PercentsStackedBar3D } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CONE | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.PercentsStackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CYLINDER | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.PercentsStackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_PYRAMID | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.PercentsStackedHorizontalPyramid } |
| BAR_OF_PIE_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.BarOfPie } |
| PIE_OF_PIE_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.PieOfPie } |
| SURFACE_CHART_CONTOUR | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Contour } |
| SURFACE_CHART_WIREFRAME_CONTOUR | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.WireframeContour } |
| SURFACE_CHART_SURFACE_3D | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Surface3D } |
| SURFACE_CHART_WIREFRAME_SURFACE_3D | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.WireframeSurface3D } |
| BUBBLE_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Bubble, ChartType.BubbleWith3D } |
| HISTOGRAM_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Histogram } |
| PARETO_LINE_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.ParetoLine } |
| BOX_AND_WHISKER_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.BoxAndWhisker } |
| WATERFALL_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Waterfall } |
| FUNNEL_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Funnel } |
| TREEMAP_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Treemap } |
| MAP_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Map } |
| SUNBURST_CHART | تجمع هذه المجموعة من أنواع السلاسل:<br/>            { ChartType.Sunburst } |


### انظر أيضًا
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)