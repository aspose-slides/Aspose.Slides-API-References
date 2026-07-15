---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Liệt kê các nhóm các loại chuỗi có thể kết hợp.
type: docs
url: /vi/com.aspose.slides/combinableseriestypesgroup/
---
**Kế thừa:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

Liệt kê các nhóm loại chuỗi có thể kết hợp. Mỗi phần tử liên quan tới một nhóm các loại chuỗi biểu đồ có thể tồn tại đồng thời trong một ChartSeriesGroup. Ví dụ: chuỗi ChartType.PercentsStackedArea không thể đồng thời xuất hiện với chuỗi ChartType.StackedArea trong một ChartSeriesGroup. Tuy nhiên, hai hoặc nhiều chuỗi ChartType.PercentsStackedArea có thể nằm trong một ChartSeriesGroup đồng thời (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Và chuỗi ChartType.Line có thể cùng xuất hiện với chuỗi ChartType.LineWithMarkers đồng thời trong một ChartSeriesGroup.CombinableSeriesTypesGroup.LineChart_Line.
## Trường

| Trường | Mô tả |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | Nhóm các loại chuỗi này: \{ ChartType.Area \} |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedArea \} |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | Nhóm các loại chuỗi này: \{ ChartType.StackedArea \} |
| [AreaChart_Area3D](#AreaChart-Area3D) | Nhóm các loại chuỗi này: \{ ChartType.Area3D \} |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | Nhóm các loại chuỗi này: \{ ChartType.StackedArea3D \} |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedArea3D \} |
| [LineChart_Line](#LineChart-Line) | Nhóm các loại chuỗi này: \{ ChartType.Line, ChartType.LineWithMarkers \} |
| [LineChart_StackedLine](#LineChart-StackedLine) | Nhóm các loại chuỗi này: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \} |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \} |
| [Line3DChart](#Line3DChart) | Nhóm các loại chuỗi này: \{ ChartType.Line3D \} |
| [StockHighLowClose](#StockHighLowClose) | Nhóm các loại chuỗi này: \{ ChartType.HighLowClose \} |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | Nhóm các loại chuỗi này: \{ ChartType.OpenHighLowClose \} |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | Nhóm các loại chuỗi này: \{ ChartType.VolumeHighLowClose \} |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | Nhóm các loại chuỗi này: \{ ChartType.VolumeOpenHighLowClose \} |
| [RadarChart](#RadarChart) | Nhóm các loại chuỗi này: \{ ChartType.Radar, ChartType.RadarWithMarkers \} |
| [FilledRadarChart](#FilledRadarChart) | Nhóm các loại chuỗi này: \{ ChartType.FilledRadar \} |
| [ScatterStraightMarker](#ScatterStraightMarker) | Nhóm các loại chuỗi này: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \} |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | Nhóm các loại chuỗi này: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \} |
| [PieChart](#PieChart) | Nhóm các loại chuỗi này: \{ ChartType.Pie, ChartType.ExplodedPie \} |
| [Pie3DChart](#Pie3DChart) | Nhóm các loại chuỗi này: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \} |
| [DoughnutChart](#DoughnutChart) | Nhóm các loại chuỗi này: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \} |
| [BarChart_VertClustered](#BarChart-VertClustered) | Nhóm các loại chuỗi này: \{ ChartType.ClusteredColumn \} |
| [BarChart_VertStacked](#BarChart-VertStacked) | Nhóm các loại chuỗi này: \{ ChartType.StackedColumn \} |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedColumn \} |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | Nhóm các loại chuỗi này: \{ ChartType.ClusteredBar \} |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | Nhóm các loại chuỗi này: \{ ChartType.StackedBar \} |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedBar \} |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | Nhóm các loại chuỗi này: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \} |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | Nhóm các loại chuỗi này: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \} |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedColumn3D \} |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedCone \} |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedCylinder \} |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedPyramid \} |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | Nhóm các loại chuỗi này: \{ ChartType.StackedColumn3D \} |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | Nhóm các loại chuỗi này: \{ ChartType.StackedCone \} |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | Nhóm các loại chuỗi này: \{ ChartType.StackedCylinder \} |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | Nhóm các loại chuỗi này: \{ ChartType.StackedPyramid \} |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | Nhóm các loại chuỗi này: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \} |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | Nhóm các loại chuỗi này: \{ ChartType.StackedBar3D \} |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | Nhóm các loại chuỗi này: \{ ChartType.StackedHorizontalCone \} |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | Nhóm các loại chuỗi này: \{ ChartType.StackedHorizontalCylinder \} |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | Nhóm các loại chuỗi này: \{ ChartType.StackedHorizontalPyramid \} |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedBar3D \} |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedHorizontalCone \} |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedHorizontalCylinder \} |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedHorizontalPyramid \} |
| [BarOfPieChart](#BarOfPieChart) | Nhóm các loại chuỗi này: \{ ChartType.BarOfPie \} |
| [PieOfPieChart](#PieOfPieChart) | Nhóm các loại chuỗi này: \{ ChartType.PieOfPie \} |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | Nhóm các loại chuỗi này: \{ ChartType.Contour \} |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | Nhóm các loại chuỗi này: \{ ChartType.WireframeContour \} |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | Nhóm các loại chuỗi này: \{ ChartType.Surface3D \} |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | Nhóm các loại chuỗi này: \{ ChartType.WireframeSurface3D \} |
| [BubbleChart](#BubbleChart) | Nhóm các loại chuỗi này: \{ ChartType.Bubble, ChartType.BubbleWith3D \} |
| [HistogramChart](#HistogramChart) | Nhóm các loại chuỗi này: \{ ChartType.Histogram \} |
| [ParetoLineChart](#ParetoLineChart) | Nhóm các loại chuỗi này: \{ ChartType.ParetoLine \} |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | Nhóm các loại chuỗi này: \{ ChartType.BoxAndWhisker \} |
| [WaterfallChart](#WaterfallChart) | Nhóm các loại chuỗi này: \{ ChartType.Waterfall \} |
| [FunnelChart](#FunnelChart) | Nhóm các loại chuỗi này: \{ ChartType.Funnel \} |
| [TreemapChart](#TreemapChart) | Nhóm các loại chuỗi này: \{ ChartType.Treemap \} |
| [MapChart](#MapChart) | Nhóm các loại chuỗi này: \{ ChartType.Map \} |
| [SunburstChart](#SunburstChart) | Nhóm các loại chuỗi này: \{ ChartType.Sunburst \} |
### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```


Nhóm các loại chuỗi này: \{ ChartType.Area \}

### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```


Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedArea \}

### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```


Nhóm các loại chuỗi này: \{ ChartType.StackedArea \}

### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```


Nhóm các loại chuỗi này: \{ ChartType.Area3D \}

### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```


Nhóm các loại chuỗi này: \{ ChartType.StackedArea3D \}

### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```


Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedArea3D \}

### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```


Nhóm các loại chuỗi này: \{ ChartType.Line, ChartType.LineWithMarkers \}

### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```


Nhóm các loại chuỗi này: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \}

### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```


Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \}

### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```


Nhóm các loại chuỗi này: \{ ChartType.Line3D \}

### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```


Nhóm các loại chuỗi này: \{ ChartType.HighLowClose \}

### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```


Nhóm các loại chuỗi này: \{ ChartType.OpenHighLowClose \}

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```


Nhóm các loại chuỗi này: \{ ChartType.VolumeHighLowClose \}

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```


Nhóm các loại chuỗi này: \{ ChartType.VolumeOpenHighLowClose \}

### RadarChart {#RadarChart}
```
public static final int RadarChart
```


Nhóm các loại chuỗi này: \{ ChartType.Radar, ChartType.RadarWithMarkers \}

### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```


Nhóm các loại chuỗi này: \{ ChartType.FilledRadar \}

### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```


Nhóm các loại chuỗi này: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \}

### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```


Nhóm các loại chuỗi này: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \}

### PieChart {#PieChart}
```
public static final int PieChart
```


Nhóm các loại chuỗi này: \{ ChartType.Pie, ChartType.ExplodedPie \}

### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```


Nhóm các loại chuỗi này: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \}

### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```


Nhóm các loại chuỗi này: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \}

### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```


Nhóm các loại chuỗi này: \{ ChartType.ClusteredColumn \}

### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```


Nhóm các loại chuỗi này: \{ ChartType.StackedColumn \}

### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```


Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedColumn \}

### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```


Nhóm các loại chuỗi này: \{ ChartType.ClusteredBar \}

### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```


Nhóm các loại chuỗi này: \{ ChartType.StackedBar \}

### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```


Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedBar \}

### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```


Nhóm các loại chuỗi này: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \}

### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```


Nhóm các loại chuỗi này: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \}

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```


Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedColumn3D \}

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```


Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedCone \}

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```


Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedCylinder \}

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```


Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedPyramid \}

### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```


Nhóm các loại chuỗi này: \{ ChartType.StackedColumn3D \}

### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```


Nhóm các loại chuỗi này: \{ ChartType.StackedCone \}

### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```


Nhóm các loại chuỗi này: \{ ChartType.StackedCylinder \}

### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```


Nhóm các loại chuỗi này: \{ ChartType.StackedPyramid \}

### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```


Nhóm các loại chuỗi này: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \}

### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```


Nhóm các loại chuỗi này: \{ ChartType.StackedBar3D \}

### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```


Nhóm các loại chuỗi này: \{ ChartType.StackedHorizontalCone \}

### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```


Nhóm các loại chuỗi này: \{ ChartType.StackedHorizontalCylinder \}

### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```


Nhóm các loại chuỗi này: \{ ChartType.StackedHorizontalPyramid \}

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```


Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedBar3D \}

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```


Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedHorizontalCone \}

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```


Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedHorizontalCylinder \}

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```


Nhóm các loại chuỗi này: \{ ChartType.PercentsStackedHorizontalPyramid \}

### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```


Nhóm các loại chuỗi này: \{ ChartType.BarOfPie \}

### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```


Nhóm các loại chuỗi này: \{ ChartType.PieOfPie \}

### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```


Nhóm các loại chuỗi này: \{ ChartType.Contour \}

### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```


Nhóm các loại chuỗi này: \{ ChartType.WireframeContour \}

### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```


Nhóm các loại chuỗi này: \{ ChartType.Surface3D \}

### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```


Nhóm các loại chuỗi này: \{ ChartType.WireframeSurface3D \}

### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```


Nhóm các loại chuỗi này: \{ ChartType.Bubble, ChartType.BubbleWith3D \}

### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```


Nhóm các loại chuỗi này: \{ ChartType.Histogram \}

### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```


Nhóm các loại chuỗi này: \{ ChartType.ParetoLine \}

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```


Nhóm các loại chuỗi này: \{ ChartType.BoxAndWhisker \}

### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```


Nhóm các loại chuỗi này: \{ ChartType.Waterfall \}

### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```


Nhóm các loại chuỗi này: \{ ChartType.Funnel \}

### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```


Nhóm các loại chuỗi này: \{ ChartType.Treemap \}

### MapChart {#MapChart}
```
public static final int MapChart
```


Nhóm các loại chuỗi này: \{ ChartType.Map \}

### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```


Nhóm các loại chuỗi này: \{ ChartType.Sunburst \}