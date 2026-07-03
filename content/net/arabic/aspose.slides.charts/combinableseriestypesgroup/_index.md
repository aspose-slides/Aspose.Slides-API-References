---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes لـ .NET مرجع API
description: تعداد لمجموعات أنواع السلاسل القابلة للجمع. كل عنصر يتعلق بمجموعة من أنواع سلاسل المخططات التي يمكن أن توجد في وقت واحد داخل ChartSeriesGroup واحد. على سبيل المثال لا يمكن لسلسلة ChartType.PercentsStackedArea أن تكون في وقت واحد مع سلسلة ChartType.StackedArea داخل ChartSeriesGroup واحد. ولكن يمكن أن تكون سلسلتان أو أكثر من ChartType.PercentsStackedArea في ChartSeriesGroup واحد في نفس الوقت CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. ويمكن أن تكون سلسلة ChartType.Line مع سلسلة ChartType.LineWithMarkers في وقت واحد داخل CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
type: docs
weight: 1530
url: /ar/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup التعداد

تعداد لمجموعات أنواع السلاسل القابلة للجمع. كل عنصر يشير إلى مجموعة من أنواع سلاسل المخطط التي يمكن وجودها في وقت واحد داخل ChartSeriesGroup واحد. على سبيل المثال: لا يمكن لسلسلة ChartType.PercentsStackedArea أن تكون في نفس الوقت مع سلسلة ChartType.StackedArea داخل ChartSeriesGroup واحد. لكن يمكن وجود سلسلتين أو أكثر من ChartType.PercentsStackedArea في ChartSeriesGroup واحد في نفس الوقت (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). ويمكن أن تكون سلسلة ChartType.Line مع سلسلة ChartType.LineWithMarkers في نفس الوقت داخل CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

```csharp
public enum CombinableSeriesTypesGroup
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| AreaChart_Area | `4` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Line3D } |
| StockHighLowClose | `18` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Histogram } |
| ParetoLineChart | `54` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Waterfall } |
| FunnelChart | `57` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Funnel } |
| TreemapChart | `58` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Treemap } |
| MapChart | `59` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Map } |
| SunburstChart | `60` | يقوم بتجميع مجموعة أنواع السلاسل التالية: { ChartType.Sunburst } |

### أنظر أيضًا

* النطاق [Aspose.Slides.Charts](../../aspose.slides.charts)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->