---
title: CombinableSeriesTypesGroup enumeration
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup 열거형

결합 가능한 시리즈 유형 그룹의 열거형입니다.
각 요소는 하나의 ChartSeriesGroup에서 동시에 존재할 수 있는 차트 시리즈 유형 그룹과 관련됩니다.
예를 들어: ChartType.PercentsStackedArea 시리즈는 ChartType.StackedArea 시리즈와 하나의 ChartSeriesGroup에서 동시에 존재할 수 없습니다.
하지만 두 개 이상의 ChartType.PercentsStackedArea 시리즈는 하나의 ChartSeriesGroup에 동시에 존재할 수 있습니다 (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). 또한 ChartType.Line 시리즈는 ChartType.LineWithMarkers 시리즈와 동시에 하나의 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup에 존재할 수 있습니다.

CombinableSeriesTypesGroup 유형은 다음 멤버를 노출합니다:

## 필드

| 필드 | 설명 |
| :- | :- |
| AREA_CHART_AREA | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Area } |
| AREA_CHART_PERCENTS_STACKED_AREA | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.PercentsStackedArea } |
| AREA_CHART_STACKED_AREA | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.StackedArea } |
| AREA_CHART_AREA_3D | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Area3D } |
| AREA_CHART_STACKED_AREA_3D | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.StackedArea3D } |
| AREA_CHART_PERCENTS_STACKED_AREA_3D | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.PercentsStackedArea3D } |
| LINE_CHART_LINE | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Line, ChartType.LineWithMarkers } |
| LINE_CHART_STACKED_LINE | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LINE_CHART_PERCENTS_STACKED_LINE | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| LINE_3D_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Line3D } |
| STOCK_HIGH_LOW_CLOSE | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.HighLowClose } |
| STOCK_OPEN_HIGH_LOW_CLOSE | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.OpenHighLowClose } |
| STOCK_VOLUME_HIGH_LOW_CLOSE | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.VolumeHighLowClose } |
| STOCK_VOLUME_OPEN_HIGH_LOW_CLOSE | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.VolumeOpenHighLowClose } |
| RADAR_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Radar, ChartType.RadarWithMarkers } |
| FILLED_RADAR_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.FilledRadar } |
| SCATTER_STRAIGHT_MARKER | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| SCATTER_SMOOTH_MARKER | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PIE_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Pie, ChartType.ExplodedPie } |
| PIE_3D_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DOUGHNUT_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BAR_CHART_VERT_CLUSTERED | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.ClusteredColumn } |
| BAR_CHART_VERT_STACKED | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.StackedColumn } |
| BAR_CHART_VERT_PERCENTS_STACKED | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.PercentsStackedColumn } |
| BAR_CHART_HORIZ_CLUSTERED | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.ClusteredBar } |
| BAR_CHART_HORIZ_STACKED | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.StackedBar } |
| BAR_CHART_HORIZ_PERCENTS_STACKED | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.PercentsStackedBar } |
| BAR_3D_CHART_VERT | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| BAR_3D_CHART_VERT_CLUSTERED | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_COLUMN_3D | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.PercentsStackedColumn3D } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CONE | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.PercentsStackedCone } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CYLINDER | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.PercentsStackedCylinder } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_PYRAMID | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.PercentsStackedPyramid } |
| BAR_3D_CHART_VERT_STACKED_COLUMN_3D | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.StackedColumn3D } |
| BAR_3D_CHART_VERT_STACKED_CONE | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.StackedCone } |
| BAR_3D_CHART_VERT_STACKED_CYLINDER | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.StackedCylinder } |
| BAR_3D_CHART_VERT_STACKED_PYRAMID | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.StackedPyramid } |
| BAR_3D_CHART_HORIZ_CLUSTERED | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_STACKED_BAR_3D | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.StackedBar3D } |
| BAR_3D_CHART_HORIZ_STACKED_CONE | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.StackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_STACKED_CYLINDER | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.StackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_STACKED_PYRAMID | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.StackedHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_BAR_3D | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.PercentsStackedBar3D } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CONE | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.PercentsStackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CYLINDER | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.PercentsStackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_PYRAMID | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.PercentsStackedHorizontalPyramid } |
| BAR_OF_PIE_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.BarOfPie } |
| PIE_OF_PIE_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.PieOfPie } |
| SURFACE_CHART_CONTOUR | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Contour } |
| SURFACE_CHART_WIREFRAME_CONTOUR | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.WireframeContour } |
| SURFACE_CHART_SURFACE_3D | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Surface3D } |
| SURFACE_CHART_WIREFRAME_SURFACE_3D | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.WireframeSurface3D } |
| BUBBLE_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Bubble, ChartType.BubbleWith3D } |
| HISTOGRAM_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Histogram } |
| PARETO_LINE_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.ParetoLine } |
| BOX_AND_WHISKER_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.BoxAndWhisker } |
| WATERFALL_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Waterfall } |
| FUNNEL_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Funnel } |
| TREEMAP_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Treemap } |
| MAP_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Map } |
| SUNBURST_CHART | 이 시리즈 유형 집합을 그룹화합니다:<br/>            { ChartType.Sunburst } |

### 참고
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)