---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup 类

 可组合系列类型组的枚举。  
 每个元素对应一组可以在同一个 ChartSeriesGroup 中同时存在的图表系列类型。  
 例如：ChartType.PercentsStackedArea 系列不能与 ChartType.StackedArea 系列同时存在于同一 ChartSeriesGroup 中。但两个或更多 ChartType.PercentsStackedArea 系列可以同时存在于同一 ChartSeriesGroup（CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea）。并且 ChartType.Line 系列可以与 ChartType.LineWithMarkers 系列同时存在于同一 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup 中。

## 常量

| 名称 | 值 | 描述 |
| --- | --- | --- |
[BarOfPieChart](#BarOfPieChart) | 0 | 将此系列类型集合分组为：{ ChartType.BarOfPie } |
[PieOfPieChart](#PieOfPieChart) | 1 | 将此系列类型集合分组为：{ ChartType.PieOfPie } |
[DoughnutChart](#DoughnutChart) | 2 | 将此系列类型集合分组为：{ ChartType.Doughnut, ChartType.ExplodedDoughnut } |
[PieChart](#PieChart) | 3 | 将此系列类型集合分组为：{ ChartType.Pie, ChartType.ExplodedPie } |
[AreaChart_Area](#AreaChart_Area) | 4 | 将此系列类型集合分组为：{ ChartType.Area } |
[AreaChart_PercentsStackedArea](#AreaChart_PercentsStackedArea) | 5 | 将此系列类型集合分组为：{ ChartType.PercentsStackedArea } |
[AreaChart_StackedArea](#AreaChart_StackedArea) | 6 | 将此系列类型集合分组为：{ ChartType.StackedArea } |
[BarChart_HorizClustered](#BarChart_HorizClustered) | 7 | 将此系列类型集合分组为：{ ChartType.ClusteredBar } |
[BarChart_HorizStacked](#BarChart_HorizStacked) | 8 | 将此系列类型集合分组为：{ ChartType.StackedBar } |
[BarChart_HorizPercentsStacked](#BarChart_HorizPercentsStacked) | 9 | 将此系列类型集合分组为：{ ChartType.PercentsStackedBar } |
[BarChart_VertClustered](#BarChart_VertClustered) | 10 | 将此系列类型集合分组为：{ ChartType.ClusteredColumn } |
[BarChart_VertStacked](#BarChart_VertStacked) | 11 | 将此系列类型集合分组为：{ ChartType.StackedColumn } |
[BarChart_VertPercentsStacked](#BarChart_VertPercentsStacked) | 12 | 将此系列类型集合分组为：{ ChartType.PercentsStackedColumn } |
[LineChart_Line](#LineChart_Line) | 13 | 将此系列类型集合分组为：{ ChartType.Line, ChartType.LineWithMarkers } |
[LineChart_StackedLine](#LineChart_StackedLine) | 14 | 将此系列类型集合分组为：{ ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
[LineChart_PercentsStackedLine](#LineChart_PercentsStackedLine) | 15 | 将此系列类型集合分组为：{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
[RadarChart](#RadarChart) | 16 | 将此系列类型集合分组为：{ ChartType.Radar, ChartType.RadarWithMarkers } |
[FilledRadarChart](#FilledRadarChart) | 17 | 将此系列类型集合分组为：{ ChartType.FilledRadar } |
[StockHighLowClose](#StockHighLowClose) | 18 | 将此系列类型集合分组为：{ ChartType.HighLowClose } |
[StockOpenHighLowClose](#StockOpenHighLowClose) | 19 | 将此系列类型集合分组为：{ ChartType.OpenHighLowClose } |
[StockVolumeHighLowClose](#StockVolumeHighLowClose) | 20 | 将此系列类型集合分组为：{ ChartType.VolumeHighLowClose } |
[StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | 21 | 将此系列类型集合分组为：{ ChartType.VolumeOpenHighLowClose } |
[ScatterStraightMarker](#ScatterStraightMarker) | 22 | 将此系列类型集合分组为：{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
[ScatterSmoothMarker](#ScatterSmoothMarker) | 23 | 将此系列类型集合分组为：{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
[AreaChart_Area3D](#AreaChart_Area3D) | 24 | 将此系列类型集合分组为：{ ChartType.Area3D } |
[AreaChart_StackedArea3D](#AreaChart_StackedArea3D) | 25 | 将此系列类型集合分组为：{ ChartType.StackedArea3D } |
[AreaChart_PercentsStackedArea3D](#AreaChart_PercentsStackedArea3D) | 26 | 将此系列类型集合分组为：{ ChartType.PercentsStackedArea3D } |
[Line3DChart](#Line3DChart) | 27 | 将此系列类型集合分组为：{ ChartType.Line3D } |
[Pie3DChart](#Pie3DChart) | 28 | 将此系列类型集合分组为：{ ChartType.Pie3D, ChartType.ExplodedPie3D } |
[Bar3DChart_Vert](#Bar3DChart_Vert) | 29 | 将此系列类型集合分组为：{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
[Bar3DChart_VertClustered](#Bar3DChart_VertClustered) | 30 | 将此系列类型集合分组为：{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
[Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart_VertPercentsStackedColumn3D) | 31 | 将此系列类型集合分组为：{ ChartType.PercentsStackedColumn3D } |
[Bar3DChart_VertPercentsStackedCone](#Bar3DChart_VertPercentsStackedCone) | 32 | 将此系列类型集合分组为：{ ChartType.PercentsStackedCone } |
[Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart_VertPercentsStackedCylinder) | 33 | 将此系列类型集合分组为：{ ChartType.PercentsStackedCylinder } |
[Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart_VertPercentsStackedPyramid) | 34 | 将此系列类型集合分组为：{ ChartType.PercentsStackedPyramid } |
[Bar3DChart_VertStackedColumn3D](#Bar3DChart_VertStackedColumn3D) | 35 | 将此系列类型集合分组为：{ ChartType.StackedColumn3D } |
[Bar3DChart_VertStackedCone](#Bar3DChart_VertStackedCone) | 36 | 将此系列类型集合分组为：{ ChartType.StackedCone } |
[Bar3DChart_VertStackedCylinder](#Bar3DChart_VertStackedCylinder) | 37 | 将此系列类型集合分组为：{ ChartType.StackedCylinder } |
[Bar3DChart_VertStackedPyramid](#Bar3DChart_VertStackedPyramid) | 38 | 将此系列类型集合分组为：{ ChartType.StackedPyramid } |
[Bar3DChart_HorizClustered](#Bar3DChart_HorizClustered) | 39 | 将此系列类型集合分组为：{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
[Bar3DChart_HorizStackedBar3D](#Bar3DChart_HorizStackedBar3D) | 40 | 将此系列类型集合分组为：{ ChartType.StackedBar3D } |
[Bar3DChart_HorizStackedCone](#Bar3DChart_HorizStackedCone) | 41 | 将此系列类型集合分组为：{ ChartType.StackedHorizontalCone } |
[Bar3DChart_HorizStackedCylinder](#Bar3DChart_HorizStackedCylinder) | 42 | 将此系列类型集合分组为：{ ChartType.StackedHorizontalCylinder } |
[Bar3DChart_HorizStackedPyramid](#Bar3DChart_HorizStackedPyramid) | 43 | 将此系列类型集合分组为：{ ChartType.StackedHorizontalPyramid } |
[Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart_HorizPercentsStackedBar3D) | 44 | 将此系列类型集合分组为：{ ChartType.PercentsStackedBar3D } |
[Bar3DChart_HorizPercentsStackedCone](#Bar3DChart_HorizPercentsStackedCone) | 45 | 将此系列类型集合分组为：{ ChartType.PercentsStackedHorizontalCone } |
[Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart_HorizPercentsStackedCylinder) | 46 | 将此系列类型集合分组为：{ ChartType.PercentsStackedHorizontalCylinder } |
[Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart_HorizPercentsStackedPyramid) | 47 | 将此系列类型集合分组为：{ ChartType.PercentsStackedHorizontalPyramid } |
[SurfaceChart_Contour](#SurfaceChart_Contour) | 48 | 将此系列类型集合分组为：{ ChartType.Contour } |
[SurfaceChart_WireframeContour](#SurfaceChart_WireframeContour) | 49 | 将此系列类型集合分组为：{ ChartType.WireframeContour } |
[SurfaceChart_Surface3D](#SurfaceChart_Surface3D) | 50 | 将此系列类型集合分组为：{ ChartType.Surface3D } |
[SurfaceChart_WireframeSurface3D](#SurfaceChart_WireframeSurface3D) | 51 | 将此系列类型集合分组为：{ ChartType.WireframeSurface3D } |
[BubbleChart](#BubbleChart) | 52 | 将此系列类型集合分组为：{ ChartType.Bubble, ChartType.BubbleWith3D } |
[HistogramChart](#HistogramChart) | 53 | 将此系列类型集合分组为：{ ChartType.Histogram } |
[ParetoLineChart](#ParetoLineChart) | 54 | 将此系列类型集合分组为：{ ChartType.ParetoLine } |
[BoxAndWhiskerChart](#BoxAndWhiskerChart) | 55 | 将此系列类型集合分组为：{ ChartType.BoxAndWhisker } |
[WaterfallChart](#WaterfallChart) | 56 | 将此系列类型集合分组为：{ ChartType.Waterfall } |
[FunnelChart](#FunnelChart) | 57 | 将此系列类型集合分组为：{ ChartType.Funnel } |
[TreemapChart](#TreemapChart) | 58 | 将此系列类型集合分组为：{ ChartType.Treemap } |
[MapChart](#MapChart) | 59 | 将此系列类型集合分组为：{ ChartType.Map } |
[SunburstChart](#SunburstChart) | 60 | 将此系列类型集合分组为：{ ChartType.Sunburst } |

---

### BarOfPieChart {#BarOfPieChart}
将此系列类型集合分组为：{ ChartType.BarOfPie }

---

### PieOfPieChart {#PieOfPieChart}
将此系列类型集合分组为：{ ChartType.PieOfPie }

---

### DoughnutChart {#DoughnutChart}
将此系列类型集合分组为：{ ChartType.Doughnut, ChartType.ExplodedDoughnut }

---

### PieChart {#PieChart}
将此系列类型集合分组为：{ ChartType.Pie, ChartType.ExplodedPie }

---

### AreaChart_Area {#AreaChart_Area}
将此系列类型集合分组为：{ ChartType.Area }

---

### AreaChart_PercentsStackedArea {#AreaChart_PercentsStackedArea}
将此系列类型集合分组为：{ ChartType.PercentsStackedArea }

---

### AreaChart_StackedArea {#AreaChart_StackedArea}
将此系列类型集合分组为：{ ChartType.StackedArea }

---

### BarChart_HorizClustered {#BarChart_HorizClustered}
将此系列类型集合分组为：{ ChartType.ClusteredBar }

---

### BarChart_HorizStacked {#BarChart_HorizStacked}
将此系列类型集合分组为：{ ChartType.StackedBar }

---

### BarChart_HorizPercentsStacked {#BarChart_HorizPercentsStacked}
将此系列类型集合分组为：{ ChartType.PercentsStackedBar }

---

### BarChart_VertClustered {#BarChart_VertClustered}
将此系列类型集合分组为：{ ChartType.ClusteredColumn }

---

### BarChart_VertStacked {#BarChart_VertStacked}
将此系列类型集合分组为：{ ChartType.StackedColumn }

---

### BarChart_VertPercentsStacked {#BarChart_VertPercentsStacked}
将此系列类型集合分组为：{ ChartType.PercentsStackedColumn }

---

### LineChart_Line {#LineChart_Line}
将此系列类型集合分组为：{ ChartType.Line, ChartType.LineWithMarkers }

---

### LineChart_StackedLine {#LineChart_StackedLine}
将此系列类型集合分组为：{ ChartType.StackedLine, ChartType.StackedLineWithMarkers }

---

### LineChart_PercentsStackedLine {#LineChart_PercentsStackedLine}
将此系列类型集合分组为：{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers }

---

### RadarChart {#RadarChart}
将此系列类型集合分组为：{ ChartType.Radar, ChartType.RadarWithMarkers }

---

### FilledRadarChart {#FilledRadarChart}
将此系列类型集合分组为：{ ChartType.FilledRadar }

---

### StockHighLowClose {#StockHighLowClose}
将此系列类型集合分组为：{ ChartType.HighLowClose }

---

### StockOpenHighLowClose {#StockOpenHighLowClose}
将此系列类型集合分组为：{ ChartType.OpenHighLowClose }

---

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
将此系列类型集合分组为：{ ChartType.VolumeHighLowClose }

---

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
将此系列类型集合分组为：{ ChartType.VolumeOpenHighLowClose }

---

### ScatterStraightMarker {#ScatterStraightMarker}
将此系列类型集合分组为：{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers }

---

### ScatterSmoothMarker {#ScatterSmoothMarker}
将此系列类型集合分组为：{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers }

---

### AreaChart_Area3D {#AreaChart_Area3D}
将此系列类型集合分组为：{ ChartType.Area3D }

---

### AreaChart_StackedArea3D {#AreaChart_StackedArea3D}
将此系列类型集合分组为：{ ChartType.StackedArea3D }

---

### AreaChart_PercentsStackedArea3D {#AreaChart_PercentsStackedArea3D}
将此系列类型集合分组为：{ ChartType.PercentsStackedArea3D }

---

### Line3DChart {#Line3DChart}
将此系列类型集合分组为：{ ChartType.Line3D }

---

### Pie3DChart {#Pie3DChart}
将此系列类型集合分组为：{ ChartType.Pie3D, ChartType.ExplodedPie3D }

---

### Bar3DChart_Vert {#Bar3DChart_Vert}
将此系列类型集合分组为：{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D }

---

### Bar3DChart_VertClustered {#Bar3DChart_VertClustered}
将此系列类型集合分组为：{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid }

---

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart_VertPercentsStackedColumn3D}
将此系列类型集合分组为：{ ChartType.PercentsStackedColumn3D }

---

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart_VertPercentsStackedCone}
将此系列类型集合分组为：{ ChartType.PercentsStackedCone }

---

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart_VertPercentsStackedCylinder}
将此系列类型集合分组为：{ ChartType.PercentsStackedCylinder }

---

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart_VertPercentsStackedPyramid}
将此系列类型集合分组为：{ ChartType.PercentsStackedPyramid }

---

### Bar3DChart_VertStackedColumn3D {#Bar3DChart_VertStackedColumn3D}
将此系列类型集合分组为：{ ChartType.StackedColumn3D }

---

### Bar3DChart_VertStackedCone {#Bar3DChart_VertStackedCone}
将此系列类型集合分组为：{ ChartType.StackedCone }

---

### Bar3DChart_VertStackedCylinder {#Bar3DChart_VertStackedCylinder}
将此系列类型集合分组为：{ ChartType.StackedCylinder }

---

### Bar3DChart_VertStackedPyramid {#Bar3DChart_VertStackedPyramid}
将此系列类型集合分组为：{ ChartType.StackedPyramid }

---

### Bar3DChart_HorizClustered {#Bar3DChart_HorizClustered}
将此系列类型集合分组为：{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid }

---

### Bar3DChart_HorizStackedBar3D {#Bar3DChart_HorizStackedBar3D}
将此系列类型集合分组为：{ ChartType.StackedBar3D }

---

### Bar3DChart_HorizStackedCone {#Bar3DChart_HorizStackedCone}
将此系列类型集合分组为：{ ChartType.StackedHorizontalCone }

---

### Bar3DChart_HorizStackedCylinder {#Bar3DChart_HorizStackedCylinder}
将此系列类型集合分组为：{ ChartType.StackedHorizontalCylinder }

---

### Bar3DChart_HorizStackedPyramid {#Bar3DChart_HorizStackedPyramid}
将此系列类型集合分组为：{ ChartType.StackedHorizontalPyramid }

---

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart_HorizPercentsStackedBar3D}
将此系列类型集合分组为：{ ChartType.PercentsStackedBar3D }

---

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart_HorizPercentsStackedCone}
将此系列类型集合分组为：{ ChartType.PercentsStackedHorizontalCone }

---

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart_HorizPercentsStackedCylinder}
将此系列类型集合分组为：{ ChartType.PercentsStackedHorizontalCylinder }

---

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart_HorizPercentsStackedPyramid}
将此系列类型集合分组为：{ ChartType.PercentsStackedHorizontalPyramid }

---

### SurfaceChart_Contour {#SurfaceChart_Contour}
将此系列类型集合分组为：{ ChartType.Contour }

---

### SurfaceChart_WireframeContour {#SurfaceChart_WireframeContour}
将此系列类型集合分组为：{ ChartType.WireframeContour }

---

### SurfaceChart_Surface3D {#SurfaceChart_Surface3D}
将此系列类型集合分组为：{ ChartType.Surface3D }

---

### SurfaceChart_WireframeSurface3D {#SurfaceChart_WireframeSurface3D}
将此系列类型集合分组为：{ ChartType.WireframeSurface3D }

---

### BubbleChart {#BubbleChart}
将此系列类型集合分组为：{ ChartType.Bubble, ChartType.BubbleWith3D }

---

### HistogramChart {#HistogramChart}
将此系列类型集合分组为：{ ChartType.Histogram }

---

### ParetoLineChart {#ParetoLineChart}
将此系列类型集合分组为：{ ChartType.ParetoLine }

---

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
将此系列类型集合分组为：{ ChartType.BoxAndWhisker }

---

### WaterfallChart {#WaterfallChart}
将此系列类型集合分组为：{ ChartType.Waterfall }

---

### FunnelChart {#FunnelChart}
将此系列类型集合分组为：{ ChartType.Funnel }

---

### TreemapChart {#TreemapChart}
将此系列类型集合分组为：{ ChartType.Treemap }

---

### MapChart {#MapChart}
将此系列类型集合分组为：{ ChartType.Map }

---

### SunburstChart {#SunburstChart}
将此系列类型集合分组为：{ ChartType.Sunburst }

---