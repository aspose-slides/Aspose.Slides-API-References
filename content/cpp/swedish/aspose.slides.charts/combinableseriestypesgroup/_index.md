---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides för C++ API-referens
description: "Uppräkning av grupper av kombinerbara serietyper. Varje element relaterar till en grupp av typer av diagramserier som kan finnas samtidigt i en ChartSeriesGroup. Till exempel: ChartType::PercentsStackedArea-serier kan inte vara samtidigt med ChartType::StackedArea-serier i en ChartSeriesGroup. Men två eller fler ChartType::PercentsStackedArea kan vara i en ChartSeriesGroup samtidigt (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea). Och ChartType::Line-serier kan vara med ChartType::LineWithMarkers-serier samtidigt i en CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup."
type: docs
weight: 1496
url: /sv/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enum

Uppräkning av grupper av kombinerbara serietyper. Varje element relaterar till en grupp av typer av diagramserier som kan finnas samtidigt i en [ChartSeriesGroup](../chartseriesgroup/). Till exempel: [ChartType::PercentsStackedArea](../charttype/) serier kan inte vara samtidigt med [ChartType::StackedArea](../charttype/) serier i en [ChartSeriesGroup](../chartseriesgroup/). Men två eller fler [ChartType::PercentsStackedArea](../charttype/) kan vara i en [ChartSeriesGroup](../chartseriesgroup/) samtidigt ([CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)). Och [ChartType::Line](../charttype/) serier kan vara med [ChartType::LineWithMarkers](../charttype/) serier samtidigt i en [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/).

```cpp
enum class CombinableSeriesTypesGroup
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| AreaChart_Area | 4 | Grupperar denna uppsättning serietyper: { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | Grupperar denna uppsättning serietyper: { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | Grupperar denna uppsättning serietyper: { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | Grupperar denna uppsättning serietyper: { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | Grupperar denna uppsättning serietyper: { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | Grupperar denna uppsättning serietyper: { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | Grupperar denna uppsättning serietyper: { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | Grupperar denna uppsättning serietyper: { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | Grupperar denna uppsättning serietyper: { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | Grupperar denna uppsättning serietyper: { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | Grupperar denna uppsättning serietyper: { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | Grupperar denna uppsättning serietyper: { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | Grupperar denna uppsättning serietyper: { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | Grupperar denna uppsättning serietyper: { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | Grupperar denna uppsättning serietyper: { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | Grupperar denna uppsättning serietyper: { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | Grupperar denna uppsättning serietyper: { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | Grupperar denna uppsättning serietyper: { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | Grupperar denna uppsättning serietyper: { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | Grupperar denna uppsättning serietyper: { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | Grupperar denna uppsättning serietyper: { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | Grupperar denna uppsättning serietyper: { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | Grupperar denna uppsättning serietyper: { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | Grupperar denna uppsättning serietyper: { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | Grupperar denna uppsättning serietyper: { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | Grupperar denna uppsättning serietyper: { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | Grupperar denna uppsättning serietyper: { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | Grupperar denna uppsättning serietyper: { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | Grupperar denna uppsättning serietyper: { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | Grupperar denna uppsättning serietyper: { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | Grupperar denna uppsättning serietyper: { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | Grupperar denna uppsättning serietyper: { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | Grupperar denna uppsättning serietyper: { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | Grupperar denna uppsättning serietyper: { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | Grupperar denna uppsättning serietyper: { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | Grupperar denna uppsättning serietyper: { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | Grupperar denna uppsättning serietyper: { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | Grupperar denna uppsättning serietyper: { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | Grupperar denna uppsättning serietyper: { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | Grupperar denna uppsättning serietyper: { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | Grupperar denna uppsättning serietyper: { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | Grupperar denna uppsättning serietyper: { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | Grupperar denna uppsättning serietyper: { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | Grupperar denna uppsättning serietyper: { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | Grupperar denna uppsättning serietyper: { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | Grupperar denna uppsättning serietyper: { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | Grupperar denna uppsättning serietyper: { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | Grupperar denna uppsättning serietyper: { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | Grupperar denna uppsättning serietyper: { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | Grupperar denna uppsättning serietyper: { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | Grupperar denna uppsättning serietyper: { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | Grupperar denna uppsättning serietyper: { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | Grupperar denna uppsättning serietyper: { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | Grupperar denna uppsättning serietyper: { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | Grupperar denna uppsättning serietyper: { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | Grupperar denna uppsättning serietyper: { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | Grupperar denna uppsättning serietyper: { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | Grupperar denna uppsättning serietyper: { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | Grupperar denna uppsättning serietyper: { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | Grupperar denna uppsättning serietyper: { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | Grupperar denna uppsättning serietyper: { [ChartType::Sunburst](../charttype/) } |

## Se även

* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)