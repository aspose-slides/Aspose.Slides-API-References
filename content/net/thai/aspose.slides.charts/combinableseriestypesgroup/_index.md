---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: การนับค่า (enumeration) ของกลุ่มประเภท series ที่สามารถรวมกันได้ แต่ละองค์ประกอบสัมพันธ์กับกลุ่มของประเภท series ของแผนภูมิที่สามารถอยู่พร้อมกันใน ChartSeriesGroup หนึ่ง ตัวอย่างเช่น series ChartType.PercentsStackedArea ไม่สามารถอยู่พร้อมกับ series ChartType.StackedArea ใน ChartSeriesGroup เดียวกันได้ แต่สองหรือมากกว่า series ChartType.PercentsStackedArea สามารถอยู่ใน ChartSeriesGroup เดียวกันพร้อมกันได้ CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea และ series ChartType.Line สามารถอยู่กับ series ChartType.LineWithMarkers พร้อมกันใน ChartSeriesGroup ของ CombinableSeriesTypesGroup.LineChart_Line
type: docs
weight: 1530
url: /th/aspose.slides.charts/combinableseriestypesgroup/
---
## การนับค่า CombinableSeriesTypesGroup

การนับค่าแบบกลุ่มของประเภท series ที่สามารถรวมกันได้ แต่ละองค์ประกอบสัมพันธ์กับกลุ่มของประเภท series ของแผนภูมิที่สามารถอยู่พร้อมกันใน ChartSeriesGroup หนึ่ง ตัวอย่างเช่น series ChartType.PercentsStackedArea ไม่สามารถอยู่พร้อมกับ series ChartType.StackedArea ใน ChartSeriesGroup เดียวกันได้ แต่สองหรือมากกว่า series ChartType.PercentsStackedArea สามารถอยู่ใน ChartSeriesGroup เดียวกันพร้อมกันได้ (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea) และ series ChartType.Line สามารถอยู่กับ series ChartType.LineWithMarkers พร้อมกันใน CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup ได้

```csharp
public enum CombinableSeriesTypesGroup
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| AreaChart_Area | `4` | Groups this set of series types: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Groups this set of series types: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Groups this set of series types: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Groups this set of series types: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Groups this set of series types: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Groups this set of series types: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Groups this set of series types: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Groups this set of series types: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Groups this set of series types: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Groups this set of series types: { ChartType.Line3D } |
| StockHighLowClose | `18` | Groups this set of series types: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Groups this set of series types: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Groups this set of series types: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Groups this set of series types: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Groups this set of series types: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Groups this set of series types: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Groups this set of series types: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Groups this set of series types: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Groups this set of series types: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Groups this set of series types: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Groups this set of series types: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Groups this set of series types: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Groups this set of series types: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Groups this set of series types: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Groups this set of series types: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Groups this set of series types: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Groups this set of series types: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Groups this set of series types: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Groups this set of series types: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Groups this set of series types: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Groups this set of series types: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Groups this set of series types: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Groups this set of series types: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Groups this set of series types: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Groups this set of series types: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Groups this set of series types: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Groups this set of series types: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Groups this set of series types: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Groups this set of series types: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Groups this set of series types: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Groups this set of series types: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Groups this set of series types: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Groups this set of series types: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Groups this set of series types: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Groups this set of series types: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Groups this set of series types: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Groups this set of series types: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Groups this set of series types: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Groups this set of series types: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Groups this set of series types: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Groups this set of series types: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Groups this set of series types: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Groups this set of series types: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Groups this set of series types: { ChartType.Histogram } |
| ParetoLineChart | `54` | Groups this set of series types: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Groups this set of series types: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Groups this set of series types: { ChartType.Waterfall } |
| FunnelChart | `57` | Groups this set of series types: { ChartType.Funnel } |
| TreemapChart | `58` | Groups this set of series types: { ChartType.Treemap } |
| MapChart | `59` | Groups this set of series types: { ChartType.Map } |
| SunburstChart | `60` | Groups this set of series types: { ChartType.Sunburst } |

### ดูเพิ่มเติม

* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->