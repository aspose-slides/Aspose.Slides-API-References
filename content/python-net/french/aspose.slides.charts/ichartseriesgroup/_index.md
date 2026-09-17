---
title: IChartSeriesGroup class
second_title: Aspose.Slides pour Python via .NET Référence de l'API
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
| [`plot_on_second_axis`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/plot_on_second_axis/) | Indique si les séries de ce groupe sont tracées sur l'axe secondaire.<br/>            Lecture seule **bool**. |
| [`series`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/series/) | Renvoie une collection en lecture seule de séries de diagramme.<br/>            Lecture seule [`IChartSeriesReadonlyCollection`](/slides/python-net/fr/aspose.slides.charts/ichartseriesreadonlycollection). |
| [`up_down_bars`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/up_down_bars/) | Fournit l'accès aux barres haut/bas d'un diagramme en ligne ou en actions.<br/>            Lecture seule [`IUpDownBarsManager`](/slides/python-net/fr/aspose.slides.charts/iupdownbarsmanager). |
| [`gap_width`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/gap_width/) | Spécifie l'espace entre les groupes de barres ou de colonnes, en pourcentage de la largeur de la barre ou de la colonne.<br/>            Lecture/écriture **int**. |
| [`gap_depth`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/gap_depth/) | Renvoie ou définit la distance, en pourcentage de la largeur du marqueur, entre les séries de données dans un diagramme 3D.<br/>            Lecture/écriture **int**. |
| [`first_slice_angle`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/first_slice_angle/) | Obtient ou définit l'angle de la première tranche de diagramme circulaire ou en anneau, <br/>            en degrés (dans le sens des aiguilles d'une montre depuis le haut, de 0 à 360 degrés).<br/>            Lecture/écriture **int**. |
| [`is_color_varied`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/is_color_varied/) | Spécifie que chaque marqueur de données dans la série a une couleur différente.<br/>            Lecture/écriture **bool**. |
| [`has_series_lines`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/has_series_lines/) | Vrai si le diagramme possède des lignes de séries. Appliqué aux diagrammes à barres empilées et OfPie.<br/>            Lecture/écriture **bool**. |
| [`overlap`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/overlap/) | Spécifie le degré de chevauchement des barres et des colonnes sur les diagrammes 2D, en pourcentage (de -100 % à 100 %).<br/>             - -100 % : Espacement maximal (les barres sont complètement séparées).<br/>             - 0 % : Les barres sont placées côte à côte sans chevauchement ni espacement.<br/>             - 100 % : Chevauchement maximal (les barres se chevauchent totalement).<br/>             Cette propriété est lecture/écriture **int**. |
| [`second_pie_size`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/second_pie_size/) | Spécifie la taille du second cercle ou de la seconde barre d'un diagramme en cercle-dans-cercle ou <br/>            d'un diagramme barre-dans-cercle, en pourcentage de la taille du premier cercle (peut <br/>            être entre 5 et 200 %).<br/>            Lecture/écriture **int**. |
| [`pie_split_position`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/pie_split_position/) | Spécifie une valeur qui sera utilisée pour déterminer quels points de données <br/>            se trouvent dans le second cercle ou la seconde barre d'un diagramme en cercle-dans-cercle ou d'un diagramme barre-dans-cercle. <br/>            Est utilisée conjointement avec la propriété PieSplitBy.<br/>            Lecture/écriture **float**. |
| [`pie_split_by`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/pie_split_by/) | Spécifie comment déterminer quels points de données sont dans le second cercle ou la seconde barre <br/>            d'un diagramme en cercle-dans-cercle ou d'un diagramme barre-dans-cercle.<br/>            Lecture/écriture [`PieSplitType`](/slides/python-net/fr/aspose.slides.charts/piesplittype). |
| [`pie_split_custom_points`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/pie_split_custom_points/) | Les informations de découpage personnalisé pour un diagramme en cercle-dans-cercle ou barre-dans-cercle avec un découpage personnalisé.<br/>            Contient les points de données qui doivent être dessinés dans le second cercle ou la seconde barre d'un diagramme en cercle-dans-cercle ou <br/>            de barre-dans-cercle.<br/>            Lecture seule [`IPieSplitCustomPointCollection`](/slides/python-net/fr/aspose.slides.charts/ipiesplitcustompointcollection). |
| [`doughnut_hole_size`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/doughnut_hole_size/) | Spécifie la taille du trou dans un diagramme en anneau (peut être entre 10 et 90 % <br/>            de la taille de la zone de tracé).<br/>            Lecture/écriture **int**. |
| [`bubble_size_scale`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/bubble_size_scale/) | Spécifie le facteur d'échelle pour le diagramme à bulles (peut être <br/>            entre 0 et 300 % de la taille par défaut).<br/>            Lecture/écriture **int**. |
| [`hi_low_lines_format`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/hi_low_lines_format/) | Spécifie le format HiLowLines. <br/>            HiLowLines appliqué avec les types de diagrammes HiLowClose, OpenHiLowClose, VolumeHiLowClose et VolumeOpenHiLowClose. |
| [`bubble_size_representation`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/bubble_size_representation/) | Spécifie comment les valeurs de taille des bulles sont représentées sur le diagramme à bulles.<br/>            Lecture/écriture [`BubbleSizeRepresentationType`](/slides/python-net/fr/aspose.slides.charts/bubblesizerepresentationtype). |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/chart/) |  |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/presentation/) |  |

Récupère l'élément à l'index spécifié.

## Indexer

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides.charts/ichartseriesgroup/__getitem__/) |  |

### Remarques

1) Voir le résumé et les remarques pour la classe ChartSeriesGroupCollection et l'énumération CombinableSeriesTypesGroup.
            2) Un groupe de séries contient certaines propriétés de séries qui sont communes à 
            chaque série du groupe ("propriétés de groupe de séries").
            "Propriétés de groupe de séries" dans la classe ChartSeriesGroup est lecture/écriture.
            Chaque "propriété de groupe de séries" peut avoir une projection lecture seule dans la classe ChartSeries.

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)