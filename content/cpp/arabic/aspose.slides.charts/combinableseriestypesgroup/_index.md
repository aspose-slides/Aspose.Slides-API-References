---
title: CombinableSeriesTypesGroup
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "تعداد مجموعات الأنواع القابلة للجمع من السلاسل. كل عنصر يرتبط بمجموعة من أنواع سلاسل المخطط التي يمكن أن تتواجد في وقت واحد في مجموعة ChartSeriesGroup واحدة. على سبيل المثال: لا يمكن لسلسلة ChartType::PercentsStackedArea أن تكون في وقت واحد مع سلسلة ChartType::StackedArea في مجموعة ChartSeriesGroup واحدة. لكن يمكن لاثنين أو أكثر من ChartType::PercentsStackedArea أن يكونوا في مجموعة ChartSeriesGroup واحدة في وقت واحد (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea). ويمكن لسلسلة ChartType::Line أن تكون مع سلسلة ChartType::LineWithMarkers في وقت واحد في مجموعة CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup."
type: docs
weight: 1496
url: /ar/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enum

تعداد مجموعات الأنواع القابلة للجمع من السلاسل. كل عنصر يرتبط بمجموعة من أنواع سلاسل المخطط التي يمكن أن تتواجد في وقت واحد في [ChartSeriesGroup](../chartseriesgroup/) واحد. على سبيل المثال: لا يمكن لسلسلة [ChartType::PercentsStackedArea](../charttype/) أن تكون في وقت واحد مع سلسلة [ChartType::StackedArea](../charttype/) في [ChartSeriesGroup](../chartseriesgroup/) واحد. لكن يمكن لاثنين أو أكثر من [ChartType::PercentsStackedArea](../charttype/) أن يكونوا في [ChartSeriesGroup](../chartseriesgroup/) واحد في وقت واحد ([CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)). ويمكن لسلسلة [ChartType::Line](../charttype/) أن تكون مع سلسلة [ChartType::LineWithMarkers](../charttype/) في وقت واحد في [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/) واحد.

```cpp
enum class CombinableSeriesTypesGroup
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| AreaChart_Area | 4 | Groups this set of series types: { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | Groups this set of series types: { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | Groups this set of series types: { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | Groups this set of series types: { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | Groups this set of series types: { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | Groups this set of series types: { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | Groups this set of series types: { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | Groups this set of series types: { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | Groups this set of series types: { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | Groups this set of series types: { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | Groups this set of series types: { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | Groups this set of series types: { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | Groups this set of series types: { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | Groups this set of series types: { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | Groups this set of series types: { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | Groups this set of series types: { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | Groups this set of series types: { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | Groups this set of series types: { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | Groups this set of series types: { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | Groups this set of series types: { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | Groups this set of series types: { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | Groups this set of series types: { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | Groups this set of series types: { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | Groups this set of series types: { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | Groups this set of series types: { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | Groups this set of series types: { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | Groups this set of series types: { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | Groups this set of series types: { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | Groups this set of series types: { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | Groups this set of series types: { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | Groups this set of series types: { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | Groups this set of series types: { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | Groups this set of series types: { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | Groups this set of series types: { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | Groups this set of series types: { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | Groups this set of series types: { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | Groups this set of series types: { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | Groups this set of series types: { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | Groups this set of series types: { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | Groups this set of series types: { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | Groups this set of series types: { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | Groups this set of series types: { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | Groups this set of series types: { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | Groups this set of series types: { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | Groups this set of series types: { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | Groups this set of series types: { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | Groups this set of series types: { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | Groups this set of series types: { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | Groups this set of series types: { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | Groups this set of series types: { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | Groups this set of series types: { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | Groups this set of series types: { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | Groups this set of series types: { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | Groups this set of series types: { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | Groups this set of series types: { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | Groups this set of series types: { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | Groups this set of series types: { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | Groups this set of series types: { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | Groups this set of series types: { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | Groups this set of series types: { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | Groups this set of series types: { [ChartType::Sunburst](../charttype/) } |

## انظر أيضًا

* نطاق [Aspose::Slides::Charts](../)
* المكتبة [Aspose.Slides](../../)