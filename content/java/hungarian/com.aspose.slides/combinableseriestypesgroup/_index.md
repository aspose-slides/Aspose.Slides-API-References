---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides Java API hivatkozás
description: A kombinálható sorozattípusok csoportjainak felsorolása.
type: docs
url: /hu/com.aspose.slides/combinableseriestypesgroup/
---
**Öröklés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

Az kombinálható sorozattípusok csoportjainak felsorolása. Minden elem egy ChartSeriesGroup-ban egyszerre létező sorozattípusok csoportjára vonatkozik. Például a ChartType.PercentsStackedArea sorozat nem lehet egyszerre a ChartType.StackedArea sorozattal ugyanabban a ChartSeriesGroup-ban. De két vagy több ChartType.PercentsStackedArea sorozat szerepelhet egyszerre egy ChartSeriesGroup-ban (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). És a ChartType.Line sorozat egyszerre lehet a ChartType.LineWithMarkers sorozattal egy CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup-ban.
## Mezők

| Mező | Leírás |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Area \} |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedArea \} |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedArea \} |
| [AreaChart_Area3D](#AreaChart-Area3D) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Area3D \} |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedArea3D \} |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedArea3D \} |
| [LineChart_Line](#LineChart-Line) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Line, ChartType.LineWithMarkers \} |
| [LineChart_StackedLine](#LineChart-StackedLine) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \} |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \} |
| [Line3DChart](#Line3DChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Line3D \} |
| [StockHighLowClose](#StockHighLowClose) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.HighLowClose \} |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.OpenHighLowClose \} |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.VolumeHighLowClose \} |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.VolumeOpenHighLowClose \} |
| [RadarChart](#RadarChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Radar, ChartType.RadarWithMarkers \} |
| [FilledRadarChart](#FilledRadarChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.FilledRadar \} |
| [ScatterStraightMarker](#ScatterStraightMarker) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \} |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \} |
| [PieChart](#PieChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Pie, ChartType.ExplodedPie \} |
| [Pie3DChart](#Pie3DChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \} |
| [DoughnutChart](#DoughnutChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \} |
| [BarChart_VertClustered](#BarChart-VertClustered) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.ClusteredColumn \} |
| [BarChart_VertStacked](#BarChart-VertStacked) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedColumn \} |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedColumn \} |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.ClusteredBar \} |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedBar \} |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedBar \} |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \} |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \} |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedColumn3D \} |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedCone \} |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedCylinder \} |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedPyramid \} |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedColumn3D \} |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedCone \} |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedCylinder \} |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedPyramid \} |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \} |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedBar3D \} |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedHorizontalCone \} |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedHorizontalCylinder \} |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedHorizontalPyramid \} |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedBar3D \} |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedHorizontalCone \} |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedHorizontalCylinder \} |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedHorizontalPyramid \} |
| [BarOfPieChart](#BarOfPieChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.BarOfPie \} |
| [PieOfPieChart](#PieOfPieChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PieOfPie \} |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Contour \} |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.WireframeContour \} |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Surface3D \} |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.WireframeSurface3D \} |
| [BubbleChart](#BubbleChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Bubble, ChartType.BubbleWith3D \} |
| [HistogramChart](#HistogramChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Histogram \} |
| [ParetoLineChart](#ParetoLineChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.ParetoLine \} |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.BoxAndWhisker \} |
| [WaterfallChart](#WaterfallChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Waterfall \} |
| [FunnelChart](#FunnelChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Funnel \} |
| [TreemapChart](#TreemapChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Treemap \} |
| [MapChart](#MapChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Map \} |
| [SunburstChart](#SunburstChart) | Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Sunburst \} |

### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Area \}

### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedArea \}

### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedArea \}

### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Area3D \}

### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedArea3D \}

### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedArea3D \}

### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Line, ChartType.LineWithMarkers \}

### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \}

### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \}

### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Line3D \}

### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.HighLowClose \}

### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.OpenHighLowClose \}

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.VolumeHighLowClose \}

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.VolumeOpenHighLowClose \}

### RadarChart {#RadarChart}
```
public static final int RadarChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Radar, ChartType.RadarWithMarkers \}

### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.FilledRadar \}

### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \}

### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \}

### PieChart {#PieChart}
```
public static final int PieChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Pie, ChartType.ExplodedPie \}

### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \}

### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \}

### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.ClusteredColumn \}

### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedColumn \}

### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedColumn \}

### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.ClusteredBar \}

### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedBar \}

### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedBar \}

### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \}

### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_Vert
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \}

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedColumn3D \}

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedCone \}

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedCylinder \}

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedPyramid \}

### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedColumn3D \}

### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedCone \}

### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedCylinder \}

### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedPyramid \}

### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \}

### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedBar3D \}

### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedHorizontalCone \}

### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedHorizontalCylinder \}

### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.StackedHorizontalPyramid \}

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedBar3D \}

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedHorizontalCone \}

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedHorizontalCylinder \}

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PercentsStackedHorizontalPyramid \}

### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.BarOfPie \}

### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.PieOfPie \}

### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Contour \}

### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.WireframeContour \}

### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Surface3D \}

### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.WireframeSurface3D \}

### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Bubble, ChartType.BubbleWith3D \}

### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Histogram \}

### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.ParetoLine \}

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.BoxAndWhisker \}

### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Waterfall \}

### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Funnel \}

### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Treemap \}

### MapChart {#MapChart}
```
public static final int MapChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Map \}

### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

Csoportosítja ezt a sorozattípus-készletet: \{ ChartType.Sunburst \}