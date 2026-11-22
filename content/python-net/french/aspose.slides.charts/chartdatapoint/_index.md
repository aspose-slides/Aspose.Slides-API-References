---
title: ChartDataPoint class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint classe

Représente un point de données de série.

Le type ChartDataPoint expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`x_value`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Lecture seule [`IStringOrDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/size_value/) | Renvoie la valeur de taille du point de données du graphique.<br/>            Utilisé avec les graphiques Treemap et Sunburst.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/color_value/) | Renvoie la valeur de couleur du point de données du graphique.<br/>            Utilisé avec les graphiques Map.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Represents series error bars values in case of Custom value type.<br/>            Lecture seule [`IErrorBarsCustomValues`](/slides/python-net/fr/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Lecture seule [`IDataLabel`](/slides/python-net/fr/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Specifies that the bubbles have a 3-D effect applied to them.<br/>            Lecture/écriture **bool**. |
| [`explosion`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/explosion/) | Specifies the amount the data point shall be moved from the center of the pie.<br/>            Lecture/écriture **int**. |
| [`format`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/format/) | Represents the formatting properties.<br/>            Lecture/écriture [`IFormat`](/slides/python-net/fr/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/marker/) | Specifies a data marker.<br/>            Lecture seule [`IMarker`](/slides/python-net/fr/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/set_as_total/) | Sets data point as total. Applied for Waterfall series type only. |
| [`related_legend_entry`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Propriétés de l’entrée de légende correspondante dans le cas d’un type de graphique de cette liste :<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Lecture seule [`ILegendEntryProperties`](/slides/python-net/fr/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/data_point_levels/) | Renvoie le conteneur des niveaux du point de données. Appliqué aux séries Treeamp et Sunburst.<br/>            L’indexation des niveaux du point de données commence à zéro. |
| [`index`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Specifies the data point shall invert its colors if the value is negative.<br/>            Lecture/écriture **bool**. |
| [`cached_value`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/cached_value/) | Gets the cached value of a chart data point.<br/>            Lecture seule [`ICachedChartValue`](/slides/python-net/fr/aspose.slides.charts/icachedchartvalue). |
| [`cached_x_value`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/cached_x_value/) | Gets the cached X value of a chart data point.<br/>            Lecture seule [`ICachedChartValue`](/slides/python-net/fr/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/cached_y_value/) | Gets the cached Y value of a chart data point.<br/>            Lecture seule [`ICachedChartValue`](/slides/python-net/fr/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/cached_bubble_size/) | Gets the cached bubble size of a chart data point.<br/>            Lecture seule [`ICachedChartValue`](/slides/python-net/fr/aspose.slides.charts/icachedchartvalue). |
| [`actual_x`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/actual_x/) | Specifies actual x location (left) of the chart element relative to the left top corner of the chart.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Lecture **float**. |
| [`actual_y`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/actual_y/) | Specifies actual top of the chart element relative to the left top corner of the chart.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Lecture **float**. |
| [`actual_width`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/actual_width/) | Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Lecture **float**. |
| [`actual_height`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/actual_height/) | Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Lecture **float**. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/remove/#) | Supprime le DataPoint de la série du graphique. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Renvoie une couleur automatique du point de données basée sur l’indice de série, l’indice du point de données, la propriété ParentSeriesGroup.IsColorVaried et le style du graphique.<br/>            Cette couleur est utilisée par défaut si FillType vaut NotDefined. |


### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)