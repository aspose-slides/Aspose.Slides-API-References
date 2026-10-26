---
title: CombinableSeriesTypesGroup
second_title: Aspose.Slides για C++ API Αναφορά
description: "Απαρίθμηση των ομάδων των συνδυάσιμων τύπων σειρών. Κάθε στοιχείο σχετίζεται με μια ομάδα τύπων σειρών διαγράμματος που μπορούν να υπάρξουν ταυτόχρονα σε ένα ChartSeriesGroup. Για παράδειγμα: οι σειρές ChartType::PercentsStackedArea δεν μπορούν να είναι ταυτόχρονα με τις σειρές ChartType::StackedArea σε ένα ChartSeriesGroup. Αλλά δύο ή περισσότερες σειρές ChartType::PercentsStackedArea μπορούν να βρίσκονται σε ένα ChartSeriesGroup ταυτόχρονα (CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea). Και οι σειρές ChartType::Line μπορούν να είναι με τις σειρές ChartType::LineWithMarkers ταυτόχρονα σε ένα CombinableSeriesTypesGroup::LineChart_LineChartSeriesGroup."
type: docs
weight: 1496
url: /el/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enum

Απαρίθμηση των ομάδων των συνδυάσιμων τύπων σειρών. Κάθε στοιχείο σχετίζεται με μια ομάδα τύπων σειρών γραφήματος που μπορούν να υπάρξουν ταυτόχρονα σε ένα [ChartSeriesGroup](../chartseriesgroup/). Για παράδειγμα: Οι σειρές [ChartType::PercentsStackedArea](../charttype/) δεν μπορούν να βρίσκονται ταυτόχρονα με τις σειρές [ChartType::StackedArea](../charttype/) σε ένα [ChartSeriesGroup](../chartseriesgroup/). Αλλά δύο ή περισσότερες [ChartType::PercentsStackedArea](../charttype/) μπορούν να βρίσκονται σε ένα [ChartSeriesGroup](../chartseriesgroup/) ταυτόχρονα ([CombinableSeriesTypesGroup::AreaChart_PercentsStackedArea](./)). Και οι σειρές [ChartType::Line](../charttype/) μπορούν να είναι με τις σειρές [ChartType::LineWithMarkers](../charttype/) ταυτόχρονα σε ένα [CombinableSeriesTypesGroup::LineChart_Line](./)[ChartSeriesGroup](../chartseriesgroup/).

