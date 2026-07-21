---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides для C++ справочник API
description: "Перечисление групп комбинируемых типов рядов. Каждый элемент относится к группе типов рядов диаграммы, которые могут существовать одновременно в одном ChartSeriesGroup. Например: ряд ChartType::PercentsStackedArea не может одновременно существовать с рядом ChartType::StackedArea в одном ChartSeriesGroup. Но два или более ChartType::PercentsStackedArea могут находиться в одном ChartSeriesGroup одновременно (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea). А ряд ChartType::Line может одновременно находиться с рядом ChartType::LineWithMarkers в одном CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup."
type: docs
weight: 1496
url: /ru/aspose.slides.charts/combinableseriestypesgroup/
---
## Перечисление CombinableSeriesTypesGroup enum

Перечисление групп комбинируемых типов рядов. Каждый элемент относится к группе типов рядов диаграммы, которые могут существовать одновременно в одном [ChartSeriesGroup](../chartseriesgroup/). Например, ряд [ChartType::PercentsStackedArea](../charttype/) не может одновременно существовать с рядом [ChartType::StackedArea](../charttype/) в одном [ChartSeriesGroup](../chartseriesgroup/). Но два или более [ChartType::PercentsStackedArea](../charttype/) могут находиться в одном [ChartSeriesGroup](../chartseriesgroup/) одновременно ([CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)). А ряды [ChartType::Line](../charttype/) могут одновременно находиться с рядами [ChartType::LineWithMarkers](../charttype/) в одном [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/).

```cpp
enum class CombinableSeriesTypesGroup
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| AreaChart_Area | 4 | Группирует этот набор типов рядов: { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | Группирует этот набор типов рядов: { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | Группирует этот набор типов рядов: { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | Группирует этот набор типов рядов: { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | Группирует этот набор типов рядов: { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | Группирует этот набор типов рядов: { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | Группирует этот набор типов рядов: { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | Группирует этот набор типов рядов: { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | Группирует этот набор типов рядов: { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | Группирует этот набор типов рядов: { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | Группирует этот набор типов рядов: { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | Группирует этот набор типов рядов: { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | Группирует этот набор типов рядов: { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | Группирует этот набор типов рядов: { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | Группирует этот набор типов рядов: { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | Группирует этот набор типов рядов: { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | Группирует этот набор типов рядов: { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | Группирует этот набор типов рядов: { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | Группирует этот набор типов рядов: { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | Группирует этот набор типов рядов: { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | Группирует этот набор типов рядов: { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | Группирует этот набор типов рядов: { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | Группирует этот набор типов рядов: { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | Группирует этот набор типов рядов: { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | Группирует этот набор типов рядов: { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | Группирует этот набор типов рядов: { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | Группирует этот набор типов рядов: { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | Группирует этот набор типов рядов: { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | Группирует этот набор типов рядов: { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | Группирует этот набор типов рядов: { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | Группирует этот набор типов рядов: { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | Группирует этот набор типов рядов: { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | Группирует этот набор типов рядов: { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | Группирует этот набор типов рядов: { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | Группирует этот набор типов рядов: { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | Группирует этот набор типов рядов: { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | Группирует этот набор типов рядов: { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | Группирует этот набор типов рядов: { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | Группирует этот набор типов рядов: { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | Группирует этот набор типов рядов: { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | Группирует этот набор типов рядов: { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | Группирует этот набор типов рядов: { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | Группирует этот набор типов рядов: { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | Группирует этот набор типов рядов: { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | Группирует этот набор типов рядов: { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | Группирует этот набор типов рядов: { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | Группирует этот набор типов рядов: { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | Группирует этот набор типов рядов: { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | Группирует этот набор типов рядов: { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | Группирует этот набор типов рядов: { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | Группирует этот набор типов рядов: { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | Группирует этот набор типов рядов: { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | Группирует этот набор типов рядов: { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | Группирует этот набор типов рядов: { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | Группирует этот набор типов рядов: { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | Группирует этот набор типов рядов: { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | Группирует этот набор типов рядов: { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | Группирует этот набор типов рядов: { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | Группирует этот набор типов рядов: { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | Группирует этот набор типов рядов: { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | Группирует этот набор типов рядов: { [ChartType::Sunburst](../charttype/) } |

## См. также

* Пространство имён [Aspose::Slides::Charts](../)
* Библиотека [Aspose.Slides](../../)