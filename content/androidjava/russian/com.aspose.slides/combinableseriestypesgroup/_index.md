---
title: CombinableSeriesTypesGroup
second_title: Справочник API Aspose.Slides для Android через Java
description: Перечисление групп комбинируемых типов рядов.
type: docs
url: /ru/com.aspose.slides/combinableseriestypesgroup/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CombinableSeriesTypesGroup extends System.Enum
```

Перечисление групп комбинируемых типов рядов. Каждый элемент относится к группе типов рядов диаграммы, которые могут существовать одновременно в одном ChartSeriesGroup. Например, ChartType.PercentsStackedArea series cannot be simultaneously with ChartType.StackedArea series in one ChartSeriesGroup. But two or more ChartType.PercentsStackedArea can be in one ChartSeriesGroup simultaneously (CombinableSeriesTypesGroup.AreaChart\_PercentsStackedArea). And ChartType.Line series can be with ChartType.LineWithMarkers series simultaneously in one CombinableSeriesTypesGroup.LineChart\_Line ChartSeriesGroup.
## Поля

| Поле | Описание |
| --- | --- |
| [AreaChart_Area](#AreaChart-Area) | Группирует этот набор типов рядов: \{ ChartType.Area \} |
| [AreaChart_PercentsStackedArea](#AreaChart-PercentsStackedArea) | Группирует этот набор типов рядов: \{ ChartType.PercentsStackedArea \} |
| [AreaChart_StackedArea](#AreaChart-StackedArea) | Группирует этот набор типов рядов: \{ ChartType.StackedArea \} |
| [AreaChart_Area3D](#AreaChart-Area3D) | Группирует этот набор типов рядов: \{ ChartType.Area3D \} |
| [AreaChart_StackedArea3D](#AreaChart-StackedArea3D) | Группирует этот набор типов рядов: \{ ChartType.StackedArea3D \} |
| [AreaChart_PercentsStackedArea3D](#AreaChart-PercentsStackedArea3D) | Группирует этот набор типов рядов: \{ ChartType.PercentsStackedArea3D \} |
| [LineChart_Line](#LineChart-Line) | Группирует этот набор типов рядов: \{ ChartType.Line, ChartType.LineWithMarkers \} |
| [LineChart_StackedLine](#LineChart-StackedLine) | Группирует этот набор типов рядов: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \} |
| [LineChart_PercentsStackedLine](#LineChart-PercentsStackedLine) | Группирует этот набор типов рядов: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \} |
| [Line3DChart](#Line3DChart) | Группирует этот набор типов рядов: \{ ChartType.Line3D \} |
| [StockHighLowClose](#StockHighLowClose) | Группирует этот набор типов рядов: \{ ChartType.HighLowClose \} |
| [StockOpenHighLowClose](#StockOpenHighLowClose) | Группирует этот набор типов рядов: \{ ChartType.OpenHighLowClose \} |
| [StockVolumeHighLowClose](#StockVolumeHighLowClose) | Группирует этот набор типов рядов: \{ ChartType.VolumeHighLowClose \} |
| [StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | Группирует этот набор типов рядов: \{ ChartType.VolumeOpenHighLowClose \} |
| [RadarChart](#RadarChart) | Группирует этот набор типов рядов: \{ ChartType.Radar, ChartType.RadarWithMarkers \} |
| [FilledRadarChart](#FilledRadarChart) | Группирует этот набор типов рядов: \{ ChartType.FilledRadar \} |
| [ScatterStraightMarker](#ScatterStraightMarker) | Группирует этот набор типов рядов: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \} |
| [ScatterSmoothMarker](#ScatterSmoothMarker) | Группирует этот набор типов рядов: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \} |
| [PieChart](#PieChart) | Группирует этот набор типов рядов: \{ ChartType.Pie, ChartType.ExplodedPie \} |
| [Pie3DChart](#Pie3DChart) | Группирует этот набор типов рядов: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \} |
| [DoughnutChart](#DoughnutChart) | Группирует этот набор типов рядов: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \} |
| [BarChart_VertClustered](#BarChart-VertClustered) | Группирует этот набор типов рядов: \{ ChartType.ClusteredColumn \} |
| [BarChart_VertStacked](#BarChart-VertStacked) | Группирует этот набор типов рядов: \{ ChartType.StackedColumn \} |
| [BarChart_VertPercentsStacked](#BarChart-VertPercentsStacked) | Группирует этот набор типов рядов: \{ ChartType.PercentsStackedColumn \} |
| [BarChart_HorizClustered](#BarChart-HorizClustered) | Группирует этот набор типов рядов: \{ ChartType.ClusteredBar \} |
| [BarChart_HorizStacked](#BarChart-HorizStacked) | Группирует этот набор типов рядов: \{ ChartType.StackedBar \} |
| [BarChart_HorizPercentsStacked](#BarChart-HorizPercentsStacked) | Группирует этот набор типов рядов: \{ ChartType.PercentsStackedBar \} |
| [Bar3DChart_Vert](#Bar3DChart-Vert) | Группирует этот набор типов рядов: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \} |
| [Bar3DChart_VertClustered](#Bar3DChart-VertClustered) | Группирует этот набор типов рядов: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \} |
| [Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart-VertPercentsStackedColumn3D) | Группирует этот набор типов рядов: \{ ChartType.PercentsStackedColumn3D \} |
| [Bar3DChart_VertPercentsStackedCone](#Bar3DChart-VertPercentsStackedCone) | Группирует этот набор типов рядов: \{ ChartType.PercentsStackedCone \} |
| [Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart-VertPercentsStackedCylinder) | Группирует этот набор типов рядов: \{ ChartType.PercentsStackedCylinder \} |
| [Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart-VertPercentsStackedPyramid) | Группирует этот набор типов рядов: \{ ChartType.PercentsStackedPyramid \} |
| [Bar3DChart_VertStackedColumn3D](#Bar3DChart-VertStackedColumn3D) | Группирует этот набор типов рядов: \{ ChartType.StackedColumn3D \} |
| [Bar3DChart_VertStackedCone](#Bar3DChart-VertStackedCone) | Группирует этот набор типов рядов: \{ ChartType.StackedCone \} |
| [Bar3DChart_VertStackedCylinder](#Bar3DChart-VertStackedCylinder) | Группирует этот набор типов рядов: \{ ChartType.StackedCylinder \} |
| [Bar3DChart_VertStackedPyramid](#Bar3DChart-VertStackedPyramid) | Группирует этот набор типов рядов: \{ ChartType.StackedPyramid \} |
| [Bar3DChart_HorizClustered](#Bar3DChart-HorizClustered) | Группирует этот набор типов рядов: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \} |
| [Bar3DChart_HorizStackedBar3D](#Bar3DChart-HorizStackedBar3D) | Группирует этот набор типов рядов: \{ ChartType.StackedBar3D \} |
| [Bar3DChart_HorizStackedCone](#Bar3DChart-HorizStackedCone) | Группирует этот набор типов рядов: \{ ChartType.StackedHorizontalCone \} |
| [Bar3DChart_HorizStackedCylinder](#Bar3DChart-HorizStackedCylinder) | Группирует этот набор типов рядов: \{ ChartType.StackedHorizontalCylinder \} |
| [Bar3DChart_HorizStackedPyramid](#Bar3DChart-HorizStackedPyramid) | Группирует этот набор типов рядов: \{ ChartType.StackedHorizontalPyramid \} |
| [Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart-HorizPercentsStackedBar3D) | Группирует этот набор типов рядов: \{ ChartType.PercentsStackedBar3D \} |
| [Bar3DChart_HorizPercentsStackedCone](#Bar3DChart-HorizPercentsStackedCone) | Группирует этот набор типов рядов: \{ ChartType.PercentsStackedHorizontalCone \} |
| [Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart-HorizPercentsStackedCylinder) | Группирует этот набор типов рядов: \{ ChartType.PercentsStackedHorizontalCylinder \} |
| [Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart-HorizPercentsStackedPyramid) | Группирует этот набор типов рядов: \{ ChartType.PercentsStackedHorizontalPyramid \} |
| [BarOfPieChart](#BarOfPieChart) | Группирует этот набор типов рядов: \{ ChartType.BarOfPie \} |
| [PieOfPieChart](#PieOfPieChart) | Группирует этот набор типов рядов: \{ ChartType.PieOfPie \} |
| [SurfaceChart_Contour](#SurfaceChart-Contour) | Группирует этот набор типов рядов: \{ ChartType.Contour \} |
| [SurfaceChart_WireframeContour](#SurfaceChart-WireframeContour) | Группирует этот набор типов рядов: \{ ChartType.WireframeContour \} |
| [SurfaceChart_Surface3D](#SurfaceChart-Surface3D) | Группирует этот набор типов рядов: \{ ChartType.Surface3D \} |
| [SurfaceChart_WireframeSurface3D](#SurfaceChart-WireframeSurface3D) | Группирует этот набор типов рядов: \{ ChartType.WireframeSurface3D \} |
| [BubbleChart](#BubbleChart) | Группирует этот набор типов рядов: \{ ChartType.Bubble, ChartType.BubbleWith3D \} |
| [HistogramChart](#HistogramChart) | Группирует этот набор типов рядов: \{ ChartType.Histogram \} |
| [ParetoLineChart](#ParetoLineChart) | Группирует этот набор типов рядов: \{ ChartType.ParetoLine \} |
| [BoxAndWhiskerChart](#BoxAndWhiskerChart) | Группирует этот набор типов рядов: \{ ChartType.BoxAndWhisker \} |
| [WaterfallChart](#WaterfallChart) | Группирует этот набор типов рядов: \{ ChartType.Waterfall \} |
| [FunnelChart](#FunnelChart) | Группирует этот набор типов рядов: \{ ChartType.Funnel \} |
| [TreemapChart](#TreemapChart) | Группирует этот набор типов рядов: \{ ChartType.Treemap \} |
| [MapChart](#MapChart) | Группирует этот набор типов рядов: \{ ChartType.Map \} |
| [SunburstChart](#SunburstChart) | Группирует этот набор типов рядов: \{ ChartType.Sunburst \} |
### AreaChart_Area {#AreaChart-Area}
```
public static final int AreaChart_Area
```

Группирует этот набор типов рядов: \{ ChartType.Area \}
### AreaChart_PercentsStackedArea {#AreaChart-PercentsStackedArea}
```
public static final int AreaChart_PercentsStackedArea
```

Группирует этот набор типов рядов: \{ ChartType.PercentsStackedArea \}
### AreaChart_StackedArea {#AreaChart-StackedArea}
```
public static final int AreaChart_StackedArea
```

Группирует этот набор типов рядов: \{ ChartType.StackedArea \}
### AreaChart_Area3D {#AreaChart-Area3D}
```
public static final int AreaChart_Area3D
```

Группирует этот набор типов рядов: \{ ChartType.Area3D \}
### AreaChart_StackedArea3D {#AreaChart-StackedArea3D}
```
public static final int AreaChart_StackedArea3D
```

Группирует этот набор типов рядов: \{ ChartType.StackedArea3D \}
### AreaChart_PercentsStackedArea3D {#AreaChart-PercentsStackedArea3D}
```
public static final int AreaChart_PercentsStackedArea3D
```

Группирует этот набор типов рядов: \{ ChartType.PercentsStackedArea3D \}
### LineChart_Line {#LineChart-Line}
```
public static final int LineChart_Line
```

Группирует этот набор типов рядов: \{ ChartType.Line, ChartType.LineWithMarkers \}
### LineChart_StackedLine {#LineChart-StackedLine}
```
public static final int LineChart_StackedLine
```

Группирует этот набор типов рядов: \{ ChartType.StackedLine, ChartType.StackedLineWithMarkers \}
### LineChart_PercentsStackedLine {#LineChart-PercentsStackedLine}
```
public static final int LineChart_PercentsStackedLine
```

Группирует этот набор типов рядов: \{ ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers \}
### Line3DChart {#Line3DChart}
```
public static final int Line3DChart
```

Группирует этот набор типов рядов: \{ ChartType.Line3D \}
### StockHighLowClose {#StockHighLowClose}
```
public static final int StockHighLowClose
```

Группирует этот набор типов рядов: \{ ChartType.HighLowClose \}
### StockOpenHighLowClose {#StockOpenHighLowClose}
```
public static final int StockOpenHighLowClose
```

Группирует этот набор типов рядов: \{ ChartType.OpenHighLowClose \}
### StockVolumeHighLowClose {#StockVolumeHighLowClose}
```
public static final int StockVolumeHighLowClose
```

Группирует этот набор типов рядов: \{ ChartType.VolumeHighLowClose \}
### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
```
public static final int StockVolumeOpenHighLowClose
```

Группирует этот набор типов рядов: \{ ChartType.VolumeOpenHighLowClose \}
### RadarChart {#RadarChart}
```
public static final int RadarChart
```

Группирует этот набор типов рядов: \{ ChartType.Radar, ChartType.RadarWithMarkers \}
### FilledRadarChart {#FilledRadarChart}
```
public static final int FilledRadarChart
```

Группирует этот набор типов рядов: \{ ChartType.FilledRadar \}
### ScatterStraightMarker {#ScatterStraightMarker}
```
public static final int ScatterStraightMarker
```

Группирует этот набор типов рядов: \{ ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers \}
### ScatterSmoothMarker {#ScatterSmoothMarker}
```
public static final int ScatterSmoothMarker
```

Группирует этот набор типов рядов: \{ ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers \}
### PieChart {#PieChart}
```
public static final int PieChart
```

Группирует этот набор типов рядов: \{ ChartType.Pie, ChartType.ExplodedPie \}
### Pie3DChart {#Pie3DChart}
```
public static final int Pie3DChart
```

Группирует этот набор типов рядов: \{ ChartType.Pie3D, ChartType.ExplodedPie3D \}
### DoughnutChart {#DoughnutChart}
```
public static final int DoughnutChart
```

Группирует этот набор типов рядов: \{ ChartType.Doughnut, ChartType.ExplodedDoughnut \}
### BarChart_VertClustered {#BarChart-VertClustered}
```
public static final int BarChart_VertClustered
```

Группирует этот набор типов рядов: \{ ChartType.ClusteredColumn \}
### BarChart_VertStacked {#BarChart-VertStacked}
```
public static final int BarChart_VertStacked
```

Группирует этот набор типов рядов: \{ ChartType.StackedColumn \}
### BarChart_VertPercentsStacked {#BarChart-VertPercentsStacked}
```
public static final int BarChart_VertPercentsStacked
```

Группирует этот набор типов рядов: \{ ChartType.PercentsStackedColumn \}
### BarChart_HorizClustered {#BarChart-HorizClustered}
```
public static final int BarChart_HorizClustered
```

Группирует этот набор типов рядов: \{ ChartType.ClusteredBar \}
### BarChart_HorizStacked {#BarChart-HorizStacked}
```
public static final int BarChart_HorizStacked
```

Группирует этот набор типов рядов: \{ ChartType.StackedBar \}
### BarChart_HorizPercentsStacked {#BarChart-HorizPercentsStacked}
```
public static final int BarChart_HorizPercentsStacked
```

Группирует этот набор типов рядов: \{ ChartType.PercentsStackedBar \}
### Bar3DChart_Vert {#Bar3DChart-Vert}
```
public static final int Bar3DChart_Vert
```

Группирует этот набор типов рядов: \{ ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D \}
### Bar3DChart_VertClustered {#Bar3DChart-VertClustered}
```
public static final int Bar3DChart_VertClustered
```

Группирует этот набор типов рядов: \{ ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid \}
### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart-VertPercentsStackedColumn3D}
```
public static final int Bar3DChart_VertPercentsStackedColumn3D
```

Группирует этот набор типов рядов: \{ ChartType.PercentsStackedColumn3D \}
### Bar3DChart_VertPercentsStackedCone {#Bar3DChart-VertPercentsStackedCone}
```
public static final int Bar3DChart_VertPercentsStackedCone
```

Группирует этот набор типов рядов: \{ ChartType.PercentsStackedCone \}
### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart-VertPercentsStackedCylinder}
```
public static final int Bar3DChart_VertPercentsStackedCylinder
```

Группирует этот набор типов рядов: \{ ChartType.PercentsStackedCylinder \}
### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart-VertPercentsStackedPyramid}
```
public static final int Bar3DChart_VertPercentsStackedPyramid
```

Группирует этот набор типов рядов: \{ ChartType.PercentsStackedPyramid \}
### Bar3DChart_VertStackedColumn3D {#Bar3DChart-VertStackedColumn3D}
```
public static final int Bar3DChart_VertStackedColumn3D
```

Группирует этот набор типов рядов: \{ ChartType.StackedColumn3D \}
### Bar3DChart_VertStackedCone {#Bar3DChart-VertStackedCone}
```
public static final int Bar3DChart_VertStackedCone
```

Группирует этот набор типов рядов: \{ ChartType.StackedCone \}
### Bar3DChart_VertStackedCylinder {#Bar3DChart-VertStackedCylinder}
```
public static final int Bar3DChart_VertStackedCylinder
```

Группирует этот набор типов рядов: \{ ChartType.StackedCylinder \}
### Bar3DChart_VertStackedPyramid {#Bar3DChart-VertStackedPyramid}
```
public static final int Bar3DChart_VertStackedPyramid
```

Группирует этот набор типов рядов: \{ ChartType.StackedPyramid \}
### Bar3DChart_HorizClustered {#Bar3DChart-HorizClustered}
```
public static final int Bar3DChart_HorizClustered
```

Группирует этот набор типов рядов: \{ ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid \}
### Bar3DChart_HorizStackedBar3D {#Bar3DChart-HorizStackedBar3D}
```
public static final int Bar3DChart_HorizStackedBar3D
```

Группирует этот набор типов рядов: \{ ChartType.StackedBar3D \}
### Bar3DChart_HorizStackedCone {#Bar3DChart-HorizStackedCone}
```
public static final int Bar3DChart_HorizStackedCone
```

Группирует этот набор типов рядов: \{ ChartType.StackedHorizontalCone \}
### Bar3DChart_HorizStackedCylinder {#Bar3DChart-HorizStackedCylinder}
```
public static final int Bar3DChart_HorizStackedCylinder
```

Группирует этот набор типов рядов: \{ ChartType.StackedHorizontalCylinder \}
### Bar3DChart_HorizStackedPyramid {#Bar3DChart-HorizStackedPyramid}
```
public static final int Bar3DChart_HorizStackedPyramid
```

Группирует этот набор типов рядов: \{ ChartType.StackedHorizontalPyramid \}
### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart-HorizPercentsStackedBar3D}
```
public static final int Bar3DChart_HorizPercentsStackedBar3D
```

Группирует этот набор типов рядов: \{ ChartType.PercentsStackedBar3D \}
### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart-HorizPercentsStackedCone}
```
public static final int Bar3DChart_HorizPercentsStackedCone
```

Группирует этот набор типов рядов: \{ ChartType.PercentsStackedHorizontalCone \}
### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart-HorizPercentsStackedCylinder}
```
public static final int Bar3DChart_HorizPercentsStackedCylinder
```

Группирует этот набор типов рядов: \{ ChartType.PercentsStackedHorizontalCylinder \}
### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart-HorizPercentsStackedPyramid}
```
public static final int Bar3DChart_HorizPercentsStackedPyramid
```

Группирует этот набор типов рядов: \{ ChartType.PercentsStackedHorizontalPyramid \}
### BarOfPieChart {#BarOfPieChart}
```
public static final int BarOfPieChart
```

Группирует этот набор типов рядов: \{ ChartType.BarOfPie \}
### PieOfPieChart {#PieOfPieChart}
```
public static final int PieOfPieChart
```

Группирует этот набор типов рядов: \{ ChartType.PieOfPie \}
### SurfaceChart_Contour {#SurfaceChart-Contour}
```
public static final int SurfaceChart_Contour
```

Группирует этот набор типов рядов: \{ ChartType.Contour \}
### SurfaceChart_WireframeContour {#SurfaceChart-WireframeContour}
```
public static final int SurfaceChart_WireframeContour
```

Группирует этот набор типов рядов: \{ ChartType.WireframeContour \}
### SurfaceChart_Surface3D {#SurfaceChart-Surface3D}
```
public static final int SurfaceChart_Surface3D
```

Группирует этот набор типов рядов: \{ ChartType.Surface3D \}
### SurfaceChart_WireframeSurface3D {#SurfaceChart-WireframeSurface3D}
```
public static final int SurfaceChart_WireframeSurface3D
```

Группирует этот набор типов рядов: \{ ChartType.WireframeSurface3D \}
### BubbleChart {#BubbleChart}
```
public static final int BubbleChart
```

Группирует этот набор типов рядов: \{ ChartType.Bubble, ChartType.BubbleWith3D \}
### HistogramChart {#HistogramChart}
```
public static final int HistogramChart
```

Группирует этот набор типов рядов: \{ ChartType.Histogram \}
### ParetoLineChart {#ParetoLineChart}
```
public static final int ParetoLineChart
```

Группирует этот набор типов рядов: \{ ChartType.ParetoLine \}
### BoxAndWhiskerChart {#BoxAndWhiskerChart}
```
public static final int BoxAndWhiskerChart
```

Группирует этот набор типов рядов: \{ ChartType.BoxAndWhisker \}
### WaterfallChart {#WaterfallChart}
```
public static final int WaterfallChart
```

Группирует этот набор типов рядов: \{ ChartType.Waterfall \}
### FunnelChart {#FunnelChart}
```
public static final int FunnelChart
```

Группирует этот набор типов рядов: \{ ChartType.Funnel \}
### TreemapChart {#TreemapChart}
```
public static final int TreemapChart
```

Группирует этот набор типов рядов: \{ ChartType.Treemap \}
### MapChart {#MapChart}
```
public static final int MapChart
```

Группирует этот набор типов рядов: \{ ChartType.Map \}
### SunburstChart {#SunburstChart}
```
public static final int SunburstChart
```

Группирует этот набор типов рядов: \{ ChartType.Sunburst \}