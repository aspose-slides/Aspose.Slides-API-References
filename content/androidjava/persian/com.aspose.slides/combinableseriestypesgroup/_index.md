---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: شمارشی از گروه‌های انواع سری‌های ترکیبی.
type: docs
url: /fa/com.aspose.slides/combinableseriestypesgroup/
---
**ارث‌برداری:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

شمارشی از گروه‌های انواع سری‌های ترکیبی است. هر عنصر به گروهی از انواع سری‌های نمودار که می‌توانند به‌صورت همزمان در یک ChartSeriesGroup وجود داشته باشند، مربوط می‌شود. به عنوان مثال: سری ChartType.PercentsStackedArea نمی‌تواند به‌طور همزمان با سری ChartType.StackedArea در یک ChartSeriesGroup باشد. اما دو یا چند سری ChartType.PercentsStackedArea می‌توانند به‌صورت همزمان در یک ChartSeriesGroup حضور داشته باشند (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). و سری ChartType.Line می‌تواند به‌صورت همزمان با سری ChartType.LineWithMarkers در یک CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

## فیلدها

| فیلد | توضیح |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Area \} |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedArea \} |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedArea \} |
| [AreaChart_Area3D](#AreaChart-Area3D) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Area3D \} |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedArea3D \} |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedArea3D \} |
| [LineChart_Line](#LineChart-Line) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Line, ChartType.LineWithMarkers \} |
| [LineChart_StackedLine](#LineChart-StackedLine) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \} |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \} |
| [Line3DChart](#Line3DChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Line3D \} |
| [StockHighLowClose](#StockHighLowClose) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.HighLowClose \} |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.OpenHighLowClose \} |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.VolumeHighLowClose \} |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.VolumeOpenHighLowClose \} |
| [RadarChart](#RadarChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Radar, ChartType.RadarWithMarkers \} |
| [FilledRadarChart](#FilledRadarChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.FilledRadar \} |
| [ScatterStraightMarker](#ScatterStraightMarker) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \} |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \} |
| [PieChart](#PieChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Pie, ChartType.ExplodedPie \} |
| [Pie3DChart](#Pie3DChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \} |
| [DoughnutChart](#DoughnutChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \} |
| [BarChart_VertClustered](#BarChart-VertClustered) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.ClusteredColumn \} |
| [BarChart_VertStacked](#BarChart-VertStacked) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedColumn \} |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedColumn \} |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.ClusteredBar \} |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedBar \} |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedBar \} |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \} |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \} |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedColumn3D \} |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedCone \} |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedCylinder \} |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedPyramid \} |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedColumn3D \} |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedCone \} |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedCylinder \} |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedPyramid \} |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \} |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedBar3D \} |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedHorizontalCone \} |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedHorizontalCylinder \} |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedHorizontalPyramid \} |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedBar3D \} |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedHorizontalCone \} |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedHorizontalCylinder \} |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedHorizontalPyramid \} |
| [BarOfPieChart](#BarOfPieChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.BarOfPie \} |
| [PieOfPieChart](#PieOfPieChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PieOfPie \} |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Contour \} |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.WireframeContour \} |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Surface3D \} |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.WireframeSurface3D \} |
| [BubbleChart](#BubbleChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Bubble, ChartType.BubbleWith3D \} |
| [HistogramChart](#HistogramChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Histogram \} |
| [ParetoLineChart](#ParetoLineChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.ParetoLine \} |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.BoxAndWhisker \} |
| [WaterfallChart](#WaterfallChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Waterfall \} |
| [FunnelChart](#FunnelChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Funnel \} |
| [TreemapChart](#TreemapChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Treemap \} |
| [MapChart](#MapChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Map \} |
| [SunburstChart](#SunburstChart) | این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Sunburst \} |

### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Area \}

### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedArea \}

### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedArea \}

### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Area3D \}

### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedArea3D \}

### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedArea3D \}

### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Line, ChartType.LineWithMarkers \}

### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \}

### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \}

### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Line3D \}

### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.HighLowClose \}

### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.OpenHighLowClose \}

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.VolumeHighLowClose \}

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.VolumeOpenHighLowClose \}

### RadarChart {#RadarChart}
```
public static final int RadarChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Radar, ChartType.RadarWithMarkers \}

### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.FilledRadar \}

### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \}

### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \}

### PieChart {#PieChart}
```
public static final int PieChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Pie, ChartType.ExplodedPie \}

### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \}

### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \}

### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.ClusteredColumn \}

### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedColumn \}

### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedColumn \}

### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.ClusteredBar \}

### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedBar \}

### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedBar \}

### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \}

### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \}

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedColumn3D \}

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedCone \}

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedCylinder \}

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedPyramid \}

### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedColumn3D \}

### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedCone \}

### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedCylinder \}

### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedPyramid \}

### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \}

### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedBar3D \}

### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedHorizontalCone \}

### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedHorizontalCylinder \}

### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.StackedHorizontalPyramid \}

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedBar3D \}

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedHorizontalCone \}

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedHorizontalCylinder \}

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PercentsStackedHorizontalPyramid \}

### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.BarOfPie \}

### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.PieOfPie \}

### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Contour \}

### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.WireframeContour \}

### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Surface3D \}

### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.WireframeSurface3D \}

### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Bubble, ChartType.BubbleWith3D \}

### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Histogram \}

### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.ParetoLine \}

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.BoxAndWhisker \}

### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Waterfall \}

### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Funnel \}

### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Treemap \}

### MapChart {#MapChart}
```
public static final int MapChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Map \}

### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

این مجموعه از انواع سری‌ها را گروه‌بندی می‌کند: \{ ChartType.Sunburst \}