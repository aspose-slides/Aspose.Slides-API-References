---
title: CombinableSeriesTypesGroup
second_title: Referensi API Aspose.Slides untuk C++
description: "Enumerasi grup tipe seri yang dapat digabungkan. Setiap elemen berhubungan dengan grup tipe seri diagram yang dapat ada secara bersamaan dalam satu ChartSeriesGroup. Sebagai contoh: ChartType::PercentsStackedArea series tidak dapat berada secara bersamaan dengan ChartType::StackedArea series dalam satu ChartSeriesGroup. Namun dua atau lebih ChartType::PercentsStackedArea dapat berada dalam satu ChartSeriesGroup secara bersamaan (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea). Dan ChartType::Line series dapat berada dengan ChartType::LineWithMarkers series secara bersamaan dalam satu CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup."
type: docs
weight: 1496
url: /id/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enum

Enumerasi grup tipe seri yang dapat digabungkan. Setiap elemen berhubungan dengan grup tipe seri diagram yang dapat ada secara bersamaan dalam satu [ChartSeriesGroup](../chartseriesgroup/). Sebagai contoh: [ChartType::PercentsStackedArea](../charttype/) series tidak dapat berada secara bersamaan dengan [ChartType::StackedArea](../charttype/) series dalam satu [ChartSeriesGroup](../chartseriesgroup/). Namun dua atau lebih [ChartType::PercentsStackedArea](../charttype/) dapat berada dalam satu [ChartSeriesGroup](../chartseriesgroup/) secara bersamaan ([CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)). Dan [ChartType::Line](../charttype/) series dapat berada dengan [ChartType::LineWithMarkers](../charttype/) series secara bersamaan dalam satu [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/).

```cpp
enum class CombinableSeriesTypesGroup
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| AreaChart_Area | 4 | Mengelompokkan set tipe seri ini: { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | Mengelompokkan set tipe seri ini: { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | Mengelompokkan set tipe seri ini: { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | Mengelompokkan set tipe seri ini: { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | Mengelompokkan set tipe seri ini: { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | Mengelompokkan set tipe seri ini: { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | Mengelompokkan set tipe seri ini: { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | Mengelompokkan set tipe seri ini: { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | Mengelompokkan set tipe seri ini: { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | Mengelompokkan set tipe seri ini: { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | Mengelompokkan set tipe seri ini: { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | Mengelompokkan set tipe seri ini: { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | Mengelompokkan set tipe seri ini: { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | Mengelompokkan set tipe seri ini: { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | Mengelompokkan set tipe seri ini: { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | Mengelompokkan set tipe seri ini: { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | Mengelompokkan set tipe seri ini: { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | Mengelompokkan set tipe seri ini: { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | Mengelompokkan set tipe seri ini: { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | Mengelompokkan set tipe seri ini: { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | Mengelompokkan set tipe seri ini: { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | Mengelompokkan set tipe seri ini: { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | Mengelompokkan set tipe seri ini: { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | Mengelompokkan set tipe seri ini: { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | Mengelompokkan set tipe seri ini: { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | Mengelompokkan set tipe seri ini: { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | Mengelompokkan set tipe seri ini: { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | Mengelompokkan set tipe seri ini: { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | Mengelompokkan set tipe seri ini: { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | Mengelompokkan set tipe seri ini: { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | Mengelompokkan set tipe seri ini: { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | Mengelompokkan set tipe seri ini: { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | Mengelompokkan set tipe seri ini: { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | Mengelompokkan set tipe seri ini: { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | Mengelompokkan set tipe seri ini: { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | Mengelompokkan set tipe seri ini: { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | Mengelompokkan set tipe seri ini: { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | Mengelompokkan set tipe seri ini: { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | Mengelompokkan set tipe seri ini: { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | Mengelompokkan set tipe seri ini: { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | Mengelompokkan set tipe seri ini: { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | Mengelompokkan set tipe seri ini: { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | Mengelompokkan set tipe seri ini: { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | Mengelompokkan set tipe seri ini: { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | Mengelompokkan set tipe seri ini: { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | Mengelompokkan set tipe seri ini: { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | Mengelompokkan set tipe seri ini: { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | Mengelompokkan set tipe seri ini: { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | Mengelompokkan set tipe seri ini: { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | Mengelompokkan set tipe seri ini: { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | Mengelompokkan set tipe seri ini: { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | Mengelompokkan set tipe seri ini: { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | Mengelompokkan set tipe seri ini: { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | Mengelompokkan set tipe seri ini: { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | Mengelompokkan set tipe seri ini: { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | Mengelompokkan set tipe seri ini: { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | Mengelompokkan set tipe seri ini: { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | Mengelompokkan set tipe seri ini: { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | Mengelompokkan set tipe seri ini: { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | Mengelompokkan set tipe seri ini: { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | Mengelompokkan set tipe seri ini: { [ChartType::Sunburst](../charttype/) } |

## Lihat Juga

* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)