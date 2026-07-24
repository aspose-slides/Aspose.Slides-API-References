---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides für C++ API-Referenz
description: "Aufzählung von Gruppen kombinierbarer Serientypen. Jedes Element bezieht sich auf eine Gruppe von Typen von Diagrammserien, die gleichzeitig in einer ChartSeriesGroup bestehen können. Zum Beispiel: ChartType::PercentsStackedArea-Serien können nicht gleichzeitig mit ChartType::StackedArea-Serien in einer ChartSeriesGroup existieren. Aber zwei oder mehr ChartType::PercentsStackedArea können gleichzeitig in einer ChartSeriesGroup sein (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea). Und ChartType::Line-Serien können gleichzeitig mit ChartType::LineWithMarkers-Serien in einer CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup sein."
type: docs
weight: 1496
url: /de/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enum

Aufzählung von Gruppen kombinierbarer Serientypen. Jedes Element bezieht sich auf eine Gruppe von Typen von Diagrammserien, die gleichzeitig in einem [ChartSeriesGroup](../chartseriesgroup/) bestehen können. Zum Beispiel können [ChartType::PercentsStackedArea](../charttype/)-Serien nicht gleichzeitig mit [ChartType::StackedArea](../charttype/)-Serien in einem [ChartSeriesGroup](../chartseriesgroup/) existieren. Aber zwei oder mehr [ChartType::PercentsStackedArea](../charttype/) können gleichzeitig in einem [ChartSeriesGroup](../chartseriesgroup/) sein ([CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)). Und [ChartType::Line](../charttype/)-Serien können gleichzeitig mit [ChartType::LineWithMarkers](../charttype/)-Serien in einem [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/) sein.

```cpp
enum class CombinableSeriesTypesGroup
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| AreaChart_Area | 4 | Gruppiert diesen Satz von Serientypen: { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | Gruppiert diesen Satz von Serientypen: { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | Gruppiert diesen Satz von Serientypen: { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | Gruppiert diesen Satz von Serientypen: { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | Gruppiert diesen Satz von Serientypen: { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | Gruppiert diesen Satz von Serientypen: { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | Gruppiert diesen Satz von Serientypen: { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | Gruppiert diesen Satz von Serientypen: { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | Gruppiert diesen Satz von Serientypen: { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | Gruppiert diesen Satz von Serientypen: { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | Gruppiert diesen Satz von Serientypen: { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | Gruppiert diesen Satz von Serientypen: { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | Gruppiert diesen Satz von Serientypen: { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | Gruppiert diesen Satz von Serientypen: { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | Gruppiert diesen Satz von Serientypen: { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | Gruppiert diesen Satz von Serientypen: { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | Gruppiert diesen Satz von Serientypen: { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | Gruppiert diesen Satz von Serientypen: { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | Gruppiert diesen Satz von Serientypen: { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | Gruppiert diesen Satz von Serientypen: { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | Gruppiert diesen Satz von Serientypen: { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | Gruppiert diesen Satz von Serientypen: { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | Gruppiert diesen Satz von Serientypen: { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | Gruppiert diesen Satz von Serientypen: { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | Gruppiert diesen Satz von Serientypen: { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | Gruppiert diesen Satz von Serientypen: { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | Gruppiert diesen Satz von Serientypen: { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | Gruppiert diesen Satz von Serientypen: { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | Gruppiert diesen Satz von Serientypen: { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | Gruppiert diesen Satz von Serientypen: { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | Gruppiert diesen Satz von Serientypen: { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | Gruppiert diesen Satz von Serientypen: { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | Gruppiert diesen Satz von Serientypen: { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | Gruppiert diesen Satz von Serientypen: { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | Gruppiert diesen Satz von Serientypen: { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | Gruppiert diesen Satz von Serientypen: { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | Gruppiert diesen Satz von Serientypen: { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | Gruppiert diesen Satz von Serientypen: { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | Gruppiert diesen Satz von Serientypen: { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | Gruppiert diesen Satz von Serientypen: { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | Gruppiert diesen Satz von Serientypen: { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | Gruppiert diesen Satz von Serientypen: { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | Gruppiert diesen Satz von Serientypen: { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | Gruppiert diesen Satz von Serientypen: { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | Gruppiert diesen Satz von Serientypen: { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | Gruppiert diesen Satz von Serientypen: { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | Gruppiert diesen Satz von Serientypen: { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | Gruppiert diesen Satz von Serientypen: { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | Gruppiert diesen Satz von Serientypen: { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | Gruppiert diesen Satz von Serientypen: { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | Gruppiert diesen Satz von Serientypen: { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | Gruppiert diesen Satz von Serientypen: { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | Gruppiert diesen Satz von Serientypen: { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | Gruppiert diesen Satz von Serientypen: { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | Gruppiert diesen Satz von Serientypen: { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | Gruppiert diesen Satz von Serientypen: { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | Gruppiert diesen Satz von Serientypen: { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | Gruppiert diesen Satz von Serientypen: { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | Gruppiert diesen Satz von Serientypen: { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | Gruppiert diesen Satz von Serientypen: { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | Gruppiert diesen Satz von Serientypen: { [ChartType::Sunburst](../charttype/) } |

## Siehe auch

* Namensraum [Aspose::Slides::Charts](../)
* Bibliothek [Aspose.Slides](../../)