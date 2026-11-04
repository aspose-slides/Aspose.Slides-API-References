---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes لـ .NET مرجع API
description: تعداد لمجموعات أنواع السلاسل القابلة للدمج. كل عنصر يتعلق بمجموعة من أنواع سلاسل المخطط التي يمكن أن تتواجد في وقت واحد داخل ChartSeriesGroup واحدة. على سبيل المثال لا يمكن لسلاسل ChartType.PercentsStackedArea أن تكون في نفس الوقت مع سلاسل ChartType.StackedArea في ChartSeriesGroup واحدة. لكن يمكن لسلسلتين أو أكثر من ChartType.PercentsStackedArea أن تكون في ChartSeriesGroup واحدة في نفس الوقت CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. ويمكن لسلاسل ChartType.Line أن تكون مع سلاسل ChartType.LineWithMarkers في نفس الوقت في CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
type: docs
weight: 1540
url: /ar/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup التعداد

التعداد لمجموعات أنواع السلاسل القابلة للدمج. كل عنصر يتعلق بمجموعة من أنواع سلاسل المخطط التي يمكن أن تتواجد في وقت واحد داخل مجموعة ChartSeriesGroup واحدة. على سبيل المثال: لا يمكن أن توجد سلاسل ChartType.PercentsStackedArea في نفس الوقت مع سلاسل ChartType.StackedArea في مجموعة ChartSeriesGroup واحدة. لكن يمكن أن تكون سلاسل ChartType.PercentsStackedArea متعددة في مجموعة ChartSeriesGroup واحدة في وقت واحد (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). ويمكن أن تكون سلاسل ChartType.Line مع سلاسل ChartType.LineWithMarkers في نفس الوقت في مجموعة CombinableSeriesTypesGroup.LineChart_Line واحدة.

```csharp
public enum CombinableSeriesTypesGroup
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| AreaChart_Area | `4` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Line3D } |
| StockHighLowClose | `18` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Histogram } |
| ParetoLineChart | `54` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Waterfall } |
| FunnelChart | `57` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Funnel } |
| TreemapChart | `58` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Treemap } |
| MapChart | `59` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Map } |
| SunburstChart | `60` | تجمع مجموعة أنواع السلاسل التالية: { ChartType.Sunburst } |

### انظر أيضًا

* نطاق الاسم [Aspose.Slides.Charts](../../aspose.slides.charts)
* التجميع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->