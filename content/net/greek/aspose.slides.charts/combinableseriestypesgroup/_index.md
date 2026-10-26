---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes για .NET Αναφορά API
description: Απαρίθμηση ομάδων συνδυάσιμων τύπων σειρών. Κάθε στοιχείο σχετίζεται με ομάδα τύπων σειρών διαγράμματος που μπορούν να υπάρχουν ταυτόχρονα σε ένα ChartSeriesGroup. Για παράδειγμα οι σειρές ChartType.PercentsStackedArea δεν μπορούν να είναι ταυτόχρονα με τις σειρές ChartType.StackedArea σε ένα ChartSeriesGroup. Αλλά δύο ή περισσότερες σειρές ChartType.PercentsStackedArea μπορούν να είναι σε ένα ChartSeriesGroup ταυτόχρονα CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. Και οι σειρές ChartType.Line μπορούν να είναι με τις σειρές ChartType.LineWithMarkers ταυτόχρονα σε ένα CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
type: docs
weight: 1530
url: /el/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup απαρίθμηση

Απαρίθμηση ομάδων συνδυάσιμων τύπων σειρών. Κάθε στοιχείο σχετίζεται με ομάδα τύπων σειρών διαγράμματος που μπορούν να συνυπάρχουν ταυτόχρονα σε ένα ChartSeriesGroup. Για παράδειγμα: η σειρά ChartType.PercentsStackedArea δεν μπορεί να είναι ταυτόχρονα με τη σειρά ChartType.StackedArea σε ένα ChartSeriesGroup. Ωστόσο δύο ή περισσότερες σειρές ChartType.PercentsStackedArea μπορούν να βρίσκονται ταυτόχρονα σε ένα ChartSeriesGroup (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Και οι σειρές ChartType.Line μπορούν να είναι με τις σειρές ChartType.LineWithMarkers ταυτόχρονα σε ένα CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

```csharp
public enum CombinableSeriesTypesGroup
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| AreaChart_Area | `4` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Line3D } |
| StockHighLowClose | `18` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Histogram } |
| ParetoLineChart | `54` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Waterfall } |
| FunnelChart | `57` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Funnel } |
| TreemapChart | `58` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Treemap } |
| MapChart | `59` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Map } |
| SunburstChart | `60` | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { ChartType.Sunburst } |

### Δείτε επίσης

* χώρο ονομάτων [Aspose.Slides.Charts](../../aspose.slides.charts)
* συστατικό [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->