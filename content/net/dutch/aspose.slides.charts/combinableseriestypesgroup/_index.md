---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes voor .NET API-referentie
description: Enumeratie van groepen van combineerbare serietypen. Elk element verwijst naar een groep van typen grafiekseries die gelijktijdig kunnen bestaan in één ChartSeriesGroup. Bijvoorbeeld kunnen ChartType.PercentsStackedArea series niet gelijktijdig met ChartType.StackedArea series in één ChartSeriesGroup bestaan. Maar twee of meer ChartType.PercentsStackedArea series kunnen wel tegelijkertijd in één ChartSeriesGroup staan, namelijk CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. En ChartType.Line series kunnen samen met ChartType.LineWithMarkers series gelijktijdig in één CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup staan.
type: docs
weight: 1530
url: /nl/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeratie

Enumeratie van groepen van combineerbare serietypen. Elk element verwijst naar een groep van typen grafiekseries die gelijktijdig kunnen bestaan in één ChartSeriesGroup. Bijvoorbeeld: ChartType.PercentsStackedArea series kunnen niet gelijktijdig met ChartType.StackedArea series in één ChartSeriesGroup bestaan. Maar twee of meer ChartType.PercentsStackedArea series kunnen wel tegelijkertijd in één ChartSeriesGroup staan (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). En ChartType.Line series kunnen samen met ChartType.LineWithMarkers series gelijktijdig in één CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup staan.

```csharp
public enum CombinableSeriesTypesGroup
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| AreaChart_Area | `4` | Groepeert deze set van serietypen: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Groepeert deze set van serietypen: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Groepeert deze set van serietypen: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Groepeert deze set van serietypen: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Groepeert deze set van serietypen: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Groepeert deze set van serietypen: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Groepeert deze set van serietypen: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Groepeert deze set van serietypen: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Groepeert deze set van serietypen: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Groepeert deze set van serietypen: { ChartType.Line3D } |
| StockHighLowClose | `18` | Groepeert deze set van serietypen: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Groepeert deze set van serietypen: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Groepeert deze set van serietypen: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Groepeert deze set van serietypen: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Groepeert deze set van serietypen: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Groepeert deze set van serietypen: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Groepeert deze set van serietypen: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Groepeert deze set van serietypen: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Groepeert deze set van serietypen: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Groepeert deze set van serietypen: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Groepeert deze set van serietypen: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Groepeert deze set van serietypen: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Groepeert deze set van serietypen: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Groepeert deze set van serietypen: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Groepeert deze set van serietypen: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Groepeert deze set van serietypen: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Groepeert deze set van serietypen: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Groepeert deze set van serietypen: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Groepeert deze set van serietypen: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Groepeert deze set van serietypen: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Groepeert deze set van serietypen: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Groepeert deze set van serietypen: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Groepeert deze set van serietypen: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Groepeert deze set van serietypen: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Groepeert deze set van serietypen: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Groepeert deze set van serietypen: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Groepeert deze set van serietypen: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Groepeert deze set van serietypen: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Groepeert deze set van serietypen: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Groepeert deze set van serietypen: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Groepeert deze set van serietypen: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Groepeert deze set van serietypen: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Groepeert deze set van serietypen: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Groepeert deze set van serietypen: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Groepeert deze set van serietypen: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Groepeert deze set van serietypen: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Groepeert deze set van serietypen: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Groepeert deze set van serietypen: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Groepeert deze set van serietypen: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Groepeert deze set van serietypen: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Groepeert deze set van serietypen: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Groepeert deze set van serietypen: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Groepeert deze set van serietypen: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Groepeert deze set van serietypen: { ChartType.Histogram } |
| ParetoLineChart | `54` | Groepeert deze set van serietypen: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Groepeert deze set van serietypen: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Groepeert deze set van serietypen: { ChartType.Waterfall } |
| FunnelChart | `57` | Groepeert deze set van serietypen: { ChartType.Funnel } |
| TreemapChart | `58` | Groepeert deze set van serietypen: { ChartType.Treemap } |
| MapChart | `59` | Groepeert deze set van serietypen: { ChartType.Map } |
| SunburstChart | `60` | Groepeert deze set van serietypen: { ChartType.Sunburst } |

### Zie ook

* naamruimte [Aspose.Slides.Charts](../../aspose.slides.charts)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->