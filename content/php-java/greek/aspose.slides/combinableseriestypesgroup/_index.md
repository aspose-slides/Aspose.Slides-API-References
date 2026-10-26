---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup κλάση

Απαρίθμηση ομάδων συνδυάσιμων τύπων σειρών.
Κάθε στοιχείο σχετίζεται με μια ομάδα τύπων σειρών γραφήματος που μπορούν να συνυπάρχουν ταυτόχρονα σε ένα ChartSeriesGroup.
Για παράδειγμα: η σειρά ChartType.PercentsStackedArea δεν μπορεί να είναι ταυτόχρονα με τη σειρά ChartType.StackedArea σε ένα ChartSeriesGroup.
Αλλά δύο ή περισσότερες σειρές ChartType.PercentsStackedArea μπορούν να βρίσκονται ταυτόχρονα σε ένα ChartSeriesGroup (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea).
Και οι σειρές ChartType.Line μπορούν να είναι με τις σειρές ChartType.LineWithMarkers ταυτόχρονα σε ένα CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

## Σταθερές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
[BarOfPieChart](#BarOfPieChart) | 0 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.BarOfPie } |
[PieOfPieChart](#PieOfPieChart) | 1 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PieOfPie } |
[DoughnutChart](#DoughnutChart) | 2 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
[PieChart](#PieChart) | 3 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Pie, ChartType.ExplodedPie } |
[AreaChart_Area](#AreaChart_Area) | 4 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Area } |
[AreaChart_PercentsStackedArea](#AreaChart_PercentsStackedArea) | 5 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedArea } |
[AreaChart_StackedArea](#AreaChart_StackedArea) | 6 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedArea } |
[BarChart_HorizClustered](#BarChart_HorizClustered) | 7 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ClusteredBar } |
[BarChart_HorizStacked](#BarChart_HorizStacked) | 8 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedBar } |
[BarChart_HorizPercentsStacked](#BarChart_HorizPercentsStacked) | 9 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedBar } |
[BarChart_VertClustered](#BarChart_VertClustered) | 10 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ClusteredColumn } |
[BarChart_VertStacked](#BarChart_VertStacked) | 11 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedColumn } |
[BarChart_VertPercentsStacked](#BarChart_VertPercentsStacked) | 12 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedColumn } |
[LineChart_Line](#LineChart_Line) | 13 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Line, ChartType.LineWithMarkers } |
[LineChart_StackedLine](#LineChart_StackedLine) | 14 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
[LineChart_PercentsStackedLine](#LineChart_PercentsStackedLine) | 15 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
[RadarChart](#RadarChart) | 16 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Radar, ChartType.RadarWithMarkers } |
[FilledRadarChart](#FilledRadarChart) | 17 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.FilledRadar } |
[StockHighLowClose](#StockHighLowClose) | 18 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.HighLowClose } |
[StockOpenHighLowClose](#StockOpenHighLowClose) | 19 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.OpenHighLowClose } |
[StockVolumeHighLowClose](#StockVolumeHighLowClose) | 20 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.VolumeHighLowClose } |
[StockVolumeOpenHighLowClose](#StockVolumeOpenHighLowClose) | 21 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.VolumeOpenHighLowClose } |
[ScatterStraightMarker](#ScatterStraightMarker) | 22 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
[ScatterSmoothMarker](#ScatterSmoothMarker) | 23 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
[AreaChart_Area3D](#AreaChart_Area3D) | 24 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Area3D } |
[AreaChart_StackedArea3D](#AreaChart_StackedArea3D) | 25 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedArea3D } |
[AreaChart_PercentsStackedArea3D](#AreaChart_PercentsStackedArea3D) | 26 | Ομαδ  φοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedArea3D } |
[Line3DChart](#Line3DChart) | 27 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Line3D } |
[Pie3DChart](#Pie3DChart) | 28 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
[Bar3DChart_Vert](#Bar3DChart_Vert) | 29 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
[Bar3DChart_VertClustered](#Bar3DChart_VertClustered) | 30 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
[Bar3DChart_VertPercentsStackedColumn3D](#Bar3DChart_VertPercentsStackedColumn3D) | 31 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedColumn3D } |
[Bar3DChart_VertPercentsStackedCone](#Bar3DChart_VertPercentsStackedCone) | 32 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedCone } |
[Bar3DChart_VertPercentsStackedCylinder](#Bar3DChart_VertPercentsStackedCylinder) | 33 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedCylinder } |
[Bar3DChart_VertPercentsStackedPyramid](#Bar3DChart_VertPercentsStackedPyramid) | 34 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedPyramid } |
[Bar3DChart_VertStackedColumn3D](#Bar3DChart_VertStackedColumn3D) | 35 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedColumn3D } |
[Bar3DChart_VertStackedCone](#Bar3DChart_VertStackedCone) | 36 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedCone } |
[Bar3DChart_VertStackedCylinder](#Bar3DChart_VertStackedCylinder) | 37 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedCylinder } |
[Bar3DChart_VertStackedPyramid](#Bar3DChart_VertStackedPyramid) | 38 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedPyramid } |
[Bar3DChart_HorizClustered](#Bar3DChart_HorizClustered) | 39 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
[Bar3DChart_HorizStackedBar3D](#Bar3DChart_HorizStackedBar3D) | 40 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedBar3D } |
[Bar3DChart_HorizStackedCone](#Bar3DChart_HorizStackedCone) | 41 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedHorizontalCone } |
[Bar3DChart_HorizStackedCylinder](#Bar3DChart_HorizStackedCylinder) | 42 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedHorizontalCylinder } |
[Bar3DChart_HorizStackedPyramid](#Bar3DChart_HorizStackedPyramid) | 43 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedHorizontalPyramid } |
[Bar3DChart_HorizPercentsStackedBar3D](#Bar3DChart_HorizPercentsStackedBar3D) | 44 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedBar3D } |
[Bar3DChart_HorizPercentsStackedCone](#Bar3DChart_HorizPercentsStackedCone) | 45 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedHorizontalCone } |
[Bar3DChart_HorizPercentsStackedCylinder](#Bar3DChart_HorizPercentsStackedCylinder) | 46 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedHorizontalCylinder } |
[Bar3DChart_HorizPercentsStackedPyramid](#Bar3DChart_HorizPercentsStackedPyramid) | 47 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedHorizontalPyramid } |
[SurfaceChart_Contour](#SurfaceChart_Contour) | 48 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Contour } |
[SurfaceChart_WireframeContour](#SurfaceChart_WireframeContour) | 49 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.WireframeContour } |
[SurfaceChart_Surface3D](#SurfaceChart_Surface3D) | 50 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Surface3D } |
[SurfaceChart_WireframeSurface3D](#SurfaceChart_WireframeSurface3D) | 51 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.WireframeSurface3D } |
[BubbleChart](#BubbleChart) | 52 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Bubble, ChartType.BubbleWith3D } |
[HistogramChart](#HistogramChart) | 53 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Histogram } |
[ParetoLineChart](#ParetoLineChart) | 54 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ParetoLine } |
[BoxAndWhiskerChart](#BoxAndWhiskerChart) | 55 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.BoxAndWhisker } |
[WaterfallChart](#WaterfallChart) | 56 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Waterfall } |
[FunnelChart](#FunnelChart) | 57 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Funnel } |
[TreemapChart](#TreemapChart) | 58 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Treemap } |
[MapChart](#MapChart) | 59 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Map } |
[SunburstChart](#SunburstChart) | 60 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Sunburst } |

---

### BarOfPieChart {#BarOfPieChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.BarOfPie }

---

### PieOfPieChart {#PieOfPieChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PieOfPie }

---

### DoughnutChart {#DoughnutChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Doughnut, ChartType.ExplodedDoughnut }

---

### PieChart {#PieChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Pie, ChartType.ExplodedPie }

---

### AreaChart_Area {#AreaChart_Area}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Area }

---

### AreaChart_PercentsStackedArea {#AreaChart_PercentsStackedArea}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedArea }

---

### AreaChart_StackedArea {#AreaChart_StackedArea}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedArea }

---

### BarChart_HorizClustered {#BarChart_HorizClustered}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ClusteredBar }

---

### BarChart_HorizStacked {#BarChart_HorizStacked}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedBar }

---

### BarChart_HorizPercentsStacked {#BarChart_HorizPercentsStacked}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedBar }

---

### BarChart_VertClustered {#BarChart_VertClustered}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ClusteredColumn }

---

### BarChart_VertStacked {#BarChart_VertStacked}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedColumn }

---

### BarChart_VertPercentsStacked {#BarChart_VertPercentsStacked}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedColumn }

---

### LineChart_Line {#LineChart_Line}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Line, ChartType.LineWithMarkers }

---

### LineChart_StackedLine {#LineChart_StackedLine}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedLine, ChartType.StackedLineWithMarkers }

---

### LineChart_PercentsStackedLine {#LineChart_PercentsStackedLine}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers }

---

### RadarChart {#RadarChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Radar, ChartType.RadarWithMarkers }

---

### FilledRadarChart {#FilledRadarChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.FilledRadar }

---

### StockHighLowClose {#StockHighLowClose}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.HighLowClose }

---

### StockOpenHighLowClose {#StockOpenHighLowClose}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.OpenHighLowClose }

---

### StockVolumeHighLowClose {#StockVolumeHighLowClose}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.VolumeHighLowClose }

---

### StockVolumeOpenHighLowClose {#StockVolumeOpenHighLowClose}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.VolumeOpenHighLowClose }

---

### ScatterStraightMarker {#ScatterStraightMarker}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers }

---

### ScatterSmoothMarker {#ScatterSmoothMarker}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers }

---

### AreaChart_Area3D {#AreaChart_Area3D}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Area3D }

---

### AreaChart_StackedArea3D {#AreaChart_StackedArea3D}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedArea3D }

---

### AreaChart_PercentsStackedArea3D {#AreaChart_PercentsStackedArea3D}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedArea3D }

---

### Line3DChart {#Line3DChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Line3D }

---

### Pie3DChart {#Pie3DChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Pie3D, ChartType.ExplodedPie3D }

---

### Bar3DChart_Vert {#Bar3DChart_Vert}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D }

---

### Bar3DChart_VertClustered {#Bar3DChart_VertClustered}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid }

---

### Bar3DChart_VertPercentsStackedColumn3D {#Bar3DChart_VertPercentsStackedColumn3D}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedColumn3D }

---

### Bar3DChart_VertPercentsStackedCone {#Bar3DChart_VertPercentsStackedCone}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedCone }

---

### Bar3DChart_VertPercentsStackedCylinder {#Bar3DChart_VertPercentsStackedCylinder}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedCylinder }

---

### Bar3DChart_VertPercentsStackedPyramid {#Bar3DChart_VertPercentsStackedPyramid}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedPyramid }

---

### Bar3DChart_VertStackedColumn3D {#Bar3DChart_VertStackedColumn3D}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedColumn3D }

---

### Bar3DChart_VertStackedCone {#Bar3DChart_VertStackedCone}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedCone }

---

### Bar3DChart_VertStackedCylinder {#Bar3DChart_VertStackedCylinder}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedCylinder }

---

### Bar3DChart_VertStackedPyramid {#Bar3DChart_VertStackedPyramid}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedPyramid }

---

### Bar3DChart_HorizClustered {#Bar3DChart_HorizClustered}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid }

---

### Bar3DChart_HorizStackedBar3D {#Bar3DChart_HorizStackedBar3D}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedBar3D }

---

### Bar3DChart_HorizStackedCone {#Bar3DChart_HorizStackedCone}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedHorizontalCone }

---

### Bar3DChart_HorizStackedCylinder {#Bar3DChart_HorizStackedCylinder}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedHorizontalCylinder }

---

### Bar3DChart_HorizStackedPyramid {#Bar3DChart_HorizStackedPyramid}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedHorizontalPyramid }

---

### Bar3DChart_HorizPercentsStackedBar3D {#Bar3DChart_HorizPercentsStackedBar3D}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedBar3D }

---

### Bar3DChart_HorizPercentsStackedCone {#Bar3DChart_HorizPercentsStackedCone}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedHorizontalCone }

---

### Bar3DChart_HorizPercentsStackedCylinder {#Bar3DChart_HorizPercentsStackedCylinder}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedHorizontalCylinder }

---

### Bar3DChart_HorizPercentsStackedPyramid {#Bar3DChart_HorizPercentsStackedPyramid}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedHorizontalPyramid }

---

### SurfaceChart_Contour {#SurfaceChart_Contour}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Contour }

---

### SurfaceChart_WireframeContour {#SurfaceChart_WireframeContour}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.WireframeContour }

---

### SurfaceChart_Surface3D {#SurfaceChart_Surface3D}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Surface3D }

---

### SurfaceChart_WireframeSurface3D {#SurfaceChart_WireframeSurface3D}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.WireframeSurface3D }

---

### BubbleChart {#BubbleChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Bubble, ChartType.BubbleWith3D }

---

### HistogramChart {#HistogramChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Histogram }

---

### ParetoLineChart {#ParetoLineChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ParetoLine }

---

### BoxAndWhiskerChart {#BoxAndWhiskerChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.BoxAndWhisker }

---

### WaterfallChart {#WaterfallChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Waterfall }

---

### FunnelChart {#FunnelChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Funnel }

---

### TreemapChart {#TreemapChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Treemap }

---

### MapChart {#MapChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Map }

---

### SunburstChart {#SunburstChart}
Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Sunburst }

---