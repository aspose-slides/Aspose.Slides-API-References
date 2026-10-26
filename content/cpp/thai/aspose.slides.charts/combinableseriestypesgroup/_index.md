---
title: CombinableSeriesTypesGroup
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "การนับจำนวนของกลุ่มประเภทซีรีส์ที่สามารถรวมกันได้. แต่ละองค์ประกอบสัมพันธ์กับกลุ่มของประเภทซีรีส์แผนภูมิที่สามารถอยู่พร้อมกันในหนึ่ง ChartSeriesGroup. ตัวอย่างเช่น: ชุดข้อมูล ChartType::PercentsStackedArea ไม่สามารถอยู่พร้อมกันกับชุดข้อมูล ChartType::StackedArea ในหนึ่ง ChartSeriesGroup. แต่สองหรือมากกว่า ChartType::PercentsStackedArea สามารถอยู่ในหนึ่ง ChartSeriesGroup พร้อมกัน (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea). และชุดข้อมูล ChartType::Line สามารถอยู่กับชุดข้อมูล ChartType::LineWithMarkers พร้อมกันในหนึ่ง CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup."
type: docs
weight: 1496
url: /th/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enum

การนับจำนวนของกลุ่มประเภทซีรีส์ที่สามารถรวมกันได้. แต่ละองค์ประกอบสัมพันธ์กับกลุ่มของประเภทซีรีส์แผนภูมิที่สามารถอยู่พร้อมกันในหนึ่ง [ChartSeriesGroup](../chartseriesgroup/). ตัวอย่างเช่น: ซีรีส์ [ChartType::PercentsStackedArea](../charttype/) ไม่สามารถอยู่พร้อมกันกับซีรีส์ [ChartType::StackedArea](../charttype/) ในหนึ่ง [ChartSeriesGroup](../chartseriesgroup/). แต่สองหรือมากกว่า [ChartType::PercentsStackedArea](../charttype/) สามารถอยู่ในหนึ่ง [ChartSeriesGroup](../chartseriesgroup/) พร้อมกัน ([CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)). และซีรีส์ [ChartType::Line](../charttype/) สามารถอยู่พร้อมกับซีรีส์ [ChartType::LineWithMarkers](../charttype/) ในหนึ่ง [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/).

```cpp
enum class CombinableSeriesTypesGroup
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| AreaChart_Area | 4 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | จัดกลุ่มชุดประเภทซีรีส์นี้: { [ChartType::Sunburst](../charttype/) } |

## ดูเพิ่มเติม

* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)