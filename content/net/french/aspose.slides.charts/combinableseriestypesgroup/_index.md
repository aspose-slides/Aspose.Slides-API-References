---
title: CombinableSeriesTypesGroup
second_title: Référence de l'API Aspose.Slides pour .NET
description: Énumération de groupes de types de séries combinables. Chaque élément se rapporte à un groupe de types de séries de graphiques qui peuvent persister simultanément dans un ChartSeriesGroup. Par exemple  la série ChartType.PercentsStackedArea ne peut pas être simultanément avec la série ChartType.StackedArea dans un ChartSeriesGroup. Mais deux ou plusieurs ChartType.PercentsStackedArea peuvent être dans un ChartSeriesGroup simultanément CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea. Et la série ChartType.Line peut être avec la série ChartType.LineWithMarkers simultanément dans un CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.
type: docs
weight: 1410
url: /fr/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup enumeration

Énumération de groupes de types de séries combinables. Chaque élément se rapporte à un groupe de types de séries de graphiques qui peuvent persister simultanément dans un ChartSeriesGroup. Par exemple : la série ChartType.PercentsStackedArea ne peut pas être simultanément avec la série ChartType.StackedArea dans un ChartSeriesGroup. Mais deux ou plusieurs ChartType.PercentsStackedArea peuvent être dans un ChartSeriesGroup simultanément (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Et la série ChartType.Line peut être avec la série ChartType.LineWithMarkers simultanément dans un CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup.

```csharp
public enum CombinableSeriesTypesGroup
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| AreaChart_Area | `4` | Regroupe cet ensemble de types de séries : { ChartType.Area } |
| AreaChart_PercentsStackedArea | `5` | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedArea } |
| AreaChart_StackedArea | `6` | Regroupe cet ensemble de types de séries : { ChartType.StackedArea } |
| AreaChart_Area3D | `24` | Regroupe cet ensemble de types de séries : { ChartType.Area3D } |
| AreaChart_StackedArea3D | `25` | Regroupe cet ensemble de types de séries : { ChartType.StackedArea3D } |
| AreaChart_PercentsStackedArea3D | `26` | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedArea3D } |
| LineChart_Line | `13` | Regroupe cet ensemble de types de séries : { ChartType.Line, ChartType.LineWithMarkers } |
| LineChart_StackedLine | `14` | Regroupe cet ensemble de types de séries : { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LineChart_PercentsStackedLine | `15` | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| Line3DChart | `27` | Regroupe cet ensemble de types de séries : { ChartType.Line3D } |
| StockHighLowClose | `18` | Regroupe cet ensemble de types de séries : { ChartType.HighLowClose } |
| StockOpenHighLowClose | `19` | Regroupe cet ensemble de types de séries : { ChartType.OpenHighLowClose } |
| StockVolumeHighLowClose | `20` | Regroupe cet ensemble de types de séries : { ChartType.VolumeHighLowClose } |
| StockVolumeOpenHighLowClose | `21` | Regroupe cet ensemble de types de séries : { ChartType.VolumeOpenHighLowClose } |
| RadarChart | `16` | Regroupe cet ensemble de types de séries : { ChartType.Radar, ChartType.RadarWithMarkers } |
| FilledRadarChart | `17` | Regroupe cet ensemble de types de séries : { ChartType.FilledRadar } |
| ScatterStraightMarker | `22` | Regroupe cet ensemble de types de séries : { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| ScatterSmoothMarker | `23` | Regroupe cet ensemble de types de séries : { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PieChart | `3` | Regroupe cet ensemble de types de séries : { ChartType.Pie, ChartType.ExplodedPie } |
| Pie3DChart | `28` | Regroupe cet ensemble de types de séries : { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DoughnutChart | `2` | Regroupe cet ensemble de types de séries : { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BarChart_VertClustered | `10` | Regroupe cet ensemble de types de séries : { ChartType.ClusteredColumn } |
| BarChart_VertStacked | `11` | Regroupe cet ensemble de types de séries : { ChartType.StackedColumn } |
| BarChart_VertPercentsStacked | `12` | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedColumn } |
| BarChart_HorizClustered | `7` | Regroupe cet ensemble de types de séries : { ChartType.ClusteredBar } |
| BarChart_HorizStacked | `8` | Regroupe cet ensemble de types de séries : { ChartType.StackedBar } |
| BarChart_HorizPercentsStacked | `9` | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedBar } |
| Bar3DChart_Vert | `29` | Regroupe cet ensemble de types de séries : { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| Bar3DChart_VertClustered | `30` | Regroupe cet ensemble de types de séries : { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| Bar3DChart_VertPercentsStackedColumn3D | `31` | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedColumn3D } |
| Bar3DChart_VertPercentsStackedCone | `32` | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedCone } |
| Bar3DChart_VertPercentsStackedCylinder | `33` | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedCylinder } |
| Bar3DChart_VertPercentsStackedPyramid | `34` | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedPyramid } |
| Bar3DChart_VertStackedColumn3D | `35` | Regroupe cet ensemble de types de séries : { ChartType.StackedColumn3D } |
| Bar3DChart_VertStackedCone | `36` | Regroupe cet ensemble de types de séries : { ChartType.StackedCone } |
| Bar3DChart_VertStackedCylinder | `37` | Regroupe cet ensemble de types de séries : { ChartType.StackedCylinder } |
| Bar3DChart_VertStackedPyramid | `38` | Regroupe cet ensemble de types de séries : { ChartType.StackedPyramid } |
| Bar3DChart_HorizClustered | `39` | Regroupe cet ensemble de types de séries : { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| Bar3DChart_HorizStackedBar3D | `40` | Regroupe cet ensemble de types de séries : { ChartType.StackedBar3D } |
| Bar3DChart_HorizStackedCone | `41` | Regroupe cet ensemble de types de séries : { ChartType.StackedHorizontalCone } |
| Bar3DChart_HorizStackedCylinder | `42` | Regroupe cet ensemble de types de séries : { ChartType.StackedHorizontalCylinder } |
| Bar3DChart_HorizStackedPyramid | `43` | Regroupe cet ensemble de types de séries : { ChartType.StackedHorizontalPyramid } |
| Bar3DChart_HorizPercentsStackedBar3D | `44` | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedBar3D } |
| Bar3DChart_HorizPercentsStackedCone | `45` | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedHorizontalCone } |
| Bar3DChart_HorizPercentsStackedCylinder | `46` | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedHorizontalCylinder } |
| Bar3DChart_HorizPercentsStackedPyramid | `47` | Regroupe cet ensemble de types de séries : { ChartType.PercentsStackedHorizontalPyramid } |
| BarOfPieChart | `0` | Regroupe cet ensemble de types de séries : { ChartType.BarOfPie } |
| PieOfPieChart | `1` | Regroupe cet ensemble de types de séries : { ChartType.PieOfPie } |
| SurfaceChart_Contour | `48` | Regroupe cet ensemble de types de séries : { ChartType.Contour } |
| SurfaceChart_WireframeContour | `49` | Regroupe cet ensemble de types de séries : { ChartType.WireframeContour } |
| SurfaceChart_Surface3D | `50` | Regroupe cet ensemble de types de séries : { ChartType.Surface3D } |
| SurfaceChart_WireframeSurface3D | `51` | Regroupe cet ensemble de types de séries : { ChartType.WireframeSurface3D } |
| BubbleChart | `52` | Regroupe cet ensemble de types de séries : { ChartType.Bubble, ChartType.BubbleWith3D } |
| HistogramChart | `53` | Regroupe cet ensemble de types de séries : { ChartType.Histogram } |
| ParetoLineChart | `54` | Regroupe cet ensemble de types de séries : { ChartType.ParetoLine } |
| BoxAndWhiskerChart | `55` | Regroupe cet ensemble de types de séries : { ChartType.BoxAndWhisker } |
| WaterfallChart | `56` | Regroupe cet ensemble de types de séries : { ChartType.Waterfall } |
| FunnelChart | `57` | Regroupe cet ensemble de types de séries : { ChartType.Funnel } |
| TreemapChart | `58` | Regroupe cet ensemble de types de séries : { ChartType.Treemap } |
| MapChart | `59` | Regroupe cet ensemble de types de séries : { ChartType.Map } |
| SunburstChart | `60` | Regroupe cet ensemble de types de séries : { ChartType.Sunburst } |

### Voir également

* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
