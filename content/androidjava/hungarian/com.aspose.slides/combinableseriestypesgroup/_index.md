---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: A kombinálható sorozattípusok csoportjainak felsorolása.
type: docs
url: /hu/com.aspose.slides/combinableseriestypesgroup/
---
**Öröklődés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

A kombinálható sorozattípusok csoportjainak felsorolása. Minden elem egy olyan sorozattípus-csoportra vonatkozik, amely egyszerre több ChartSeriesGroup-ban is létezhet. Például: a ChartType.PercentsStackedArea sorozat nem lehet egyszerre a ChartType.StackedArea sorozattal egy ChartSeriesGroup-ban. De két vagy több ChartType.PercentsStackedArea sorozat lehet egy ChartSeriesGroup-ban egyszerre (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). És a ChartType.Line sorozat lehet a ChartType.LineWithMarkers sorozattal egyszerre egy CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup-ban.
## Mezők

| Field | Description |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Area \} |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedArea \} |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedArea \} |
| [AreaChart_Area3D](#AreaChart-Area3D) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Area3D \} |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedArea3D \} |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedArea3D \} |
| [LineChart_Line](#LineChart-Line) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Line, ChartType.LineWithMarkers \} |
| [LineChart_StackedLine](#LineChart-StackedLine) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \} |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \} |
| [Line3DChart](#Line3DChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Line3D \} |
| [StockHighLowClose](#StockHighLowClose) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.HighLowClose \} |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.OpenHighLowClose \} |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.VolumeHighLowClose \} |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.VolumeOpenHighLowClose \} |
| [RadarChart](#RadarChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Radar, ChartType.RadarWithMarkers \} |
| [FilledRadarChart](#FilledRadarChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.FilledRadar \} |
| [ScatterStraightMarker](#ScatterStraightMarker) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \} |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \} |
| [PieChart](#PieChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Pie, ChartType.ExplodedPie \} |
| [Pie3DChart](#Pie3DChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \} |
| [DoughnutChart](#DoughnutChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \} |
| [BarChart_VertClustered](#BarChart-VertClustered) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.ClusteredColumn \} |
| [BarChart_VertStacked](#BarChart-VertStacked) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedColumn \} |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedColumn \} |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.ClusteredBar \} |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedBar \} |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedBar \} |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \} |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \} |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedColumn3D \} |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedCone \} |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedCylinder \} |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedPyramid \} |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedColumn3D \} |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedCone \} |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedCylinder \} |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedPyramid \} |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \} |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedBar3D \} |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedHorizontalCone \} |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedHorizontalCylinder \} |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedHorizontalPyramid \} |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedBar3D \} |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedHorizontalCone \} |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedHorizontalCylinder \} |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedHorizontalPyramid \} |
| [BarOfPieChart](#BarOfPieChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.BarOfPie \} |
| [PieOfPieChart](#PieOfPieChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PieOfPie \} |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Contour \} |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.WireframeContour \} |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Surface3D \} |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.WireframeSurface3D \} |
| [BubbleChart](#BubbleChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Bubble, ChartType.BubbleWith3D \} |
| [HistogramChart](#HistogramChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Histogram \} |
| [ParetoLineChart](#ParetoLineChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.ParetoLine \} |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.BoxAndWhisker \} |
| [WaterfallChart](#WaterfallChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Waterfall \} |
| [FunnelChart](#FunnelChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Funnel \} |
| [TreemapChart](#TreemapChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Treemap \} |
| [MapChart](#MapChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Map \} |
| [SunburstChart](#SunburstChart) | Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Sunburst \} |
### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Area \}

### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedArea \}

### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedArea \}

### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Area3D \}

### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedArea3D \}

### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedArea3D \}

### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Line, ChartType.LineWithMarkers \}

### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \}

### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \}

### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Line3D \}

### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.HighLowClose \}

### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.OpenHighLowClose \}

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.VolumeHighLowClose \}

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.VolumeOpenHighLowClose \}

### RadarChart {#RadarChart}
```
public static final int RadarChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Radar, ChartType.RadarWithMarkers \}

### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.FilledRadar \}

### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \}

### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \}

### PieChart {#PieChart}
```
public static final int PieChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Pie, ChartType.ExplodedPie \}

### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \}

### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \}

### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.ClusteredColumn \}

### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedColumn \}

### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedColumn \}

### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.ClusteredBar \}

### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedBar \}

### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedBar \}

### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \}

### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \}

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedColumn3D \}

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedCone \}

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedCylinder \}

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedPyramid \}

### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedColumn3D \}

### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedCone \}

### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedCylinder \}

### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedPyramid \}

### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \}

### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedBar3D \}

### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedHorizontalCone \}

### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedHorizontalCylinder \}

### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.StackedHorizontalPyramid \}

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedBar3D \}

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedHorizontalCone \}

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedHorizontalCylinder \}

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PercentsStackedHorizontalPyramid \}

### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.BarOfPie \}

### PieOfPieChart {#PieOfPieChart}
```
public static final int BarOfPieChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.PieOfPie \}

### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Contour \}

### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.WireframeContour \}

### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Surface3D \}

### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.WireframeSurface3D \}

### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Bubble, ChartType.BubbleWith3D \}

### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Histogram \}

### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.ParetoLine \}

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.BoxAndWhisker \}

### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Waterfall \}

### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Funnel \}

### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Treemap \}

### MapChart {#MapChart}
```
public static final int MapChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Map \}

### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

Az adott sorozattípusok halmazát csoportosítja: \{ ChartType.Sunburst \}