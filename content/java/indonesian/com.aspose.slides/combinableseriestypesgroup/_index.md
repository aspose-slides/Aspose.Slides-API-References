---
title: CombinableSeriesTypesGroup
second_title: Referensi API Aspose.Slides untuk Java
description: Enumerasi grup tipe seri yang dapat digabungkan.
type: docs
url: /id/com.aspose.slides/combinableseriestypesgroup/
---
**Warisan:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

Enumerasi grup tipe seri yang dapat dikombinasikan. Setiap elemen berhubungan dengan grup tipe seri diagram yang dapat bertahan secara bersamaan dalam satu ChartSeriesGroup. Sebagai contoh: seri ChartType.PercentsStackedArea tidak dapat berada secara bersamaan dengan seri ChartType.StackedArea dalam satu ChartSeriesGroup. Namun dua atau lebih seri ChartType.PercentsStackedArea dapat berada secara bersamaan dalam satu ChartSeriesGroup (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Dan seri ChartType.Line dapat berada dengan seri ChartType.LineWithMarkers secara bersamaan dalam satu CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Area } |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedArea } |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedArea } |
| [AreaChart_Area3D](#AreaChart-Area3D) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Area3D } |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedArea3D } |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedArea3D } |
| [LineChart_Line](#LineChart-Line) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Line, ChartType.LineWithMarkers } |
| [LineChart_StackedLine](#LineChart-StackedLine) | Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| [Line3DChart](#Line3DChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Line3D } |
| [StockHighLowClose](#StockHighLowClose) | Mengelompokkan kumpulan tipe seri ini: { ChartType.HighLowClose } |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | Mengelompokkan kumpulan tipe seri ini: { ChartType.OpenHighLowClose } |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | Mengelompokkan kumpulan tipe seri ini: { ChartType.VolumeHighLowClose } |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | Mengelompokkan kumpulan tipe seri ini: { ChartType.VolumeOpenHighLowClose } |
| [RadarChart](#RadarChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Radar, ChartType.RadarWithMarkers } |
| [FilledRadarChart](#FilledRadarChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.FilledRadar } |
| [ScatterStraightMarker](#ScatterStraightMarker) | Mengelompokkan kumpulan tipe seri ini: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | Mengelompokkan kumpulan tipe seri ini: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| [PieChart](#PieChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Pie, ChartType.ExplodedPie } |
| [Pie3DChart](#Pie3DChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| [DoughnutChart](#DoughnutChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| [BarChart_VertClustered](#BarChart-VertClustered) | Mengelompokkan kumpulan tipe seri ini: { ChartType.ClusteredColumn } |
| [BarChart_VertStacked](#BarChart-VertStacked) | Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedColumn } |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedColumn } |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | Mengelompokkan kumpulan tipe seri ini: { ChartType.ClusteredBar } |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedBar } |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedBar } |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | Mengelompokkan kumpulan tipe seri ini: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedColumn3D } |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedCone } |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedCylinder } |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedPyramid } |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedColumn3D } |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedCone } |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedCylinder } |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedPyramid } |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | Mengelompokkan kumpulan tipe seri ini: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedBar3D } |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedHorizontalCone } |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedHorizontalCylinder } |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedHorizontalPyramid } |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedBar3D } |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedHorizontalCone } |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedHorizontalCylinder } |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedHorizontalPyramid } |
| [BarOfPieChart](#BarOfPieChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.BarOfPie } |
| [PieOfPieChart](#PieOfPieChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.PieOfPie } |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Contour } |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | Mengelompokkan kumpulan tipe seri ini: { ChartType.WireframeContour } |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Surface3D } |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | Mengelompokkan kumpulan tipe seri ini: { ChartType.WireframeSurface3D } |
| [BubbleChart](#BubbleChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Bubble, ChartType.BubbleWith3D } |
| [HistogramChart](#HistogramChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Histogram } |
| [ParetoLineChart](#ParetoLineChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.ParetoLine } |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.BoxAndWhisker } |
| [WaterfallChart](#WaterfallChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Waterfall } |
| [FunnelChart](#FunnelChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Funnel } |
| [TreemapChart](#TreemapChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Treemap } |
| [MapChart](#MapChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Map } |
| [SunburstChart](#SunburstChart) | Mengelompokkan kumpulan tipe seri ini: { ChartType.Sunburst } |

### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Area }

### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedArea }

### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedArea }

### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Area3D }

### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedArea3D }

### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedArea3D }

### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Line, ChartType.LineWithMarkers }

### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedLine, ChartType.StackedLineWithMarkers }

### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers }

### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Line3D }

### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.HighLowClose }

### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.OpenHighLowClose }

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.VolumeHighLowClose }

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.VolumeOpenHighLowClose }

### RadarChart {#RadarChart}
```
public static final int RadarChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Radar, ChartType.RadarWithMarkers }

### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.FilledRadar }

### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers }

### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers }

### PieChart {#PieChart}
```
public static final int PieChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Pie, ChartType.ExplodedPie }

### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Pie3D, ChartType.ExplodedPie3D }

### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Doughnut, ChartType.ExplodedDoughnut }

### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.ClusteredColumn }

### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedColumn }

### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedColumn }

### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.ClusteredBar }

### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedBar }

### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedBar }

### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D }

### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid }

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedColumn3D }

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedCone }

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedCylinder }

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedPyramid }

### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedColumn3D }

### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedCone }

### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedCylinder }

### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedPyramid }

### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid }

### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedBar3D }

### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedHorizontalCone }

### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedHorizontalCylinder }

### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.StackedHorizontalPyramid }

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedBar3D }

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedHorizontalCone }

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedHorizontalCylinder }

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.PercentsStackedHorizontalPyramid }

### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.BarOfPie }

### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.PieOfPie }

### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Contour }

### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.WireframeContour }

### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Surface3D }

### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.WireframeSurface3D }

### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Bubble, ChartType.BubbleWith3D }

### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Histogram }

### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.ParetoLine }

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.BoxAndWhisker }

### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Waterfall }

### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Funnel }

### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Treemap }

### MapChart {#MapChart}
```
public static final int MapChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Map }

### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

Mengelompokkan kumpulan tipe seri ini: { ChartType.Sunburst }