---
title: IChartDataPoint class
second_title: Aspose.Slides pour Python via l'API .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint classe

Représente un point de données de série.

Le type IChartDataPoint expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`x_value`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/x_value/) | Obtient la valeur x d’un point de données de graphique.<br/>            Lecture seule [`IStringOrDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/y_value/) | Obtient la valeur y d’un point de données de graphique.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/bubble_size/) | Obtient la taille de la bulle d’un point de données de graphique.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/value/) | Obtient la valeur d’un point de données de graphique.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`cached_x_value`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/cached_x_value/) | Obtient la valeur X mise en cache d’un point de données de graphique.<br/>            Lecture seule [`ICachedChartValue`](/slides/python-net/fr/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/cached_y_value/) | Obtient la valeur Y mise en cache d’un point de données de graphique.<br/>            Lecture seule [`ICachedChartValue`](/slides/python-net/fr/aspose.slides.charts/icachedchartvalue). |
| [`cached_value`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/cached_value/) | Obtient la valeur mise en cache d’un point de données de graphique.<br/>            Lecture seule [`ICachedChartValue`](/slides/python-net/fr/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/cached_bubble_size/) | Obtient la taille de bulle mise en cache d’un point de données de graphique.<br/>            Lecture seule [`ICachedChartValue`](/slides/python-net/fr/aspose.slides.charts/icachedchartvalue). |
| [`size_value`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/size_value/) | Obtient la valeur de taille d’un point de données de graphique.<br/>            Utilisé avec les graphiques Treemap et Sunburst.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/color_value/) | Obtient la valeur de couleur d’un point de données de graphique.<br/>            Utilisé avec les graphiques Carte.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Représente les valeurs des barres d’erreur de série dans le cas d’un type de valeur Custom.<br/>            Lecture seule [`IErrorBarsCustomValues`](/slides/python-net/fr/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/label/) | Représente le libellé du point de données de graphique.<br/>            Lecture seule [`IDataLabel`](/slides/python-net/fr/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Indique que les bulles ont un effet 3-D appliqué.<br/>            Lecture/écriture **bool**. |
| [`explosion`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/explosion/) | Indique le montant de déplacement du point de données depuis le centre de la part.<br/>            Lecture/écriture **int**. |
| [`format`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/format/) | Représente les propriétés de formatage.<br/>            Lecture/écriture [`IFormat`](/slides/python-net/fr/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/marker/) | Indique un marqueur de données.<br/>            Lecture seule [`IMarker`](/slides/python-net/fr/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Propriétés de l’entrée de légende correspondante dans le cas de types de graphique de la liste suivante :<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Lecture seule [`ILegendEntryProperties`](/slides/python-net/fr/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/set_as_total/) | Définit le point de données comme total. Appliqué uniquement pour la série Waterfall. |
| [`invert_if_negative`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Indique que le point de données doit inverser ses couleurs si la valeur est négative.<br/>            Lecture/écriture **bool**. |
| [`data_point_levels`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Retourne le conteneur des niveaux de point de données.<br/>            Appliqué pour les séries Treeamp et Sunburst.<br/>            L’indexation des niveaux de point de données commence à zéro. |
| [`index`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/index/) | Détermine à quelle collection d’enfants du parent ce point de données s’applique.<br/>            Lecture **int**. |
| [`actual_x`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/remove/#) | Supprime le DataPoint de la série du graphique. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Retourne une couleur automatique du point de données basée sur l’index de la série, l’index du point de données, la propriété ParentSeriesGroup.IsColorVaried et le style du graphique.<br/>            Cette couleur est utilisée par défaut si FillType equals NotDefined. |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)