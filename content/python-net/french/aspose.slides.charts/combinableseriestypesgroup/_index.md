---
title: CombinableSeriesTypesGroup enumeration
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/combinableseriestypesgroup/
---
## CombinableSeriesTypesGroup énumération

Énumération des groupes de types de séries combinables.
            Chaque élément se rapporte à un groupe de types de séries de diagramme pouvant coexister simultanément dans un ChartSeriesGroup.
            Par exemple : les séries ChartType.PercentsStackedArea ne peuvent pas être simultanément avec les séries ChartType.StackedArea dans un ChartSeriesGroup.
            Cependant, deux séries ou plus de ChartType.PercentsStackedArea peuvent être dans un ChartSeriesGroup simultanément (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Et les séries ChartType.Line peuvent être avec les séries ChartType.LineWithMarkers simultanément dans un ChartSeriesGroup CombinableSeriesTypesGroup.LineChart_Line.

Le type CombinableSeriesTypesGroup expose les membres suivants :

## Champs

| Champ | Description |
| :- | :- |
| AREA_CHART_AREA | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Area } |
| AREA_CHART_PERCENTS_STACKED_AREA | Regroupe cet ensemble de types de séries :<br/>            { ChartType.PercentsStackedArea } |
| AREA_CHART_STACKED_AREA | Regroupe cet ensemble de types de séries :<br/>            { ChartType.StackedArea } |
| AREA_CHART_AREA_3D | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Area3D } |
| AREA_CHART_STACKED_AREA_3D | Regroupe cet ensemble de types de séries :<br/>            { ChartType.StackedArea3D } |
| AREA_CHART_PERCENTS_STACKED_AREA_3D | Regroupe cet ensemble de types de séries :<br/>            { ChartType.PercentsStackedArea3D } |
| LINE_CHART_LINE | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Line, ChartType.LineWithMarkers } |
| LINE_CHART_STACKED_LINE | Regroupe cet ensemble de types de séries :<br/>            { ChartType.StackedLine, ChartType.StackedLineWithMarkers } |
| LINE_CHART_PERCENTS_STACKED_LINE | Regroupe cet ensemble de types de séries :<br/>            { ChartType.PercentsStackedLine, ChartType.PercentsStackedLineWithMarkers } |
| LINE_3D_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Line3D } |
| STOCK_HIGH_LOW_CLOSE | Regroupe cet ensemble de types de séries :<br/>            { ChartType.HighLowClose } |
| STOCK_OPEN_HIGH_LOW_CLOSE | Regroupe cet ensemble de types de séries :<br/>            { ChartType.OpenHighLowClose } |
| STOCK_VOLUME_HIGH_LOW_CLOSE | Regroupe cet ensemble de types de séries :<br/>            { ChartType.VolumeHighLowClose } |
| STOCK_VOLUME_OPEN_HIGH_LOW_CLOSE | Regroupe cet ensemble de types de séries :<br/>            { ChartType.VolumeOpenHighLowClose } |
| RADAR_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Radar, ChartType.RadarWithMarkers } |
| FILLED_RADAR_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.FilledRadar } |
| SCATTER_STRAIGHT_MARKER | Regroupe cet ensemble de types de séries :<br/>            { ChartType.ScatterWithMarkers, ChartType.ScatterWithStraightLines, ChartType.ScatterWithStraightLinesAndMarkers } |
| SCATTER_SMOOTH_MARKER | Regroupe cet ensemble de types de séries :<br/>            { ChartType.ScatterWithSmoothLines, ChartType.ScatterWithSmoothLinesAndMarkers } |
| PIE_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Pie, ChartType.ExplodedPie } |
| PIE_3D_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Pie3D, ChartType.ExplodedPie3D } |
| DOUGHNUT_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Doughnut, ChartType.ExplodedDoughnut } |
| BAR_CHART_VERT_CLUSTERED | Regroupe cet ensemble de types de séries :<br/>            { ChartType.ClusteredColumn } |
| BAR_CHART_VERT_STACKED | Regroupe cet ensemble de types de séries :<br/>            { ChartType.StackedColumn } |
| BAR_CHART_VERT_PERCENTS_STACKED | Regroupe cet ensemble de types de séries :<br/>            { ChartType.PercentsStackedColumn } |
| BAR_CHART_HORIZ_CLUSTERED | Regroupe cet ensemble de types de séries :<br/>            { ChartType.ClusteredBar } |
| BAR_CHART_HORIZ_STACKED | Regroupe cet ensemble de types de séries :<br/>            { ChartType.StackedBar } |
| BAR_CHART_HORIZ_PERCENTS_STACKED | Regroupe cet ensemble de types de séries :<br/>            { ChartType.PercentsStackedBar } |
| BAR_3D_CHART_VERT | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Column3D, ChartType.Cylinder3D, ChartType.Cone3D, ChartType.Pyramid3D } |
| BAR_3D_CHART_VERT_CLUSTERED | Regroupe cet ensemble de types de séries :<br/>            { ChartType.ClusteredColumn3D, ChartType.ClusteredCone, ChartType.ClusteredCylinder, ChartType.ClusteredPyramid } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_COLUMN_3D | Regroupe cet ensemble de types de séries :<br/>            { ChartType.PercentsStackedColumn3D } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CONE | Regroupe cet ensemble de types de séries :<br/>            { ChartType.PercentsStackedCone } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_CYLINDER | Regroupe cet ensemble de types de séries :<br/>            { ChartType.PercentsStackedCylinder } |
| BAR_3D_CHART_VERT_PERCENTS_STACKED_PYRAMID | Regroupe cet ensemble de types de séries :<br/>            { ChartType.PercentsStackedPyramid } |
| BAR_3D_CHART_VERT_STACKED_COLUMN_3D | Regroupe cet ensemble de types de séries :<br/>            { ChartType.StackedColumn3D } |
| BAR_3D_CHART_VERT_STACKED_CONE | Regroupe cet ensemble de types de séries :<br/>            { ChartType.StackedCone } |
| BAR_3D_CHART_VERT_STACKED_CYLINDER | Regroupe cet ensemble de types de séries :<br/>            { ChartType.StackedCylinder } |
| BAR_3D_CHART_VERT_STACKED_PYRAMID | Regroupe cet ensemble de types de séries :<br/>            { ChartType.StackedPyramid } |
| BAR_3D_CHART_HORIZ_CLUSTERED | Regroupe cet ensemble de types de séries :<br/>            { ChartType.ClusteredBar3D, ChartType.ClusteredHorizontalCone, ChartType.ClusteredHorizontalCylinder, ChartType.ClusteredHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_STACKED_BAR_3D | Regroupe cet ensemble de types de séries :<br/>            { ChartType.StackedBar3D } |
| BAR_3D_CHART_HORIZ_STACKED_CONE | Regroupe cet ensemble de types de séries :<br/>            { ChartType.StackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_STACKED_CYLINDER | Regroupe cet ensemble de types de séries :<br/>            { ChartType.StackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_STACKED_PYRAMID | Regroupe cet ensemble de types de séries :<br/>            { ChartType.StackedHorizontalPyramid } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_BAR_3D | Regroupe cet ensemble de types de séries :<br/>            { ChartType.PercentsStackedBar3D } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CONE | Regroupe cet ensemble de types de séries :<br/>            { ChartType.PercentsStackedHorizontalCone } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_CYLINDER | Regroupe cet ensemble de types de séries :<br/>            { ChartType.PercentsStackedHorizontalCylinder } |
| BAR_3D_CHART_HORIZ_PERCENTS_STACKED_PYRAMID | Regroupe cet ensemble de types de séries :<br/>            { ChartType.PercentsStackedHorizontalPyramid } |
| BAR_OF_PIE_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.BarOfPie } |
| PIE_OF_PIE_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.PieOfPie } |
| SURFACE_CHART_CONTOUR | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Contour } |
| SURFACE_CHART_WIREFRAME_CONTOUR | Regroupe cet ensemble de types de séries :<br/>            { ChartType.WireframeContour } |
| SURFACE_CHART_SURFACE_3D | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Surface3D } |
| SURFACE_CHART_WIREFRAME_SURFACE_3D | Regroupe cet ensemble de types de séries :<br/>            { ChartType.WireframeSurface3D } |
| BUBBLE_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Bubble, ChartType.BubbleWith3D } |
| HISTOGRAM_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Histogram } |
| PARETO_LINE_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.ParetoLine } |
| BOX_AND_WHISKER_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.BoxAndWhisker } |
| WATERFALL_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Waterfall } |
| FUNNEL_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Funnel } |
| TREEMAP_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Treemap } |
| MAP_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Map } |
| SUNBURST_CHART | Regroupe cet ensemble de types de séries :<br/>            { ChartType.Sunburst } |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)