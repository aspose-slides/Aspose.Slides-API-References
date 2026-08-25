---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs
url: /fr/aspose.slides/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup classe

Énumération des groupes de types de séries combinables.  
Chaque élément se rapporte à un groupe de types de séries de diagramme qui peuvent coexister simultanément dans un ChartSeriesGroup.  
Par exemple : les séries ChartType.PercentsStackedArea ne peuvent pas être simultanément avec les séries ChartType.StackedArea dans un ChartSeriesGroup. Mais deux ou plusieurs ChartType.PercentsStackedArea peuvent se trouver dans un ChartSeriesGroup simultanément (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Et les séries ChartType.Line peuvent être avec les séries ChartType.LineWithMarkers simultanément dans un ChartSeriesGroup CombinableSeriesTypesGroup.LineChart_Line.

## Constantes

| Nom | Valeur | Description |
| --- | --- | --- |
[BarOfPieChart](#BarOfPieChart) | 0 | Regroupe cet ensemble de types de séries : { ChartType.BarOfPie } |
[PieOfPieChart](#PieOfPieChart) | 1 | Regroupe cet ensemble de types de séries : { ChartType.PieOfPie } |
[DoughnutChart](#DoughnutChart) | 2 | Regroupe cet ensemble de types de séries : { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
[PieChart](#PieChart) | 3 | Regroupe cet ensemble de types de séries : { ChartType.Pie, ChartType.ExplodedPie } |
[AreaChart_Area](#AreaChart_Area) | 4 | Regroupe cet ensemble de types de séries : { ChartType.Area } |
[AreaChart_PercentsStackedArea](#AreaChart_PercentsStackedArea) | 5 | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedArea } |
[AreaChart_StackedArea](#AreaChart_StackedArea) | 6 | Regroupe cet ensemble de types de séries : { ChartType.StackedArea } |
[BarChart_HorizClustered](#BarChart_HorizClustered) | 7 | Regroupe cet ensemble de types de séries : { ChartType.ClusteredBar } |
[BarChart_HorizStacked](#BarChart_HorizStacked) | 8 | Regroupe cet ensemble de types de séries : { ChartType.StackedBar } |
[BarChart_HorizPercentsStacked](#BarChart_HorizPercentsStacked) | 9 | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedBar } |
[BarChart_VertClustered](#BarChart_VertClustered) | 10 | Regroupe cet ensemble de types de séries : { ChartType.ClusteredColumn } |
[BarChart_VertStacked](#BarChart_VertStacked) | 11 | Regroupe cet ensemble de types de séries : { ChartType.StackedColumn } |
[BarChart_VertPercentsStacked](#BarChart_VertPercentsStacked) | 12 | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedColumn } |
[LineChart_Line](#LineChart_Line) | 13 | Regroupe cet ensemble de types de séries : { ChartType.Line, ChartType.LineWithMarkers } |
[LineChart_StackedLine](#LineChart_StackedLine) | 14 | Regroupe cet ensemble de types de séries : { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
[LineChart_PercentsStackedLine](#LineChart_PercentsStackedLine) | 15 | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
[RadarChart](#RadarChart) | 16 | Regroupe cet ensemble de types de séries : { ChartType.Radar, ChartType.RadarWithMarkers } |
[FilledRadarChart](#FilledRadarChart) | 17 | Regroupe cet ensemble de types de séries : { ChartType.FilledRadar } |
[StockHighLowClose](#StockHighLowClose) | 18 | Regroupe cet ensemble de types de séries : { ChartType.HighLowClose } |
[StockOpenHighLowClose](#StockOpenHighLowClose) | 19 | Regroupe cet ensemble de types de séries : { ChartType.OpenHighLowClose } |
[StockVolumeHighLowClose](#StockVolumeHighLowClose) | 20 | Regroupe cet ensemble de types de séries : { ChartType.VolumeHighLowClose } |
[StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | 21 | Regroupe cet ensemble de types de séries : { ChartType.VolumeOpenHighLowClose } |
[ScatterStraightMarker](#ScatterStraightMarker) | 22 | Regroupe cet ensemble de types de séries : { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
[ScatterSmoothMarker](#ScatterSmoothMarker) | 23 | Regroupe cet ensemble de types de séries : { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
[AreaChart_Area3D](#AreaChart_Area3D) | 24 | Regroupe cet ensemble de types de séries : { ChartType.Area3D } |
[AreaChart_StackedArea3D](#AreaChart_StackedArea3D) | 25 | Regroupe cet ensemble de types de séries : { ChartType.StackedArea3D } |
[AreaChart_PercentsStackedArea3D](#AreaChart_PercentsStackedArea3D) | 26 | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedArea3D } |
[Line3DChart](#Line3DChart) | 27 | Regroupe cet ensemble de types de séries : { ChartType.Line3D } |
[Pie3DChart](#Pie3DChart) | 28 | Regroupe cet ensemble de types de séries : { ChartType.Pie3D, ChartType.ExplodedPie3D } |
[Bar3DChart_Vert](#Bar3DChart_Vert) | 29 | Regroupe cet ensemble de types de séries : { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
[Bar3DChart_VertClustered](#Bar3DChart_VertClustered) | 30 | Regroupe cet ensemble de types de séries : { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
[Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart_VertPercentsStackedColumn3D) | 31 | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedColumn3D } |
[Bar3DChart_VertPercentsStackedCone](#Bar3DChart_VertPercentsStackedCone) | 32 | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedCone } |
[Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart_VertPercentsStackedCylinder) | 33 | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedCylinder } |
[Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart_VertPercentsStackedPyramid) | 34 | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedPyramid } |
[Bar3DChart_VertStackedColumn3D](#Bar3DChart_VertStackedColumn3D) | 35 | Regroupe cet ensemble de types de séries : { ChartType.StackedColumn3D } |
[Bar3DChart_VertStackedCone](#Bar3DChart_VertStackedCone) | 36 | Regroupe cet ensemble de types de séries : { ChartType.StackedCone } |
[Bar3DChart_VertStackedCylinder](#Bar3DChart_VertStackedCylinder) | 37 | Regroupe cet ensemble de types de séries : { ChartType.StackedCylinder } |
[Bar3DChart_VertStackedPyramid](#Bar3DChart_VertStackedPyramid) | 38 | Regroupe cet ensemble de types de séries : { ChartType.StackedPyramid } |
[Bar3DChart_HorizClustered](#Bar3DChart_HorizClustered) | 39 | Regroupe cet ensemble de types de séries : { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
[Bar3DChart_HorizStackedBar3D](#Bar3DChart_HorizStackedBar3D) | 40 | Regroupe cet ensemble de types de séries : { ChartType.StackedBar3D } |
[Bar3DChart_HorizStackedCone](#Bar3DChart_HorizStackedCone) | 41 | Regroupe cet ensemble de types de séries : { ChartType.StackedHorizontalCone } |
[Bar3DChart_HorizStackedCylinder](#Bar3DChart_HorizStackedCylinder) | 42 | Regroupe cet ensemble de types de séries : { ChartType.StackedHorizontalCylinder } |
[Bar3DChart_HorizStackedPyramid](#Bar3DChart_HorizStackedPyramid) | 43 | Regroupe cet ensemble de types de séries : { ChartType.StackedHorizontalPyramid } |
[Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart_HorizPercentsStackedBar3D) | 44 | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedBar3D } |
[Bar3DChart_HorizPercentsStackedCone](#Bar3DChart_HorizPercentsStackedCone) | 45 | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedHorizontalCone } |
[Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart_HorizPercentsStackedCylinder) | 46 | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedHorizontalCylinder } |
[Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart_HorizPercentsStackedPyramid) | 47 | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedHorizontalPyramid } |
[SurfaceChart_Contour](#SurfaceChart_Contour) | 48 | Regroupe cet ensemble de types de séries : { ChartType.Contour } |
[SurfaceChart_WireframeContour](#SurfaceChart_WireframeContour) | 49 | Regroupe cet ensemble de types de séries : { ChartType.WireframeContour } |
[SurfaceChart_Surface3D](#SurfaceChart_Surface3D) | 50 | Regroupe cet ensemble de types de séries : { ChartType.Surface3D } |
[SurfaceChart_WireframeSurface3D](#SurfaceChart_WireframeSurface3D) | 51 | Regroupe cet ensemble de types de séries : { ChartType.WireframeSurface3D } |
[BubbleChart](#BubbleChart) | 52 | Regroupe cet ensemble de types de séries : { ChartType.Bubble, ChartType.BubbleWith3D } |
[HistogramChart](#HistogramChart) | 53 | Regroupe cet ensemble de types de séries : { ChartType.Histogram } |
[ParetoLineChart](#ParetoLineChart) | 54 | Regroupe cet ensemble de types de séries : { ChartType.ParetoLine } |
[BoxAndWhiskerChart](#BoxAndWhiskerChart) | 55 | Regroupe cet ensemble de types de séries : { ChartType.BoxAndWhisker } |
[WaterfallChart](#WaterfallChart) | 56 | Regroupe cet ensemble de types de séries : { ChartType.Waterfall } |
[FunnelChart](#FunnelChart) | 57 | Regroupe cet ensemble de types de séries : { ChartType.Funnel } |
[TreemapChart](#TreemapChart) | 58 | Regroupe cet ensemble de types de séries : { ChartType.Treemap } |
[MapChart](#MapChart) | 59 | Regroupe cet ensemble de types de séries : { ChartType.Map } |
[SunburstChart](#SunburstChart) | 60 | Regroupe cet ensemble de types de séries : { ChartType.Sunburst } |

---


### BarOfPieChart {#BarOfPieChart}
Regroupe cet ensemble de types de séries : { ChartType.BarOfPie }

---

### PieOfPieChart {#PieOfPieChart}
Regroupe cet ensemble de types de séries : { ChartType.PieOfPie }

---

### DoughnutChart {#DoughnutChart}
Regroupe cet ensemble de types de séries : { ChartType.Doughnut, ChartType.ExplodedDoughnut }

---

### PieChart {#PieChart}
Regroupe cet ensemble de types de séries : { ChartType.Pie, ChartType.ExplodedPie }

---

### AreaChart_Area {#AreaChart_Area}
Regroupe cet ensemble de types de séries : { ChartType.Area }

---

### AreaChart_PercentsStackedArea {#AreaChart_PercentsStackedArea}
Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedArea }

---

### AreaChart_StackedArea {#AreaChart_StackedArea}
Regroupe cet ensemble de types de séries : { ChartType.StackedArea }

---

### BarChart_HorizClustered {#BarChart_HorizClustered}
Regroupe cet ensemble de types de séries : { ChartType.ClusteredBar }

---

### BarChart_HorizStacked {#BarChart_HorizStacked}
Regroupe cet ensemble de types de séries : { ChartType.StackedBar }

---

### BarChart_HorizPercentsStacked {#BarChart_HorizPercentsStacked}
Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedBar }

---

### BarChart_VertClustered {#BarChart_VertClustered}
Regroupe cet ensemble de types de séries : { ChartType.ClusteredColumn }

---

### BarChart_VertStacked {#BarChart_VertStacked}
Regroupe cet ensemble de types de séries : { ChartType.StackedColumn }

---

### BarChart_VertPercentsStacked {#BarChart_VertPercentsStacked}
Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedColumn }

---

### LineChart_Line {#LineChart_Line}
Regroupe cet ensemble de types de séries : { ChartType.Line, ChartType.LineWithMarkers }

---

### LineChart_StackedLine {#LineChart_StackedLine}
Regroupe cet ensemble de types de séries : { ChartType.StackedLine, ChartType.StackedLineWithMarkers }

---

### LineChart_PercentsStackedLine {#LineChart_PercentsStackedLine}
Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers }

---

### RadarChart {#RadarChart}
Regroupe cet ensemble de types de séries : { ChartType.Radar, ChartType.RadarWithMarkers }

---

### FilledRadarChart {#FilledRadarChart}
Regroupe cet ensemble de types de séries : { ChartType.FilledRadar }

---

### StockHighLowClose {#StockHighLowClose}
Regroupe cet ensemble de types de séries : { ChartType.HighLowClose }

---

### StockOpenHighLowClose {#StockOpenHighLowClose}
Regroupe cet ensemble de types de séries : { ChartType.OpenHighLowClose }

---

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
Regroupe cet ensemble de types de séries : { ChartType.VolumeHighLowClose }

---

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
Regroupe cet ensemble de types de séries : { ChartType.VolumeOpenHighLowClose }

---

### ScatterStraightMarker {#ScatterStraightMarker}
Regroupe cet ensemble de types de séries : { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers }

---

### ScatterSmoothMarker {#ScatterSmoothMarker}
Regroupe cet ensemble de types de séries : { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers }

---

### AreaChart_Area3D {#AreaChart_Area3D}
Regroupe cet ensemble de types de séries : { ChartType.Area3D }

---

### AreaChart_StackedArea3D {#AreaChart_StackedArea3D}
Regroupe cet ensemble de types de séries : { ChartType.StackedArea3D }

---

### AreaChart_PercentsStackedArea3D {#AreaChart_PercentsStackedArea3D}
Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedArea3D }

---

### Line3DChart {#Line3DChart}
Regroupe cet ensemble de types de séries : { ChartType.Line3D }

---

### Pie3DChart {#Pie3DChart}
Regroupe cet ensemble de types de séries : { ChartType.Pie3D, ChartType.ExplodedPie3D }

---

### Bar3DChart_Vert {#Bar3DChart_Vert}
Regroupe cet ensemble de types de séries : { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D }

---

### Bar3DChart_VertClustered {#Bar3DChart_VertClustered}
Regroupe cet ensemble de types de séries : { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid }

---

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart_VertPercentsStackedColumn3D}
Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedColumn3D }

---

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart_VertPercentsStackedCone}
Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedCone }

---

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart_VertPercentsStackedCylinder}
Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedCylinder }

---

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart_VertPercentsStackedPyramid}
Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedPyramid }

---

### Bar3DChart_VertStackedColumn3D {#Bar3DChart_VertStackedColumn3D}
Regroupe cet ensemble de types de séries : { ChartType.StackedColumn3D }

---

### Bar3DChart_VertStackedCone {#Bar3DChart_VertStackedCone}
Regroupe cet ensemble de types de séries : { ChartType.StackedCone }

---

### Bar3DChart_VertStackedCylinder {#Bar3DChart_VertStackedCylinder}
Regroupe cet ensemble de types de séries : { ChartType.StackedCylinder }

---

### Bar3DChart_VertStackedPyramid {#Bar3DChart_VertStackedPyramid}
Regroupe cet ensemble de types de séries : { ChartType.StackedPyramid }

---

### Bar3DChart_HorizClustered {#Bar3DChart_HorizClustered}
Regroupe cet ensemble de types de séries : { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid }

---

### Bar3DChart_HorizStackedBar3D {#Bar3DChart_HorizStackedBar3D}
Regroupe cet ensemble de types de séries : { ChartType.StackedBar3D }

---

### Bar3DChart_HorizStackedCone {#Bar3DChart_HorizStackedCone}
Regroupe cet ensemble de types de séries : { ChartType.StackedHorizontalCone }

---

### Bar3DChart_HorizStackedCylinder {#Bar3DChart_HorizStackedCylinder}
Regroupe cet ensemble de types de séries : { ChartType.StackedHorizontalCylinder }

---

### Bar3DChart_HorizStackedPyramid {#Bar3DChart_HorizStackedPyramid}
Regroupe cet ensemble de types de séries : { ChartType.StackedHorizontalPyramid }

---

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart_HorizPercentsStackedBar3D}
Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedBar3D }

---

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart_HorizPercentsStackedCone}
Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedHorizontalCone }

---

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart_HorizPercentsStackedCylinder}
Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedHorizontalCylinder }

---

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart_HorizPercentsStackedPyramid}
Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedHorizontalPyramid }

---

### SurfaceChart_Contour {#SurfaceChart_Contour}
Regroupe cet ensemble de types de séries : { ChartType.Contour }

---

### SurfaceChart_WireframeContour {#SurfaceChart_WireframeContour}
Regroupe cet ensemble de types de séries : { ChartType.WireframeContour }

---

### SurfaceChart_Surface3D {#SurfaceChart_Surface3D}
Regroupe cet ensemble de types de séries : { ChartType.Surface3D }

---

### SurfaceChart_WireframeSurface3D {#SurfaceChart_WireframeSurface3D}
Regroupe cet ensemble de types de séries : { ChartType.WireframeSurface3D }

---

### BubbleChart {#BubbleChart}
Regroupe cet ensemble de types de séries : { ChartType.Bubble, ChartType.BubbleWith3D }

---

### HistogramChart {#HistogramChart}
Regroupe cet ensemble de types de séries : { ChartType.Histogram }

---

### ParetoLineChart {#ParetoLineChart}
Regroupe cet ensemble de types de séries : { ChartType.ParetoLine }

---

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
Regroupe cet ensemble de types de séries : { ChartType.BoxAndWhisker }

---

### WaterfallChart {#WaterfallChart}
Regroupe cet ensemble de types de séries : { ChartType.Waterfall }

---

### FunnelChart {#FunnelChart}
Regroupe cet ensemble de types de séries : { ChartType.Funnel }

---

### TreemapChart {#TreemapChart}
Regroupe cet ensemble de types de séries : { ChartType.Treemap }

---

### MapChart {#MapChart}
Regroupe cet ensemble de types de séries : { ChartType.Map }

---

### SunburstChart {#SunburstChart}
Regroupe cet ensemble de types de séries : { ChartType.Sunburst }

---