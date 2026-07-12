---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Enumeración de grupos de tipos de series combinables.
type: docs
url: /es/com.aspose.slides/combinableseriestypesgroup/
---
**Herencia:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

Enumeración de grupos de tipos de series combinables. Cada elemento está relacionado con un grupo de tipos de series de gráfico que pueden coexistir simultáneamente en un ChartSeriesGroup. Por ejemplo: las series ChartType.PercentsStackedArea no pueden estar simultáneamente con las series ChartType.StackedArea en un mismo ChartSeriesGroup. Pero dos o más series ChartType.PercentsStackedArea pueden estar en un mismo ChartSeriesGroup simultáneamente (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Y las series ChartType.Line pueden estar con las series ChartType.LineWithMarkers simultáneamente en un mismo CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
## Campos

| Campo | Descripción |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | Agrupa este conjunto de tipos de series: \{ ChartType.Area \} |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedArea \} |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | Agrupa este conjunto de tipos de series: \{ ChartType.StackedArea \} |
| [AreaChart_Area3D](#AreaChart-Area3D) | Agrupa este conjunto de tipos de series: \{ ChartType.Area3D \} |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | Agrupa este conjunto de tipos de series: \{ ChartType.StackedArea3D \} |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedArea3D \} |
| [LineChart_Line](#LineChart-Line) | Agrupa este conjunto de tipos de series: \{ ChartType.Line, ChartType.LineWithMarkers \} |
| [LineChart_StackedLine](#LineChart-StackedLine) | Agrupa este conjunto de tipos de series: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \} |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \} |
| [Line3DChart](#Line3DChart) | Agrupa este conjunto de tipos de series: \{ ChartType.Line3D \} |
| [StockHighLowClose](#StockHighLowClose) | Agrupa este conjunto de tipos de series: \{ ChartType.HighLowClose \} |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | Agrupa este conjunto de tipos de series: \{ ChartType.OpenHighLowClose \} |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | Agrupa este conjunto de tipos de series: \{ ChartType.VolumeHighLowClose \} |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | Agrupa este conjunto de tipos de series: \{ ChartType.VolumeOpenHighLowClose \} |
| [RadarChart](#RadarChart) | Agrupa este conjunto de tipos de series: \{ ChartType.Radar, ChartType.RadarWithMarkers \} |
| [FilledRadarChart](#FilledRadarChart) | Agrupa este conjunto de tipos de series: \{ ChartType.FilledRadar \} |
| [ScatterStraightMarker](#ScatterStraightMarker) | Agrupa este conjunto de tipos de series: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \} |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | Agrupa este conjunto de tipos de series: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \} |
| [PieChart](#PieChart) | Agrupa este conjunto de tipos de series: \{ ChartType.Pie, ChartType.ExplodedPie \} |
| [Pie3DChart](#Pie3DChart) | Agrupa este conjunto de tipos de series: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \} |
| [DoughnutChart](#DoughnutChart) | Agrupa este conjunto de tipos de series: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \} |
| [BarChart_VertClustered](#BarChart-VertClustered) | Agrupa este conjunto de tipos de series: \{ ChartType.ClusteredColumn \} |
| [BarChart_VertStacked](#BarChart-VertStacked) | Agrupa este conjunto de tipos de series: \{ ChartType.StackedColumn \} |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedColumn \} |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | Agrupa este conjunto de tipos de series: \{ ChartType.ClusteredBar \} |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | Agrupa este conjunto de tipos de series: \{ ChartType.StackedBar \} |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedBar \} |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | Agrupa este conjunto de tipos de series: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \} |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | Agrupa este conjunto de tipos de series: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \} |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedColumn3D \} |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedCone \} |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedCylinder \} |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedPyramid \} |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | Agrupa este conjunto de tipos de series: \{ ChartType.StackedColumn3D \} |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | Agrupa este conjunto de tipos de series: \{ ChartType.StackedCone \} |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | Agrupa este conjunto de tipos de series: \{ ChartType.StackedCylinder \} |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | Agrupa este conjunto de tipos de series: \{ ChartType.StackedPyramid \} |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | Agrupa este conjunto de tipos de series: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \} |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | Agrupa este conjunto de tipos de series: \{ ChartType.StackedBar3D \} |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | Agrupa este conjunto de tipos de series: \{ ChartType.StackedHorizontalCone \} |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | Agrupa este conjunto de tipos de series: \{ ChartType.StackedHorizontalCylinder \} |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | Agrupa este conjunto de tipos de series: \{ ChartType.StackedHorizontalPyramid \} |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedBar3D \} |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedHorizontalCone \} |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedHorizontalCylinder \} |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedHorizontalPyramid \} |
| [BarOfPieChart](#BarOfPieChart) | Agrupa este conjunto de tipos de series: \{ ChartType.BarOfPie \} |
| [PieOfPieChart](#PieOfPieChart) | Agrupa este conjunto de tipos de series: \{ ChartType.PieOfPie \} |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | Agrupa este conjunto de tipos de series: \{ ChartType.Contour \} |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | Agrupa este conjunto de tipos de series: \{ ChartType.WireframeContour \} |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | Agrupa este conjunto de tipos de series: \{ ChartType.Surface3D \} |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | Agrupa este conjunto de tipos de series: \{ ChartType.WireframeSurface3D \} |
| [BubbleChart](#BubbleChart) | Agrupa este conjunto de tipos de series: \{ ChartType.Bubble, ChartType.BubbleWith3D \} |
| [HistogramChart](#HistogramChart) | Agrupa este conjunto de tipos de series: \{ ChartType.Histogram \} |
| [ParetoLineChart](#ParetoLineChart) | Agrupa este conjunto de tipos de series: \{ ChartType.ParetoLine \} |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | Agrupa este conjunto de tipos de series: \{ ChartType.BoxAndWhisker \} |
| [WaterfallChart](#WaterfallChart) | Agrupa este conjunto de tipos de series: \{ ChartType.Waterfall \} |
| [FunnelChart](#FunnelChart) | Agrupa este conjunto de tipos de series: \{ ChartType.Funnel \} |
| [TreemapChart](#TreemapChart) | Agrupa este conjunto de tipos de series: \{ ChartType.Treemap \} |
| [MapChart](#MapChart) | Agrupa este conjunto de tipos de series: \{ ChartType.Map \} |
| [SunburstChart](#SunburstChart) | Agrupa este conjunto de tipos de series: \{ ChartType.Sunburst \} |
### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

Agrupa este conjunto de tipos de series: \{ ChartType.Area \}

### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedArea \}

### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

Agrupa este conjunto de tipos de series: \{ ChartType.StackedArea \}

### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

Agrupa este conjunto de tipos de series: \{ ChartType.Area3D \}

### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

Agrupa este conjunto de tipos de series: \{ ChartType.StackedArea3D \}

### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedArea3D \}

### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

Agrupa este conjunto de tipos de series: \{ ChartType.Line, ChartType.LineWithMarkers \}

### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

Agrupa este conjunto de tipos de series: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \}

### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \}

### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.Line3D \}

### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

Agrupa este conjunto de tipos de series: \{ ChartType.HighLowClose \}

### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

Agrupa este conjunto de tipos de series: \{ ChartType.OpenHighLowClose \}

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

Agrupa este conjunto de tipos de series: \{ ChartType.VolumeHighLowClose \}

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

Agrupa este conjunto de tipos de series: \{ ChartType.VolumeOpenHighLowClose \}

### RadarChart {#RadarChart}
```
public static final int RadarChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.Radar, ChartType.RadarWithMarkers \}

### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.FilledRadar \}

### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

Agrupa este conjunto de tipos de series: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \}

### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

Agrupa este conjunto de tipos de series: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \}

### PieChart {#PieChart}
```
public static final int PieChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.Pie, ChartType.ExplodedPie \}

### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \}

### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \}

### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

Agrupa este conjunto de tipos de series: \{ ChartType.ClusteredColumn \}

### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

Agrupa este conjunto de tipos de series: \{ ChartType.StackedColumn \}

### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedColumn \}

### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

Agrupa este conjunto de tipos de series: \{ ChartType.ClusteredBar \}

### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

Agrupa este conjunto de tipos de series: \{ ChartType.StackedBar \}

### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedBar \}

### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

Agrupa este conjunto de tipos de series: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \}

### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```

Agrupa este conjunto de tipos de series: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \}

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedColumn3D \}

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedCone \}

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedCylinder \}

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedPyramid \}

### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

Agrupa este conjunto de tipos de series: \{ ChartType.StackedColumn3D \}

### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

Agrupa este conjunto de tipos de series: \{ ChartType.StackedCone \}

### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

Agrupa este conjunto de tipos de series: \{ ChartType.StackedCylinder \}

### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

Agrupa este conjunto de tipos de series: \{ ChartType.StackedPyramid \}

### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

Agrupa este conjunto de tipos de series: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \}

### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

Agrupa este conjunto de tipos de series: \{ ChartType.StackedBar3D \}

### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

Agrupa este conjunto de tipos de series: \{ ChartType.StackedHorizontalCone \}

### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

Agrupa este conjunto de tipos de series: \{ ChartType.StackedHorizontalCylinder \}

### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

Agrupa este conjunto de tipos de series: \{ ChartType.StackedHorizontalPyramid \}

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedBar3D \}

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedHorizontalCone \}

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedHorizontalCylinder \}

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

Agrupa este conjunto de tipos de series: \{ ChartType.PercentsStackedHorizontalPyramid \}

### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.BarOfPie \}

### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.PieOfPie \}

### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

Agrupa este conjunto de tipos de series: \{ ChartType.Contour \}

### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

Agrupa este conjunto de tipos de series: \{ ChartType.WireframeContour \}

### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

Agrupa este conjunto de tipos de series: \{ ChartType.Surface3D \}

### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

Agrupa este conjunto de tipos de series: \{ ChartType.WireframeSurface3D \}

### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.Bubble, ChartType.BubbleWith3D \}

### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.Histogram \}

### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.ParetoLine \}

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.BoxAndWhisker \}

### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.Waterfall \}

### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.Funnel \}

### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.Treemap \}

### MapChart {#MapChart}
```
public static final int MapChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.Map \}

### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

Agrupa este conjunto de tipos de series: \{ ChartType.Sunburst \}