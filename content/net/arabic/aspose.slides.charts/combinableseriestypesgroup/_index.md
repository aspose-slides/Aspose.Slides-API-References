---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes لـ .NET مرجع API
description: تعداد لمجموعات أنواع السلاسل القابلة للجمع. كل عنصر يتعلق بمجموعة من أنواع سلاسل المخطط التي يمكن أن تتواجد في وقت واحد في ChartSeriesGroup واحدة. على سبيل المثال لا يمكن لسلسلة ChartType.PercentsStackedArea أن تكون متزامنة مع سلسلة ChartType.StackedArea في ChartSeriesGroup واحدة. ولكن يمكن لسلسلتين أو أكثر من ChartType.PercentsStackedArea أن تكون في ChartSeriesGroup واحدة في نفس الوقت CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. ويمكن لسلسلة ChartType.Line أن تكون مع سلسلة ChartType.LineWithMarkers في نفس الوقت في CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
type: docs
weight: 1530
url: /ar/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup تعداد

تعداد مجموعات أنواع السلاسل القابلة للجمع. كل عنصر يتعلق بمجموعة من أنواع سلاسل المخطط التي يمكن أن تتواجد في وقت واحد داخل مجموعة ChartSeriesGroup واحدة. على سبيل المثال: لا يمكن لسلسلة ChartType.PercentsStackedArea أن تكون متزامنة مع سلسلة ChartType.StackedArea في مجموعة ChartSeriesGroup واحدة. ولكن يمكن لسلسلتين أو أكثر من ChartType.PercentsStackedArea أن تكون في مجموعة ChartSeriesGroup واحدة في نفس الوقت (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). ويمكن لسلسلة ChartType.Line أن تكون مع سلسلة ChartType.LineWithMarkers في نفس الوقت داخل مجموعة CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

```csharp
public enum CombinableSeriesTypesGroup
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| AreaChart_Area | `4` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Line3D } |
| StockHighLowClose | `18` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Histogram } |
| ParetoLineChart | `54` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Waterfall } |
| FunnelChart | `57` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Funnel } |
| TreemapChart | `58` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Treemap } |
| MapChart | `59` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Map } |
| SunburstChart | `60` | يقوم بتجميع مجموعة الأنواع التالية من السلاسل: { ChartType.Sunburst } |

### انظر أيضًا

* مساحة الاسم [Aspose.Slides.Charts](../../aspose.slides.charts)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->