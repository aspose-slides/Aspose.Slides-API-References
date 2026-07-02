---
title: CombinableSeriesTypesGroup
second_title: Aspose.Sildes voor .NET API-referentie
description: Enumeratie van groepen van combineerbare serietypen. Elk element verwijst naar een groep van types van grafiekseries die gelijktijdig kunnen bestaan in één ChartSeriesGroup. Bijvoorbeeld kunnen ChartType.PercentsStackedArea series niet gelijktijdig met ChartType.StackedArea series bestaan in één ChartSeriesGroup. Maar twee of meer ChartType.PercentsStackedArea series kunnen wel gelijktijdig in één ChartSeriesGroup voorkomen CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. En ChartType.Line series kunnen samen met ChartType.LineWithMarkers series gelijktijdig in één CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
type: docs
weight: 1530
url: /nl/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeratie

Enumeratie van groepen van combineerbare serietypen. Elk element verwijst naar een groep van types van grafiekseries die gelijktijdig kunnen bestaan in één ChartSeriesGroup. Bijvoorbeeld: ChartType.PercentsStackedArea-series kunnen niet gelijktijdig met ChartType.StackedArea-series bestaan in één ChartSeriesGroup. Maar twee of meer ChartType.PercentsStackedArea-series kunnen wel gelijktijdig in één ChartSeriesGroup staan (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). En ChartType.Line-series kunnen gelijktijdig met ChartType.LineWithMarkers-series bestaan in één CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

```csharp
public enum CombinableSeriesTypesGroup
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| AreaChart_Area | `4` | Groepeert deze set serietypen: { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Groepeert deze set serietypen: { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Groepeert deze set serietypen: { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Groepeert deze set serietypen: { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Groepeert deze set serietypen: { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Groepeert deze set serietypen: { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Groepeert deze set serietypen: { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Groepeert deze set serietypen: { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Groepeert deze set serietypen: { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Groepeert deze set serietypen: { ChartType.Line3D } |
| StockHighLowClose | `18` | Groepeert deze set serietypen: { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Groepeert deze set serietypen: { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Groepeert deze set serietypen: { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Groepeert deze set serietypen: { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Groepeert deze set serietypen: { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Groepeert deze set serietypen: { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Groepeert deze set serietypen: { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Groepeert deze set serietypen: { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Groepeert deze set serietypen: { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Groepeert deze set serietypen: { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Groepeert deze set serietypen: { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Groepeert deze set serietypen: { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Groepeert deze set serietypen: { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Groepeert deze set serietypen: { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Groepeert deze set serietypen: { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Groepeert deze set serietypen: { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Groepeert deze set serietypen: { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Groepeert deze set serietypen: { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Groepeert deze set serietypen: { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Groepeert deze set serietypen: { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Groepeert deze set serietypen: { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Groepeert deze set serietypen: { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Groepeert deze set serietypen: { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Groepeert deze set serietypen: { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Groepeert deze set serietypen: { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Groepeert deze set serietypen: { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Groepeert deze set serietypen: { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Groepeert deze set serietypen: { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Groepeert deze set serietypen: { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Groepeert deze set serietypen: { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Groepeert deze set serietypen: { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Groepeert deze set serietypen: { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Groepeert deze set serietypen: { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Groepeert deze set serietypen: { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Groepeert deze set serietypen: { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Groepeert deze set serietypen: { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Groepeert deze set serietypen: { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Groepeert deze set serietypen: { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Groepeert deze set serietypen: { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Groepeert deze set serietypen: { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Groepeert deze set serietypen: { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Groepeert deze set serietypen: { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Groepeert deze set serietypen: { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Groepeert deze set serietypen: { ChartType.Histogram } |
| ParetoLineChart | `54` | Groepeert deze set serietypen: { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Groepeert deze set serietypen: { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Groepeert deze set serietypen: { ChartType.Waterfall } |
| FunnelChart | `57` | Groepeert deze set serietypen: { ChartType.Funnel } |
| TreemapChart | `58` | Groepeert deze set serietypen: { ChartType.Treemap } |
| MapChart | `59` | Groepeert deze set serietypen: { ChartType.Map } |
| SunburstChart | `60` | Groepeert deze set serietypen: { ChartType.Sunburst } |

### Zie ook

* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->