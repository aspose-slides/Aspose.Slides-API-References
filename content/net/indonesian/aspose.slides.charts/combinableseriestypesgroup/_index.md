---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes untuk Referensi API .NET
description: Enumerasi grup tipe seri yang dapat digabungkan. Setiap elemen berhubungan dengan grup tipe seri diagram yang dapat ada secara bersamaan dalam satu ChartSeriesGroup. Sebagai contoh, seri ChartType.PercentsStackedArea tidak dapat bersamaan dengan seri ChartType.StackedArea dalam satu ChartSeriesGroup. Namun dua atau lebih seri ChartType.PercentsStackedArea dapat berada dalam satu ChartSeriesGroup secara bersamaan, seperti CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. Dan seri ChartType.Line dapat berada bersama seri ChartType.LineWithMarkers secara bersamaan dalam satu ChartSeriesGroup CombinableSeriesTypesGroup.LineChart_Line.
type: docs
weight: 1530
url: /id/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumerasi

Enumerasi grup tipe seri yang dapat digabungkan. Setiap elemen berhubungan dengan grup tipe seri diagram yang dapat ada secara bersamaan dalam satu ChartSeriesGroup. Sebagai contoh: seri ChartType.PercentsStackedArea tidak dapat bersamaan dengan seri ChartType.StackedArea dalam satu ChartSeriesGroup. Namun dua atau lebih seri ChartType.PercentsStackedArea dapat berada dalam satu ChartSeriesGroup secara bersamaan (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Dan seri ChartType.Line dapat berada bersama seri ChartType.LineWithMarkers secara bersamaan dalam satu ChartSeriesGroup CombinableSeriesTypesGroup.LineChart_Line.

```csharp
public enum CombinableSeriesTypesGroup
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| AreaChart_Area | `4` | Mengelompokkan set tipe seri ini: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Mengelompokkan set tipe seri ini: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Mengelompokkan set tipe seri ini: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Mengelompokkan set tipe seri ini: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Mengelompokkan set tipe seri ini: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Mengelompokkan set tipe seri ini: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Mengelompokkan set tipe seri ini: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Mengelompokkan set tipe seri ini: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Mengelompokkan set tipe seri ini: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Mengelompokkan set tipe seri ini: { ChartType.Line3D } |
| StockHighLowClose | `18` | Mengelompokkan set tipe seri ini: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Mengelompokkan set tipe seri ini: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Mengelompokkan set tipe seri ini: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Mengelompokkan set tipe seri ini: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Mengelompokkan set tipe seri ini: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Mengelompokkan set tipe seri ini: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Mengelompokkan set tipe seri ini: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Mengelompokkan set tipe seri ini: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Mengelompokkan set tipe seri ini: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Mengelompokkan set tipe seri ini: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Mengelompokkan set tipe seri ini: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Mengelompokkan set tipe seri ini: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Mengelompokkan set tipe seri ini: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Mengelompokkan set tipe seri ini: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Mengelompokkan set tipe seri ini: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Mengelompokkan set tipe seri ini: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Mengelompokkan set tipe seri ini: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Mengelompokkan set tipe seri ini: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Mengelompokkan set tipe seri ini: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Mengelompokkan set tipe seri ini: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Mengelompokkan set tipe seri ini: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Mengelompokkan set tipe seri ini: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Mengelompokkan set tipe seri ini: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Mengelompokkan set tipe seri ini: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Mengelompokkan set tipe seri ini: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Mengelompokkan set tipe seri ini: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Mengelompokkan set tipe seri ini: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Mengelompokkan set tipe seri ini: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Mengelompokkan set tipe seri ini: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Mengelompokkan set tipe seri ini: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Mengelompokkan set tipe seri ini: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Mengelompokkan set tipe seri ini: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Mengelompokkan set tipe seri ini: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Mengelompokkan set tipe seri ini: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Mengelompokkan set tipe seri ini: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Mengelompokkan set tipe seri ini: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Mengelompokkan set tipe seri ini: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Mengelompokkan set tipe seri ini: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Mengelompokkan set tipe seri ini: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Mengelompokkan set tipe seri ini: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Mengelompokkan set tipe seri ini: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Mengelompokkan set tipe seri ini: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Mengelompokkan set tipe seri ini: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Mengelompokkan set tipe seri ini: { ChartType.Histogram } |
| ParetoLineChart | `54` | Mengelompokkan set tipe seri ini: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Mengelompokkan set tipe seri ini: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Mengelompokkan set tipe seri ini: { ChartType.Waterfall } |
| FunnelChart | `57` | Mengelompokkan set tipe seri ini: { ChartType.Funnel } |
| TreemapChart | `58` | Mengelompokkan set tipe seri ini: { ChartType.Treemap } |
| MapChart | `59` | Mengelompokkan set tipe seri ini: { ChartType.Map } |
| SunburstChart | `60` | Mengelompokkan set tipe seri ini: { ChartType.Sunburst } |

### Lihat Juga

* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->