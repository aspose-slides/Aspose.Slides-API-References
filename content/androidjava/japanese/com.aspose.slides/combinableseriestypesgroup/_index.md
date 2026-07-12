---
title: CombinableSeriesTypesGroup
second_title: Android 用 Aspose.Slides の Java API リファレンス
description: 組み合わせ可能な系列タイプのグループの列挙です。
type: docs
url: /ja/com.aspose.slides/combinableseriestypesgroup/
---
**継承:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

組み合わせ可能な系列タイプのグループの列挙です。各要素は、1 つの ChartSeriesGroup 内で同時に存在できるチャート系列のタイプのグループに対応します。例として、ChartType.PercentsStackedArea 系列は ChartType.StackedArea 系列と同一の ChartSeriesGroup に同時に存在できません。しかし、ChartType.PercentsStackedArea 系列は複数あっても同一の ChartSeriesGroup に同時に配置できます (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea)。また、ChartType.Line 系列は ChartType.LineWithMarkers 系列と同じ CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup に同時に配置できます。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | このシリーズタイプのセットをグループ化します: \{ ChartType.Area \} |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedArea \} |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | このシリーズタイプのセットをグループ化します: \{ ChartType.StackedArea \} |
| [AreaChart_Area3D](#AreaChart-Area3D) | このシリーズタイプのセットをグループ化します: \{ ChartType.Area3D \} |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | このシリーズタイプのセットをグループ化します: \{ ChartType.StackedArea3D \} |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedArea3D \} |
| [LineChart_Line](#LineChart-Line) | このシリーズタイプのセットをグループ化します: \{ ChartType.Line, ChartType.LineWithMarkers \} |
| [LineChart_StackedLine](#LineChart-StackedLine) | このシリーズタイプのセットをグループ化します: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \} |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \} |
| [Line3DChart](#Line3DChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.Line3D \} |
| [StockHighLowClose](#StockHighLowClose) | このシリーズタイプのセットをグループ化します: \{ ChartType.HighLowClose \} |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | このシリーズタイプのセットをグループ化します: \{ ChartType.OpenHighLowClose \} |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | このシリーズタイプのセットをグループ化します: \{ ChartType.VolumeHighLowClose \} |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | このシリーズタイプのセットをグループ化します: \{ ChartType.VolumeOpenHighLowClose \} |
| [RadarChart](#RadarChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.Radar, ChartType.RadarWithMarkers \} |
| [FilledRadarChart](#FilledRadarChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.FilledRadar \} |
| [ScatterStraightMarker](#ScatterStraightMarker) | このシリーズタイプのセットをグループ化します: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \} |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | このシリーズタイプのセットをグループ化します: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \} |
| [PieChart](#PieChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.Pie, ChartType.ExplodedPie \} |
| [Pie3DChart](#Pie3DChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \} |
| [DoughnutChart](#DoughnutChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \} |
| [BarChart_VertClustered](#BarChart-VertClustered) | このシリーズタイプのセットをグループ化します: \{ ChartType.ClusteredColumn \} |
| [BarChart_VertStacked](#BarChart-VertStacked) | このシリーズタイプのセットをグループ化します: \{ ChartType.StackedColumn \} |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedColumn \} |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | このシリーズタイプのセットをグループ化します: \{ ChartType.ClusteredBar \} |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | このシリーズタイプのセットをグループ化します: \{ ChartType.StackedBar \} |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedBar \} |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | このシリーズタイプのセットをグループ化します: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \} |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | このシリーズタイプのセットをグループ化します: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \} |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedColumn3D \} |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedCone \} |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedCylinder \} |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedPyramid \} |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | このシリーズタイプのセットをグループ化します: \{ ChartType.StackedColumn3D \} |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | このシリーズタイプのセットをグループ化します: \{ ChartType.StackedCone \} |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | このシリーズタイプのセットをグループ化します: \{ ChartType.StackedCylinder \} |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | このシリーズタイプのセットをグループ化します: \{ ChartType.StackedPyramid \} |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | このシリーズタイプのセットをグループ化します: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \} |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | このシリーズタイプのセットをグループ化します: \{ ChartType.StackedBar3D \} |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | このシリーズタイプのセットをグループ化します: \{ ChartType.StackedHorizontalCone \} |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | このシリーズタイプのセットをグループ化します: \{ ChartType.StackedHorizontalCylinder \} |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | このシリーズタイプのセットをグループ化します: \{ ChartType.StackedHorizontalPyramid \} |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedBar3D \} |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedHorizontalCone \} |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedHorizontalCylinder \} |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedHorizontalPyramid \} |
| [BarOfPieChart](#BarOfPieChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.BarOfPie \} |
| [PieOfPieChart](#PieOfPieChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.PieOfPie \} |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | このシリーズタイプのセットをグループ化します: \{ ChartType.Contour \} |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | このシリーズタイプのセットをグループ化します: \{ ChartType.WireframeContour \} |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | このシリーズタイプのセットをグループ化します: \{ ChartType.Surface3D \} |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | このシリーズタイプのセットをグループ化します: \{ ChartType.WireframeSurface3D \} |
| [BubbleChart](#BubbleChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.Bubble, ChartType.BubbleWith3D \} |
| [HistogramChart](#HistogramChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.Histogram \} |
| [ParetoLineChart](#ParetoLineChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.ParetoLine \} |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.BoxAndWhisker \} |
| [WaterfallChart](#WaterfallChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.Waterfall \} |
| [FunnelChart](#FunnelChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.Funnel \} |
| [TreemapChart](#TreemapChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.Treemap \} |
| [MapChart](#MapChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.Map \} |
| [SunburstChart](#SunburstChart) | このシリーズタイプのセットをグループ化します: \{ ChartType.Sunburst \} |

### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Area \}

### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedArea \}

### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

このシリーズタイプのセットをグループ化します: \{ ChartType.StackedArea \}

### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Area3D \}

### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

このシリーズタイプのセットをグループ化します: \{ ChartType.StackedArea3D \}

### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedArea3D \}

### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Line, ChartType.LineWithMarkers \}

### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

このシリーズタイプのセットをグループ化します: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \}

### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \}

### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Line3D \}

### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

このシリーズタイプのセットをグループ化します: \{ ChartType.HighLowClose \}

### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

このシリーズタイプのセットをグループ化します: \{ ChartType.OpenHighLowClose \}

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

このシリーズタイプのセットをグループ化します: \{ ChartType.VolumeHighLowClose \}

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

このシリーズタイプのセットをグループ化します: \{ ChartType.VolumeOpenHighLowClose \}

### RadarChart {#RadarChart}
```
public static final int RadarChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Radar, ChartType.RadarWithMarkers \}

### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.FilledRadar \}

### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

このシリーズタイプのセットをグループ化します: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \}

### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

このシリーズタイプのセットをグループ化します: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \}

### PieChart {#PieChart}
```
public static final int PieChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Pie, ChartType.ExplodedPie \}

### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \}

### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \}

### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

このシリーズタイプのセットをグループ化します: \{ ChartType.ClusteredColumn \}

### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

このシリーズタイプのセットをグループ化します: \{ ChartType.StackedColumn \}

### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedColumn \}

### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

このシリーズタイプのセットをグループ化します: \{ ChartType.ClusteredBar \}

### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

このシリーズタイプのセットをグループ化します: \{ ChartType.StackedBar \}

### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedBar \}

### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \}

### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```

このシリーズタイプのセットをグループ化します: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \}

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedColumn3D \}

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedCone \}

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedCylinder \}

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedPyramid \}

### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

このシリーズタイプのセットをグループ化します: \{ ChartType.StackedColumn3D \}

### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

このシリーズタイプのセットをグループ化します: \{ ChartType.StackedCone \}

### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

このシリーズタイプのセットをグループ化します: \{ ChartType.StackedCylinder \}

### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

このシリーズタイプのセットをグループ化します: \{ ChartType.StackedPyramid \}

### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

このシリーズタイプのセットをグループ化します: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \}

### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

このシリーズタイプのセットをグループ化します: \{ ChartType.StackedBar3D \}

### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

このシリーズタイプのセットをグループ化します: \{ ChartType.StackedHorizontalCone \}

### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

このシリーズタイプのセットをグループ化します: \{ ChartType.StackedHorizontalCylinder \}

### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

このシリーズタイプのセットをグループ化します: \{ ChartType.StackedHorizontalPyramid \}

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedBar3D \}

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedHorizontalCone \}

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedHorizontalCylinder \}

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

このシリーズタイプのセットをグループ化します: \{ ChartType.PercentsStackedHorizontalPyramid \}

### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.BarOfPie \}

### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.PieOfPie \}

### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Contour \}

### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

このシリーズタイプのセットをグループ化します: \{ ChartType.WireframeContour \}

### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Surface3D \}

### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

このシリーズタイプのセットをグループ化します: \{ ChartType.WireframeSurface3D \}

### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Bubble, ChartType.BubbleWith3D \}

### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Histogram \}

### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.ParetoLine \}

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.BoxAndWhisker \}

### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Waterfall \}

### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Funnel \}

### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Treemap \}

### MapChart {#MapChart}
```
public static final int MapChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Map \}

### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

このシリーズタイプのセットをグループ化します: \{ ChartType.Sunburst \}