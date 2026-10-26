---
title: IChartDataPoint class
second_title: Aspose.Slides pour Python via .NET Référence d'API
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
| [`x_value`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/x_value/) | Renvoie la valeur x du point de données du graphique.<br/>            Lecture seule [`IStringOrDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/y_value/) | Renvoie la valeur y du point de données du graphique.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/bubble_size/) | Renvoie la taille de la bulle du point de données du graphique.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/value/) | Renvoie la valeur du point de données du graphique.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/size_value/) | Renvoie la valeur de taille du point de données du graphique.<br/>            Utilisé avec les graphiques Treemap et Sunburst.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/color_value/) | Renvoie la valeur de couleur du point de données du graphique.<br/>            Utilisé avec les graphiques de carte.<br/>            Lecture seule [`IDoubleChartValue`](/slides/python-net/fr/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Représente les valeurs des barres d'erreur de série dans le cas du type de valeur Custom.<br/>            Lecture seule [`IErrorBarsCustomValues`](/slides/python-net/fr/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/label/) | Représente l'étiquette du point de données du graphique.<br/>            Lecture seule [`IDataLabel`](/slides/python-net/fr/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Spécifie que les bulles ont un effet 3 D appliqué.<br/>            Lecture/écriture **bool**. |
| [`explosion`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/explosion/) | Spécifie la distance que le point de données doit être déplacé du centre du secteur.<br/>            Lecture/écriture **int**. |
| [`format`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/format/) | Représente les propriétés de formatage.<br/>            Lecture/écriture [`IFormat`](/slides/python-net/fr/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/marker/) | Spécifie un marqueur de données.<br/>            Lecture seule [`IMarker`](/slides/python-net/fr/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Propriétés de l'entrée de légende correspondante dans le cas d'un type de graphique parmi cette liste :<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Lecture seule [`ILegendEntryProperties`](/slides/python-net/fr/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/set_as_total/) | Définit le point de données comme total. Appliqué uniquement pour le type de série Waterfall. |
| [`invert_if_negative`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Spécifie que le point de données doit inverser ses couleurs si la valeur est négative.<br/>            Lecture/écriture **bool**. |
| [`data_point_levels`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Renvoie le conteneur des niveaux du point de données. Appliqué aux séries Treeamp et Sunburst.<br/>            L'indexation des niveaux du point de données commence à zéro. |
| [`index`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/index/) | Détermine à quelle collection d'enfants du parent ce point de données s'applique.<br/>            Lecture **int**. |
| [`actual_x`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/remove/#) | Supprime le DataPoint de la série du graphique. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/fr/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Renvoie une couleur automatique du point de données basée sur l'index de la série, l'index du point de données, la propriété ParentSeriesGroup.IsColorVaried et le style du graphique.<br/>            Cette couleur est utilisée par défaut si FillType est égal à NotDefined. |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)