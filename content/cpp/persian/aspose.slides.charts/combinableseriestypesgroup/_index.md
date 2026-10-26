---
title: CombinableSeriesTypesGroup
second_title: مرجع API Aspose.Slides برای C++
description: "شمارشی از گروه‌های انواع سری‌های ترکیبی. هر عنصر به گروهی از انواع سری‌های نمودار مربوط می‌شود که می‌توانند به‌طور همزمان در یک ChartSeriesGroup باقی بمانند. به‌عنوان مثال: سری ChartType::PercentsStackedArea نمی‌تواند به‌صورت همزمان با سری ChartType::StackedArea در یک ChartSeriesGroup وجود داشته باشد. اما دو یا چند سری ChartType::PercentsStackedArea می‌توانند به‌صورت همزمان در یک ChartSeriesGroup باشند (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea). و سری ChartType::Line می‌تواند به‌صورت همزمان با سری ChartType::LineWithMarkers در یک CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup باشد."
type: docs
weight: 1496
url: /fa/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enum

شمارش گروه‌های انواع سری‌های ترکیبی. هر عنصر به گروهی از انواع سری‌های نمودار که می‌توانند به‌صورت همزمان در یک [ChartSeriesGroup](../chartseriesgroup/) باقی بمانند، مرتبط است. به‌عنوان مثال: سری [ChartType::PercentsStackedArea](../charttype/) نمی‌تواند به‌صورت همزمان با سری [ChartType::StackedArea](../charttype/) در یک [ChartSeriesGroup](../chartseriesgroup/) باشد. اما دو یا چند [ChartType::PercentsStackedArea](../charttype/) می‌توانند به‌صورت همزمان در یک [ChartSeriesGroup](../chartseriesgroup/) قرار گیرند ([CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)). و سری [ChartType::Line](../charttype/) می‌تواند به‌صورت همزمان با سری [ChartType::LineWithMarkers](../charttype/) در یک [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/) باشد.

```cpp
enum class CombinableSeriesTypesGroup
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| AreaChart_Area | 4 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: { [ChartType::Sunburst](../charttype/) } |

## موارد مرتبط

* فضای نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)