```cpp
enum class CombinableSeriesTypesGroup
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| AreaChart_Area | 4 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Area](../charttype/) } |
| AreaChart_PercentsStackedArea | 5 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::PercentsStackedArea](../charttype/) } |
| AreaChart_StackedArea | 6 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::StackedArea](../charttype/) } |
| AreaChart_Area3D | 24 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Area3D](../charttype/) } |
| AreaChart_StackedArea3D | 25 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::StackedArea3D](../charttype/) } |
| AreaChart_PercentsStackedArea3D | 26 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::PercentsStackedArea3D](../charttype/) } |
| LineChart_Line | 13 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Line](../charttype/), [ChartType::LineWithMarkers](../charttype/) } |
| LineChart_StackedLine | 14 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::StackedLine](../charttype/), [ChartType::StackedLineWithMarkers](../charttype/) } |
| LineChart_PercentsStackedLine | 15 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::PercentsStackedLine](../charttype/), [ChartType::PercentsStackedLineWithMarkers](../charttype/) } |
| Line3DChart | 27 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Line3D](../charttype/) } |
| StockHighLowClose | 18 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::HighLowClose](../charttype/) } |
| StockOpenHighLowClose | 19 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::OpenHighLowClose](../charttype/) } |
| StockVolumeHighLowClose | 20 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::VolumeHighLowClose](../charttype/) } |
| StockVolumeOpenHighLowClose | 21 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::VolumeOpenHighLowClose](../charttype/) } |
| RadarChart | 16 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Radar](../charttype/), [ChartType::RadarWithMarkers](../charttype/) } |
| FilledRadarChart | 17 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::FilledRadar](../charttype/) } |
| ScatterStraightMarker | 22 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::ScatterWithMarkers](../charttype/), [ChartType::ScatterWithStraightLines](../charttype/), [ChartType::ScatterWithStraightLinesAndMarkers](../charttype/) } |
| ScatterSmoothMarker | 23 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::ScatterWithSmoothLines](../charttype/), [ChartType::ScatterWithSmoothLinesAndMarkers](../charttype/) } |
| PieChart | 3 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Pie](../charttype/), [ChartType::ExplodedPie](../charttype/) } |
| Pie3DChart | 28 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Pie3D](../charttype/), [ChartType::ExplodedPie3D](../charttype/) } |
| DoughnutChart | 2 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Doughnut](../charttype/), [ChartType::ExplodedDoughnut](../charttype/) } |
| BarChart_VertClustered | 10 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::ClusteredColumn](../charttype/) } |
| BarChart_VertStacked | 11 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::StackedColumn](../charttype/) } |
| BarChart_VertPercentsStacked | 12 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::PercentsStackedColumn](../charttype/) } |
| BarChart_HorizClustered | 7 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::ClusteredBar](../charttype/) } |
| BarChart_HorizStacked | 8 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::StackedBar](../charttype/) } |
| BarChart_HorizPercentsStacked | 9 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::PercentsStackedBar](../charttype/) } |
| Bar3DChart_Vert | 29 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Column3D](../charttype/), [ChartType::Cylinder3D](../charttype/), [ChartType::Cone3D](../charttype/), [ChartType::Pyramid3D](../charttype/) } |
| Bar3DChart_VertClustered | 30 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::ClusteredColumn3D](../charttype/), [ChartType::ClusteredCone](../charttype/), [ChartType::ClusteredCylinder](../charttype/), [ChartType::ClusteredPyramid](../charttype/) } |
| Bar3DChart_VertPercentsStackedColumn3D | 31 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::PercentsStackedColumn3D](../charttype/) } |
| Bar3DChart_VertPercentsStackedCone | 32 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::PercentsStackedCone](../charttype/) } |
| Bar3DChart_VertPercentsStackedCylinder | 33 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::PercentsStackedCylinder](../charttype/) } |
| Bar3DChart_VertPercentsStackedPyramid | 34 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::PercentsStackedPyramid](../charttype/) } |
| Bar3DChart_VertStackedColumn3D | 35 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::StackedColumn3D](../charttype/) } |
| Bar3DChart_VertStackedCone | 36 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::StackedCone](../charttype/) } |
| Bar3DChart_VertStackedCylinder | 37 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::StackedCylinder](../charttype/) } |
| Bar3DChart_VertStackedPyramid | 38 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::StackedPyramid](../charttype/) } |
| Bar3DChart_HorizClustered | 39 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::ClusteredBar3D](../charttype/), [ChartType::ClusteredHorizontalCone](../charttype/), [ChartType::ClusteredHorizontalCylinder](../charttype/), [ChartType::ClusteredHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizStackedBar3D | 40 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::StackedBar3D](../charttype/) } |
| Bar3DChart_HorizStackedCone | 41 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::StackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizStackedCylinder | 42 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::StackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizStackedPyramid | 43 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::StackedHorizontalPyramid](../charttype/) } |
| Bar3DChart_HorizPercentsStackedBar3D | 44 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::PercentsStackedBar3D](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCone | 45 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::PercentsStackedHorizontalCone](../charttype/) } |
| Bar3DChart_HorizPercentsStackedCylinder | 46 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::PercentsStackedHorizontalCylinder](../charttype/) } |
| Bar3DChart_HorizPercentsStackedPyramid | 47 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::PercentsStackedHorizontalPyramid](../charttype/) } |
| BarOfPieChart | 0 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::BarOfPie](../charttype/) } |
| PieOfPieChart | 1 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::PieOfPie](../charttype/) } |
| SurfaceChart_Contour | 48 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Contour](../charttype/) } |
| SurfaceChart_WireframeContour | 49 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::WireframeContour](../charttype/) } |
| SurfaceChart_Surface3D | 50 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Surface3D](../charttype/) } |
| SurfaceChart_WireframeSurface3D | 51 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::WireframeSurface3D](../charttype/) } |
| BubbleChart | 52 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Bubble](../charttype/), [ChartType::BubbleWith3D](../charttype/) } |
| HistogramChart | 53 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Histogram](../charttype/) } |
| ParetoLineChart | 54 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::ParetoLine](../charttype/) } |
| BoxAndWhiskerChart | 55 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::BoxAndWhisker](../charttype/) } |
| WaterfallChart | 56 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Waterfall](../charttype/) } |
| FunnelChart | 57 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Funnel](../charttype/) } |
| TreemapChart | 58 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Treemap](../charttype/) } |
| MapChart | 59 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Map](../charttype/) } |
| SunburstChart | 60 | Ομαδοποιεί αυτό το σύνολο τύπων σειρών: { [ChartType::Sunburst](../charttype/) } |

## Δείτε επίσης

* Χώρος ονομάτων [Aspose::Slides::Charts](../)
* Βιβλιοθήκη [Aspose.Slides](../../)