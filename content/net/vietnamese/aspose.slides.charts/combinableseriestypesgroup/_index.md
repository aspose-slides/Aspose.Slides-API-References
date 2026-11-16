---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes cho Tham chiếu API .NET
description: Liệt kê các nhóm của các loại series có thể kết hợp. Mỗi phần tử liên quan tới một nhóm các loại series biểu đồ có thể tồn tại đồng thời trong một ChartSeriesGroup. Ví dụ, series ChartType.PercentsStackedArea không thể đồng thời với series ChartType.StackedArea trong một ChartSeriesGroup. Tuy nhiên, hai hoặc nhiều series ChartType.PercentsStackedArea có thể nằm trong một ChartSeriesGroup đồng thời CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. Và series ChartType.Line có thể cùng với series ChartType.LineWithMarkers đồng thời trong một CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
type: docs
weight: 1540
url: /vi/aspose.slides.charts/combinableseriestypesgroup/
---
## Liệt kê CombinableSeriesTypesGroup

Liệt kê các nhóm của các loại series có thể kết hợp. Mỗi phần tử liên quan tới một nhóm các loại series biểu đồ có thể tồn tại đồng thời trong một ChartSeriesGroup. Ví dụ: series ChartType.PercentsStackedArea không thể đồng thời với series ChartType.StackedArea trong một ChartSeriesGroup. Tuy nhiên hai hoặc nhiều series ChartType.PercentsStackedArea có thể nằm trong cùng một ChartSeriesGroup đồng thời (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Và series ChartType.Line có thể cùng với series ChartType.LineWithMarkers đồng thời trong một CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

```csharp
public enum CombinableSeriesTypesGroup
```

### Giá trị

| Tên | Giá trị | Mô tả |
| --- | --- | --- |
| AreaChart_Area | `4` | Nhóm các loại series này: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Nhóm các loại series này: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Nhóm các loại series này: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Nhóm các loại series này: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Nhóm các loại series này: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Nhóm các loại series này: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Nhóm các loại series này: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Nhóm các loại series này: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Nhóm các loại series này: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Nhóm các loại series này: { ChartType.Line3D } |
| StockHighLowClose | `18` | Nhóm các loại series này: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Nhóm các loại series này: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Nhóm các loại series này: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Nhóm các loại series này: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Nhóm các loại series này: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Nhóm các loại series này: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Nhóm các loại series này: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Nhóm các loại series này: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Nhóm các loại series này: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Nhóm các loại series này: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Nhóm các loại series này: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Nhóm các loại series này: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Nhóm các loại series này: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Nhóm các loại series này: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Nhóm các loại series này: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Nhóm các loại series này: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Nhóm các loại series này: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Nhóm các loại series này: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Nhóm các loại series này: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Nhóm các loại series này: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Nhóm các loại series này: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Nhóm các loại series này: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Nhóm các loại series này: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Nhóm các loại series này: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Nhóm các loại series này: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Nhóm các loại series này: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Nhóm các loại series này: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Nhóm các loại series này: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Nhóm các loại series này: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Nhóm các loại series này: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Nhóm các loại series này: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Nhóm các loại series này: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Nhóm các loại series này: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Nhóm các loại series này: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Nhóm các loại series này: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Nhóm các loại series này: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Nhóm các loại series này: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Nhóm các loại series này: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Nhóm các loại series này: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Nhóm các loại series này: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Nhóm các loại series này: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Nhóm các loại series này: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Nhóm các loại series này: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Nhóm các loại series này: { ChartType.Histogram } |
| ParetoLineChart | `54` | Nhóm các loại series này: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Nhóm các loại series này: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Nhóm các loại series này: { ChartType.Waterfall } |
| FunnelChart | `57` | Nhóm các loại series này: { ChartType.Funnel } |
| TreemapChart | `58` | Nhóm các loại series này: { ChartType.Treemap } |
| MapChart | `59` | Nhóm các loại series này: { ChartType.Map } |
| SunburstChart | `60` | Nhóm các loại series này: { ChartType.Sunburst } |

### Xem thêm

* không gian tên [Aspose.Slides.Charts](../../aspose.slides.charts)
* tập hợp [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->