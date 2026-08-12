---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "संचयनशील श्रृंखला प्रकारों के समूहों का एन्यूमरेशन। प्रत्येक तत्व एक ChartSeriesGroup में एक साथ मौजूद रह सकने वाले चार्ट श्रृंखला प्रकारों के समूह से संबंधित है। उदाहरण के लिए: ChartType::PercentsStackedArea श्रृंखला ChartType::StackedArea श्रृंखला के साथ एक ChartSeriesGroup में एक साथ नहीं हो सकती। लेकिन दो या अधिक ChartType::PercentsStackedArea एक ChartSeriesGroup में एक साथ हो सकते हैं (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea)। और ChartType::Line श्रृंखला ChartType::LineWithMarkers श्रृंखला के साथ एक CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup में एक साथ हो सकती है।"
type: docs
weight: 1496
url: /hi/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enum

संचयनशील श्रृंखला प्रकारों के समूहों का एन्यूमरेशन। प्रत्येक तत्व [ChartSeriesGroup](../chartseriesgroup/) में एक साथ मौजूद रह सकने वाले चार्ट श्रृंखला प्रकारों के समूह से संबंधित है। उदाहरण के लिए: [ChartType::PercentsStackedArea](../charttype/) श्रृंखला [ChartSeriesGroup](../chartseriesgroup/) में [ChartType::StackedArea](../charttype/) श्रृंखला के साथ एक साथ नहीं हो सकती। लेकिन दो या अधिक [ChartType::PercentsStackedArea](../charttype/) एक साथ एक [ChartSeriesGroup](../chartseriesgroup/) में हो सकते हैं ([CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./))। और [ChartType::Line](../charttype/) श्रृंखला [ChartType::LineWithMarkers](../charttype/) श्रृंखला के साथ एक साथ एक [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/) में हो सकती है।

```cpp
enum class CombinableSeriesTypesGroup
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| AreaChart_Area | 4 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | इस श्रृंखला प्रकारों के सेट को समूहित करता है: { [ChartType::Sunburst](../charttype/) } |

## संबंधित देखें

* नामस्थान [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)