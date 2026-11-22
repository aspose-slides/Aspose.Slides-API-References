---
title: ChartSeriesGroup class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup classe

Représente un groupe de séries.

Le type ChartSeriesGroup expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`type`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/type/) | Renvoie un type de ce groupe de séries.<br/>            Lecture seule [`CombinableSeriesTypesGroup`](/slides/python-net/fr/aspose.slides.charts/combinableseriestypesgroup). |
| [`plot_on_second_axis`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/plot_on_second_axis/) | Indique si les séries de ce groupe sont tracées sur l'axe secondaire.<br/>            Lecture seule **bool**. |
| [`series`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/series/) | Renvoie une collection de séries.<br/>            Lecture seule [`IChartSeriesReadonlyCollection`](/slides/python-net/fr/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/up_down_bars/) | Fournit l'accès aux barres haut/bas d'un graphique en Line- ou Stock-chart.<br/>            Lecture seule [`IUpDownBarsManager`](/slides/python-net/fr/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/gap_width/) | Obtient ou définit l'espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne.<br/>            La valeur doit être comprise entre 0 et 500.<br/>            Lecture/écriture **int**. |
| [`gap_depth`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/gap_depth/) | Obtient ou définit la distance entre les séries de données dans un graphique 3D, en pourcentage de la largeur du marqueur.<br/>            La valeur doit être comprise entre 0 et 500.<br/>            Lecture/écriture **int**. |
| [`first_slice_angle`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/first_slice_angle/) | Obtient ou définit l'angle de la première tranche de graphique en pie ou doughnut,<br/>            en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés).<br/>            Lecture/écriture **int**. |
| [`doughnut_hole_size`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/doughnut_hole_size/) | Spécifie la taille du trou dans un graphique doughnut (peut être entre 0 et 90 % de la taille de la zone de tracé).<br/>            Lecture/écriture **int**. |
| [`overlap`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/overlap/) | Spécifie le degré de chevauchement des barres et des colonnes sur les graphiques 2-D, en pourcentage (de -100 % à 100 %).<br/>            - -100 % : Espacement maximal (les barres sont entièrement séparées).<br/>            - 0 % : Les barres sont placées côte à côte sans chevauchement ni espacement.<br/>            - 100 % : Chevauchement maximal (les barres se chevauchent complètement).<br/>            Cette propriété est lecture/écriture **int**. |
| [`second_pie_size`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/second_pie_size/) | Spécifie la taille du deuxième pie ou de la deuxième barre d'un graphique pie-of-pie ou bar-of-pie, en pourcentage de la taille du premier pie (peut être entre 5 et 200 %).<br/>            Lecture/écriture **int**. |
| [`bubble_size_representation`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/bubble_size_representation/) | Spécifie comment les valeurs de taille des bulles sont représentées sur le graphique bubble.<br/>            Lecture/écriture [`BubbleSizeRepresentationType`](/slides/python-net/fr/aspose.slides.charts/bubblesizerepresentationtype). |
| [`pie_split_position`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/pie_split_position/) | Spécifie une valeur qui doit être utilisée pour déterminer quels points de données sont dans le deuxième pie ou la deuxième barre d'un graphique pie-of-pie ou bar-of-pie.<br/>            Utilisé conjointement avec la propriété PieSplitBy.<br/>            Lecture/écriture **float**. |
| [`pie_split_by`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/pie_split_by/) | Spécifie comment déterminer quels points de données sont dans le deuxième pie ou la deuxième barre d'un graphique pie-of-pie ou bar-of-pie.<br/>            Lecture/écriture [`PieSplitType`](/slides/python-net/fr/aspose.slides.charts/piesplittype). |
| [`is_color_varied`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/is_color_varied/) | Spécifie que chaque repère de données dans la série a une couleur différente.<br/>            Lecture/écriture **bool**. |
| [`has_series_lines`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/has_series_lines/) | Vrai si le graphique possède des lignes de séries. Appliqué aux graphiques stacked bar et OfPie.<br/>            Lecture/écriture **bool**. |
| [`hi_low_lines_format`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/hi_low_lines_format/) | Spécifie le format HiLowLines.<br/>            HiLowLines s'applique aux types de graphiques HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose. |
| [`bubble_size_scale`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/bubble_size_scale/) | Spécifie le facteur d'échelle pour le graphique bubble (peut être entre 0 et 300 % de la taille par défaut).<br/>            Lecture/écriture **int**. |
| [`pie_split_custom_points`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/pie_split_custom_points/) | Les informations de division personnalisées pour un graphique pie-of-pie ou bar-of-pie avec une division personnalisée.<br/>            Contient les points de données qui doivent être dessinés dans le deuxième pie ou la deuxième barre d'un tel graphique.<br/>            Lecture seule [`PieSplitCustomPointCollection`](/slides/python-net/fr/aspose.slides.charts/piesplitcustompointcollection). |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/chart/) | Renvoie le graphique parent.<br/>            Lecture seule [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/presentation/) |  |

Obtient l'élément à l'index spécifié.

## Indexeur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides.charts/chartseriesgroup/__getitem__/) |  |


### Remarques

1) Voir le résumé et les remarques de la classe ChartSeriesGroupCollection et de l'énumération CombinableSeriesTypesGroup.  
2) Le groupe de séries contient certaines propriétés de séries qui sont communes à chaque série du groupe (« series group properties »). « series group properties » dans la classe ChartSeriesGroup est lecture/écriture.  
Chaque « series group properties » peut avoir une projection en lecture seule dans la classe ChartSeries.


### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)