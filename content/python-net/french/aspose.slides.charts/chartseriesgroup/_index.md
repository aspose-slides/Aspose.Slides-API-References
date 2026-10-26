---
title: ChartSeriesGroup class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartseriesgroup/
---
## Classe ChartSeriesGroup

Représente un groupe de séries.

Le type ChartSeriesGroup expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`type`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/type/) | Renvoie un type de ce groupe de séries.<br/>            Lecture seule [`CombinableSeriesTypesGroup`](/slides/python-net/fr/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Indique si les séries de ce groupe sont tracées sur un axe secondaire.<br/>            Lecture seule **bool**. |
| [`series`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/series/) | Renvoie une collection de séries.<br/>            Lecture seule [`IChartSeriesReadonlyCollection`](/slides/python-net/fr/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Fournit l'accès aux barres haut/bas des graphiques en ligne ou en cours.<br/>            Lecture seule [`IUpDownBarsManager`](/slides/python-net/fr/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/gap_width/) | Spécifie l'espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne.<br/>            Lecture/écriture **int**. |
| [`gap_depth`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/gap_depth/) | Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un graphique 3D.<br/>            Lecture/écriture **int**. |
| [`first_slice_angle`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Obtient ou définit l'angle de la première tranche de graphique à secteurs ou en anneau,<br/>            en degrés (dans le sens horaire depuis le haut, de 0 à 360 degrés).<br/>            Lecture/écriture **int**. |
| [`doughnut_hole_size`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Spécifie la taille du trou dans un graphique en anneau (peut être entre 0 et 90 pour cent de la taille de la zone de traçage).<br/>            Lecture/écriture **int**. |
| [`overlap`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/overlap/) | Spécifie le chevauchement des barres et des colonnes sur les graphiques 2-D, en pourcentage (de -100% à 100%).<br/>             - -100% : Espacement maximal (les barres sont complètement séparées).<br/>             - 0% : Les barres sont placées côte à côte sans chevauchement ni espacement.<br/>             - 100% : Chevauchement maximal (les barres se chevauchent complètement).<br/>             Cette propriété est Lecture/écriture **int**. |
| [`second_pie_size`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Spécifie la taille de la seconde part ou barre d'un graphique part-de-part ou barre-de-part, en pourcentage de la taille de la première part (peut être entre 5 et 200 pour cent).<br/>            Lecture/écriture **int**. |
| [`bubble_size_representation`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique en bulles.<br/>            Lecture/écriture [`BubbleSizeRepresentationType`](/slides/python-net/fr/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données se trouvent dans la seconde part ou barre d'un graphique part-de-part ou barre-de-part.<br/>            Utilisée conjointement avec la propriété PieSplitBy.<br/>            Lecture/écriture **float**. |
| [`pie_split_by`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Spécifie comment déterminer quels points de données se trouvent dans la seconde part ou barre d'un graphique part-de-part ou barre-de-part.<br/>            Lecture/écriture [`PieSplitType`](/slides/python-net/fr/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Spécifie que chaque marqueur de données dans la série a une couleur différente.<br/>            Lecture/écriture **bool**. |
| [`has_series_lines`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Vrai si le graphique possède des lignes de séries. Appliqué aux graphiques à barres empilées et OfPie.<br/>            Lecture/écriture **bool**. |
| [`hi_low_lines_format`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Spécifie le format HiLowLines.<br/>            HiLowLines appliqué avec les types de graphiques HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Spécifie le facteur d'échelle pour le graphique en bulles (peut être entre 0 et 300 pour cent de la taille par défaut).<br/>            Lecture/écriture **int**. |
| [`pie_split_custom_points`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Les informations de division personnalisée pour un graphique part-de-part ou barre-de-part avec une division personnalisée.<br/>            Contient les points de données qui doivent être dessinés dans la seconde part ou barre d'un graphique part-de-part ou barre-de-part.<br/>            Lecture seule [`PieSplitCustomPointCollection`](/slides/python-net/fr/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/chart/) | Renvoie le graphique parent.<br/>            Lecture seule [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Obtient l'élément à l'index spécifié.

## Accesseur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |

### Remarques

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup.  
2) Un groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« propriétés du groupe de séries »).  
« Propriétés du groupe de séries » dans la classe ChartSeriesGroup est Lecture/écriture.  
Chaque « propriété du groupe de séries » peut avoir une projection Lecture seule dans la classe ChartSeries.

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)