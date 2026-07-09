---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: การกำหนดค่าแบบ enumeration ของกลุ่มประเภทซีรีส์ที่สามารถรวมกันได้ แต่ละองค์ประกอบสัมพันธ์กับกลุ่มประเภทของซีรีส์แผนภูมิที่สามารถอยู่ร่วมกันได้ใน ChartSeriesGroup หนึ่ง ตัวอย่างเช่น ซีรีส์ ChartType.PercentsStackedArea ไม่สามารถอยู่พร้อมกับซีรีส์ ChartType.StackedArea ใน ChartSeriesGroup หนึ่งได้ แต่สองหรือมากกว่า ChartType.PercentsStackedArea สามารถอยู่ใน ChartSeriesGroup หนึ่งพร้อมกันได้ CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea และซีรีส์ ChartType.Line สามารถอยู่พร้อมกับซีรีส์ ChartType.LineWithMarkers ใน CombinableSeriesTypesGroup.LineChart_Line ของ ChartSeriesGroup.
type: docs
weight: 1530
url: /th/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeration

การกำหนดค่าแบบ enumeration ของกลุ่มประเภทซีรีส์ที่สามารถรวมกันได้ แต่ละองค์ประกอบสัมพันธ์กับกลุ่มประเภทของซีรีส์แผนภูมิที่สามารถอยู่ร่วมกันได้ใน ChartSeriesGroup หนึ่งอย่างพร้อมกัน ตัวอย่างเช่น: ซีรีส์ ChartType.PercentsStackedArea ไม่สามารถอยู่ร่วมกับซีรีส์ ChartType.StackedArea ใน ChartSeriesGroup หนึ่งได้ แต่สองหรือมากกว่า ChartType.PercentsStackedArea สามารถอยู่ใน ChartSeriesGroup หนึ่งพร้อมกันได้ (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea) และซีรีส์ ChartType.Line สามารถอยู่พร้อมกับซีรีส์ ChartType.LineWithMarkers ใน CombinableSeriesTypesGroup.LineChart_Line ของ ChartSeriesGroup ได้

```csharp
public enum CombinableSeriesTypesGroup
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| AreaChart_Area | `4` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Line3D } |
| StockHighLowClose | `18` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Histogram } |
| ParetoLineChart | `54` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Waterfall } |
| FunnelChart | `57` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Funnel } |
| TreemapChart | `58` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Treemap } |
| MapChart | `59` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Map } |
| SunburstChart | `60` | จัดกลุ่มชุดประเภทซีรีส์นี้: { ChartType.Sunburst } |

### ดูเพิ่มเติม

* เนมสเปซ [Aspose.Slides.Charts](../../aspose.slides.charts)
* แอสเซมบลี [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->