---
title: CombinableSeriesTypesGroup enumeration
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET API Reference
description: 
type: docs
url: /th/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeration

การแสดงรายการของกลุ่มประเภทซีรีส์ที่สามารถรวมกันได้.  
แต่ละองค์ประกอบสัมพันธ์กับกลุ่มของประเภทซีรีส์แผนภูมิที่สามารถอยู่พร้อมกันได้ในหนึ่ง ChartSeriesGroup.  
ตัวอย่างเช่น: ซีรีส์ ChartType.PercentsStackedArea ไม่สามารถอยู่พร้อมกับซีรีส์ ChartType.StackedArea ในหนึ่ง ChartSeriesGroup ได้. แต่สองหรือมากกว่า ChartType.PercentsStackedArea สามารถอยู่ในหนึ่ง ChartSeriesGroup พร้อมกันได้ (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). และซีรีส์ ChartType.Line สามารถอยู่กับซีรีส์ ChartType.LineWithMarkers พร้อมกันได้ในหนึ่ง CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

The CombinableSeriesTypesGroup type exposes the following members:

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| :- | :- |
| AREA_CHART_AREA | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Area } |
| AREA_CHART_PERCENTS_STACKED_AREA | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.PercentsStackedArea } |
| AREA_CHART_STACKED_AREA | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.StackedArea } |
| AREA_CHART_AREA_3D | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Area3D } |
| AREA_CHART_STACKED_AREA_3D | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.StackedArea3D } |
| AREA_CHART_PERCENTS_STACKED_AREA_3D | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.PercentsStackedArea3D } |
| LINE_CHART_LINE | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Line, ChartType.LineWithMarkers } |
| LINE_CHART_STACKED_LINE | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LINE_CHART_PERCENTS_STACKED_LINE | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| LINE_3D_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Line3D } |
| STOCK_HIGH_LOW_CLOSE | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.HighLowClose } |
| STOCK_OPEN_HIGH_LOW_CLOSE | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.OpenHighLowClose } |
| STOCK_VOLUME_HIGH_LOW_CLOSE | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.VolumeHighLowClose } |
| STOCK_VOLUME_OPEN_HIGH_LOW_CLOSE | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.VolumeOpenHighLowClose } |
| RADAR_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Radar, ChartType.RadarWithMarkers } |
| FILLED_RADAR_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.FilledRadar } |
| SCATTER_STRAIGHT_MARKER | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| SCATTER_SMOOTH_MARKER | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PIE_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Pie, ChartType.ExplodedPie } |
| PIE_3D_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DOUGHNUT_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BAR_CHART_VERT_CLUSTERED | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.ClusteredColumn } |
| BAR_CHART_VERT_STACKED | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.StackedColumn } |
| BAR_CHART_VERT_PERCENTS_STACKED | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.PercentsStackedColumn } |
| BAR_CHART_HORIZ_CLUSTERED | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.ClusteredBar } |
| BAR_CHART_HORIZ_STACKED | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.StackedBar } |
| BAR_CHART_HORIZ_PERCENTS_STACKED | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.PercentsStackedBar } |
| BAR_3D_CHART_VERT | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| BAR_3D_CHART_VERT_CLUSTERED | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_COLUMN_3D | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.PercentsStackedColumn3D } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CONE | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.PercentsStackedCone } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CYLINDER | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.PercentsStackedCylinder } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_PYRAMID | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.PercentsStackedPyramid } |
| BAR_3D_CHART_VERT_STACKED_COLUMN_3D | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.StackedColumn3D } |
| BAR_3D_CHART_VERT_STACKED_CONE | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.StackedCone } |
| BAR_3D_CHART_VERT_STACKED_CYLINDER | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.StackedCylinder } |
| BAR_3D_CHART_VERT_STACKED_PYRAMID | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.StackedPyramid } |
| BAR_3D_CHART_HORIZ_CLUSTERED | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_STACKED_BAR_3D | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.StackedBar3D } |
| BAR_3D_CHART_HORIZ_STACKED_CONE | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.StackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_STACKED_CYLINDER | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.StackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_STACKED_PYRAMID | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.StackedHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_BAR_3D | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.PercentsStackedBar3D } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CONE | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.PercentsStackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CYLINDER | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.PercentsStackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_PYRAMID | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.PercentsStackedHorizontalPyramid } |
| BAR_OF_PIE_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.BarOfPie } |
| PIE_OF_PIE_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.PieOfPie } |
| SURFACE_CHART_CONTOUR | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Contour } |
| SURFACE_CHART_WIREFRAME_CONTOUR | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.WireframeContour } |
| SURFACE_CHART_SURFACE_3D | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Surface3D } |
| SURFACE_CHART_WIREFRAME_SURFACE_3D | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.WireframeSurface3D } |
| BUBBLE_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Bubble, ChartType.BubbleWith3D } |
| HISTOGRAM_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Histogram } |
| PARETO_LINE_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.ParetoLine } |
| BOX_AND_WHISKER_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.BoxAndWhisker } |
| WATERFALL_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Waterfall } |
| FUNNEL_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Funnel } |
| TREEMAP_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Treemap } |
| MAP_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Map } |
| SUNBURST_CHART | จัดกลุ่มชุดประเภทของ series นี้:<br/>            { ChartType.Sunburst } |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.charts`](/slides/python-net/th/aspose.slides.charts)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)