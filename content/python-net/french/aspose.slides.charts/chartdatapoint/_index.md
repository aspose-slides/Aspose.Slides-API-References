---
title: ChartDataPoint class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint classe

Represents series data point.

The ChartDataPoint type exposes the following members:

## Propriétés

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Lecture seule [`IStringOrDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/size_value/) | Renvoie la valeur de taille du point de données du graphique.<br/>            Utilisé avec les graphiques Treemap et Sunburst. <br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/color_value/) | Renvoie la valeur de couleur du point de données du graphique.<br/>            Utilisé avec les graphiques Carte. <br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Représente les valeurs des barres d’erreur de série dans le cas du type de valeur Custom.<br/>            Lecture seule [`IErrorBarsCustomValues`](/slides/python-net/fr/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Lecture seule [`IDataLabel`](/slides/python-net/fr/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Spécifie que les bulles ont un effet 3-D appliqué.<br/>            Lecture/écriture **bool**. |
| [`explosion`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/explosion/) | Spécifie la quantité de déplacement du point de données depuis le centre du secteur.<br/>            Lecture/écriture **int**. |
| [`format`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/format/) | Représente les propriétés de formatage.<br/>            Lecture/écriture [`IFormat`](/slides/python-net/fr/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/marker/) | Spécifie un marqueur de données.<br/>            Lecture seule [`IMarker`](/slides/python-net/fr/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/set_as_total/) | Définit le point de données comme total. Appliqué uniquement pour le type de série Waterfall. |
| [`related_legend_entry`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Propriétés de l’entrée de légende correspondante dans le cas d’un type de graphique de cette liste :<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Lecture seule [`ILegendEntryProperties`](/slides/python-net/fr/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/data_point_levels/) | Renvoie le conteneur des niveaux de points de données. Appliqué pour les séries Treeamp et Sunburst.<br/>            L’indexation des niveaux de points de données commence à zéro. |
| [`index`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Spécifie que le point de données doit inverser ses couleurs si la valeur est négative.<br/>            Lecture/écriture **bool**. |
| [`actual_x`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/actual_x/) | Spécifie la position x réelle (gauche) de l’élément du graphique par rapport au coin supérieur gauche du graphique.<br/>            Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. <br/>            Lecture **float**. |
| [`actual_y`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/actual_y/) | Spécifie la position y réelle (haut) de l’élément du graphique par rapport au coin supérieur gauche du graphique.<br/>            Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. <br/>            Lecture **float**. |
| [`actual_width`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/actual_width/) | Spécifie la largeur réelle de l’élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. <br/>            Lecture **float**. |
| [`actual_height`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/actual_height/) | Spécifie la hauteur réelle de l’élément du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. <br/>            Lecture **float**. |

## Méthodes

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/remove/#) | Supprime le DataPoint de la série du graphique. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/fr/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Renvoie une couleur automatique du point de données basée sur l’index de série, l’index du point de données, la propriété ParentSeriesGroup.IsColorVaried et le style du graphique.<br/>            Cette couleur est utilisée par défaut si FillType est égal à NotDefined. |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)