---
title: CombinableSeriesTypesGroup
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 결합 가능한 시리즈 유형 그룹의 열거형.
type: docs
url: /ko/com.aspose.slides/combinableseriestypesgroup/
---
**상속:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

결합 가능한 시리즈 유형 그룹의 열거형입니다. 각 요소는 하나의 ChartSeriesGroup에서 동시에 존재할 수 있는 차트 시리즈 유형 그룹과 관련됩니다. 예를 들어: ChartType.PercentsStackedArea 시리즈는 하나의 ChartSeriesGroup에서 ChartType.StackedArea 시리즈와 동시에 존재할 수 없습니다. 그러나 두 개 이상의 ChartType.PercentsStackedArea는 하나의 ChartSeriesGroup에서 동시에 존재할 수 있습니다 (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). 그리고 ChartType.Line 시리즈는 ChartType.LineWithMarkers 시리즈와 동시에 하나의 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup에 존재할 수 있습니다.

## 필드

| 필드 | 설명 |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Area \} |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedArea \} |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedArea \} |
| [AreaChart_Area3D](#AreaChart-Area3D) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Area3D \} |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedArea3D \} |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedArea3D \} |
| [LineChart_Line](#LineChart-Line) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Line, ChartType.LineWithMarkers \} |
| [LineChart_StackedLine](#LineChart-StackedLine) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \} |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \} |
| [Line3DChart](#Line3DChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Line3D \} |
| [StockHighLowClose](#StockHighLowClose) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.HighLowClose \} |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.OpenHighLowClose \} |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.VolumeHighLowClose \} |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.VolumeOpenHighLowClose \} |
| [RadarChart](#RadarChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Radar, ChartType.RadarWithMarkers \} |
| [FilledRadarChart](#FilledRadarChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.FilledRadar \} |
| [ScatterStraightMarker](#ScatterStraightMarker) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \} |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \} |
| [PieChart](#PieChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Pie, ChartType.ExplodedPie \} |
| [Pie3DChart](#Pie3DChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \} |
| [DoughnutChart](#DoughnutChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \} |
| [BarChart_VertClustered](#BarChart-VertClustered) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.ClusteredColumn \} |
| [BarChart_VertStacked](#BarChart-VertStacked) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedColumn \} |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedColumn \} |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.ClusteredBar \} |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedBar \} |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedBar \} |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \} |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \} |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedColumn3D \} |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedCone \} |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedCylinder \} |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedPyramid \} |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedColumn3D \} |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedCone \} |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedCylinder \} |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedPyramid \} |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \} |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedBar3D \} |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedHorizontalCone \} |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedHorizontalCylinder \} |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedHorizontalPyramid \} |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedBar3D \} |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedHorizontalCone \} |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedHorizontalCylinder \} |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedHorizontalPyramid \} |
| [BarOfPieChart](#BarOfPieChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.BarOfPie \} |
| [PieOfPieChart](#PieOfPieChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PieOfPie \} |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Contour \} |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.WireframeContour \} |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Surface3D \} |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.WireframeSurface3D \} |
| [BubbleChart](#BubbleChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Bubble, ChartType.BubbleWith3D \} |
| [HistogramChart](#HistogramChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Histogram \} |
| [ParetoLineChart](#ParetoLineChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.ParetoLine \} |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.BoxAndWhisker \} |
| [WaterfallChart](#WaterfallChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Waterfall \} |
| [FunnelChart](#FunnelChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Funnel \} |
| [TreemapChart](#TreemapChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Treemap \} |
| [MapChart](#MapChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Map \} |
| [SunburstChart](#SunburstChart) | 이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Sunburst \} |

### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Area \}

### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedArea \}

### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedArea \}

### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Area3D \}

### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedArea3D \}

### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedArea3D \}

### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Line, ChartType.LineWithMarkers \}

### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \}

### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \}

### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Line3D \}

### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.HighLowClose \}

### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.OpenHighLowClose \}

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.VolumeHighLowClose \}

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.VolumeOpenHighLowClose \}

### RadarChart {#RadarChart}
```
public static final int RadarChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Radar, ChartType.RadarWithMarkers \}

### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.FilledRadar \}

### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \}

### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \}

### PieChart {#PieChart}
```
public static final int PieChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Pie, ChartType.ExplodedPie \}

### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \}

### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \}

### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.ClusteredColumn \}

### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedColumn \}

### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedColumn \}

### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.ClusteredBar \}

### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedBar \}

### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedBar \}

### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \}

### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \}

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedColumn3D \}

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedCone \}

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedCylinder \}

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedPyramid \}

### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedColumn3D \}

### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedCone \}

### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedCylinder \}

### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedPyramid \}

### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \}

### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedBar3D \}

### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedHorizontalCone \}

### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedHorizontalCylinder \}

### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.StackedHorizontalPyramid \}

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedBar3D \}

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedHorizontalCone \}

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedHorizontalCylinder \}

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PercentsStackedHorizontalPyramid \}

### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.BarOfPie \}

### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.PieOfPie \}

### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Contour \}

### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.WireframeContour \}

### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Surface3D \}

### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.WireframeSurface3D \}

### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Bubble, ChartType.BubbleWith3D \}

### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Histogram \}

### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.ParetoLine \}

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.BoxAndWhisker \}

### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Waterfall \}

### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Funnel \}

### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Treemap \}

### MapChart {#MapChart}
```
public static final int MapChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Map \}

### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

이 시리즈 유형 집합을 그룹화합니다: \{ ChartType.Sunburst \}