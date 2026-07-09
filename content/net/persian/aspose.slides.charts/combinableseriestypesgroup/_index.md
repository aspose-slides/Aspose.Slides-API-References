---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes برای .NET مرجع API
description: شمارشی از گروه‌های انواع سری‌های ترکیبی. هر عنصر به گروهی از انواع سری‌های نمودار که می‌توانند به‌صورت همزمان در یک ChartSeriesGroup حضور داشته باشند، مرتبط است. برای مثال، سری ChartType.PercentsStackedArea نمی‌تواند به‌صورت همزمان با سری ChartType.StackedArea در یک ChartSeriesGroup موجود باشد. اما دو یا چند سری ChartType.PercentsStackedArea می‌توانند به‌طور همزمان در یک ChartSeriesGroup وجود داشته باشند: CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. و سری ChartType.Line می‌تواند به‌صورت همزمان با سری ChartType.LineWithMarkers در یک ChartSeriesGroup از نوع CombinableSeriesTypesGroup.LineChart_Line وجود داشته باشد.
type: docs
weight: 1530
url: /fa/aspose.slides.charts/combinableseriestypesgroup/
---
## شمارش CombinableSeriesTypesGroup

شمارشی از گروه‌های انواع سری‌های ترکیبی. هر عنصر به گروهی از انواع سری‌های نمودار که می‌توانند به‌طور همزمان در یک ChartSeriesGroup حضور داشته باشند، مرتبط است. به‌عنوان مثال: ChartType.PercentsStackedArea سری نمی‌تواند به‌طور همزمان با ChartType.StackedArea سری در یک ChartSeriesGroup وجود داشته باشد. اما دو یا چند ChartType.PercentsStackedArea می‌توانند به‌طور همزمان در یک ChartSeriesGroup باشند (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). و ChartType.Line سری می‌تواند به‌طور همزمان با ChartType.LineWithMarkers سری در یک ChartSeriesGroup از نوع CombinableSeriesTypesGroup.LineChart_Line باشد.

```csharp
public enum CombinableSeriesTypesGroup
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| AreaChart_Area | `4` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Line3D } |
| StockHighLowClose | `18` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Histogram } |
| ParetoLineChart | `54` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Waterfall } |
| FunnelChart | `57` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Funnel } |
| TreemapChart | `58` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Treemap } |
| MapChart | `59` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Map } |
| SunburstChart | `60` | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { ChartType.Sunburst } |

### موارد مرتبط

* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->