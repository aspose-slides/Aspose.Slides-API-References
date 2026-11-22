---
title: IChartSeriesGroup class
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup classe

Représente un groupe de séries.

Le type IChartSeriesGroup expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`type`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/type/) | Renvoie un type de ce groupe de séries.<br/>            Lecture seule [`CombinableSeriesTypesGroup`](/slides/python-net/fr/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Indique si les séries de ce groupe sont tracées sur un axe secondaire.<br/>            Lecture seule **bool**. |
| [`series`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/series/) | Renvoie une collection en lecture seule de séries de graphique.<br/>            Lecture seule [`IChartSeriesReadonlyCollection`](/slides/python-net/fr/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Fournit l'accès aux barres haut/bas d'un graphique en ligne ou en actions.<br/>            Lecture seule [`IUpDownBarsManager`](/slides/python-net/fr/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/gap_width/) | Obtient ou définit l'espace entre les grappes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne.<br/>            La valeur doit être comprise entre 0 et 500.<br/>            Lecture/écriture **int**. |
| [`gap_depth`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Obtient ou définit la distance entre les séries de données dans un graphique 3D, en pourcentage de la largeur du marqueur.<br/>            La valeur doit être comprise entre 0 et 500.<br/>            Lecture/écriture **int**. |
| [`first_slice_angle`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Obtient ou définit l'angle de la première tranche de graphique en secteur ou en beignet,<br/>            en degrés (dans le sens horaire depuis le haut, de 0 à 360 degrés).<br/>            Lecture/écriture **int**. |
| [`is_color_varied`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Spécifie que chaque marqueur de données dans la série a une couleur différente.<br/>            Lecture/écriture **bool**. |
| [`has_series_lines`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Vrai si le graphique possède des lignes de série. Appliqué aux graphiques à barres empilées et OfPie.<br/>            Lecture/écriture **bool**. |
| [`overlap`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/overlap/) | Spécifie le degré de chevauchement des barres et colonnes sur les graphiques 2-D, en pourcentage (de -100% à 100%).<br/>             - -100%: Espacement maximal (les barres sont complètement séparées).<br/>             - 0%: Les barres sont placées côte à côte sans chevauchement ni espacement.<br/>             - 100%: Chevauchement maximal (les barres se chevauchent complètement).<br/>             Cette propriété est en lecture/écriture **int**. |
| [`second_pie_size`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Spécifie la taille du deuxième secteur ou barre d'un graphique secteur-dégré ou <br/>            d'un graphique barre-dégré, en pourcentage de la taille du premier secteur (peut <br/>            être entre 5 et 200 pourcents).<br/>            Lecture/écriture **int**. |
| [`pie_split_position`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Spécifie une valeur qui sera utilisée pour déterminer quels points de données <br/>            sont dans le deuxième secteur ou barre d'un graphique secteur-dégré ou barre-dégré. <br/>            Utilisé conjointement avec la propriété PieSplitBy.<br/>            Lecture/écriture **float**. |
| [`pie_split_by`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Spécifie comment déterminer quels points de données sont dans le deuxième secteur ou barre <br/>            d'un graphique secteur-dégré ou barre-dégré.<br/>            Lecture/écriture [`PieSplitType`](/slides/python-net/fr/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Les informations de division personnalisée pour un graphique secteur-dégré ou barre-dégré avec division personnalisée.<br/>            Contient les points de données qui doivent être dessinés dans le deuxième secteur ou barre d'un graphique secteur-dégré ou <br/>            barre-dégré.<br/>            Lecture seule [`IPieSplitCustomPointCollection`](/slides/python-net/fr/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Spécifie la taille du trou d'un graphique en beignet (peut être entre 10 et 90 pourcents <br/>            de la taille de la zone de tracé).<br/>            Lecture/écriture **int**. |
| [`bubble_size_scale`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Spécifie le facteur d'échelle pour le graphique à bulles (peut être <br/>            entre 0 et 300 pourcents de la taille par défaut).<br/>            Lecture/écriture **int**. |
| [`hi_low_lines_format`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Spécifie le format HiLowLines.<br/>            HiLowLines appliqué aux types de graphiques HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique à bulles.<br/>            Lecture/écriture [`BubbleSizeRepresentationType`](/slides/python-net/fr/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Obtient l'élément à l'index spécifié.

## Accesseur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |


### Remarques

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup.
2) Le groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« propriétés du groupe de séries »). « propriétés du groupe de séries » dans la classe ChartSeriesGroup sont en lecture/écriture. Chaque « propriétés du groupe de séries » peut avoir une projection en lecture seule dans la classe ChartSeries.

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)