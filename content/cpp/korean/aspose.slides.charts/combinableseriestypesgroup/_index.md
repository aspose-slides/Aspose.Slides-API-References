---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides for C++ API 레퍼런스
description: "조합 가능한 시리즈 유형 그룹을 열거합니다. 각 요소는 하나의 ChartSeriesGroup에 동시에 존재할 수 있는 차트 시리즈 유형 그룹과 관련됩니다. 예를 들어: ChartType::PercentsStackedArea 시리즈는 ChartType::StackedArea 시리즈와 하나의 ChartSeriesGroup에 동시에 존재할 수 없습니다. 그러나 두 개 이상의 ChartType::PercentsStackedArea는 하나의 ChartSeriesGroup에 동시에 존재할 수 있습니다 (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea). 또한 ChartType::Line 시리즈는 ChartType::LineWithMarkers 시리즈와 동시에 하나의 CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup에 존재할 수 있습니다."
type: docs
weight: 1496
url: /ko/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enum

조합 가능한 시리즈 유형 그룹을 열거합니다. 각 요소는 하나의 [ChartSeriesGroup](../chartseriesgroup/)에 동시에 존재할 수 있는 차트 시리즈 유형 그룹과 관련됩니다. 예를 들어: [ChartType::PercentsStackedArea](../charttype/) 시리즈는 [ChartType::StackedArea](../charttype/) 시리즈와 하나의 [ChartSeriesGroup](../chartseriesgroup/)에 동시에 존재할 수 없습니다. 그러나 두 개 이상의 [ChartType::PercentsStackedArea](../charttype/)은 하나의 [ChartSeriesGroup](../chartseriesgroup/)에 동시에 존재할 수 있습니다([CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)). 또한 [ChartType::Line](../charttype/) 시리즈는 [ChartType::LineWithMarkers](../charttype/) 시리즈와 동시에 하나의 [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/)에 존재할 수 있습니다.

```cpp
enum class CombinableSeriesTypesGroup
```

### Values

| 이름 | 값 | 설명 |
| --- | --- | --- |
| AreaChart_Area | 4 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | 이 시리즈 유형 집합을 그룹화합니다: { [ChartType::Sunburst](../charttype/) } |

## 참조

* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)