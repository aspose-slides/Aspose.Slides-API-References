---
title: DataLabelCollection class
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection classe

Représente les libellés d'une série.

Le type DataLabelCollection expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/chart/) | Renvoie le graphique parent.<br/>            Lecture seule [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/is_visible/) | False signifie que le libellé de données n'est pas visible par défaut (et ainsi tous les <br/>            indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sont false).<br/>            Lecture seule **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | Obtient le nombre de libellés de données visibles dans la collection.<br/>            Lecture seule **int**. |
| [`count`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/count/) | Obtient le nombre de tous les libellés de données dans la collection.<br/>            Lecture seule **int**. |
| [`default_data_label_format`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/default_data_label_format/) | Obtient le format de libellé de données par défaut.<br/>            Lecture seule [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/leader_lines_format/) | Représente le format des lignes directrices des libellés de données.<br/>             Lecture seule [`IChartLinesFormat`](/slides/python-net/fr/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/parent_series/) | Obtient la série parente.<br/>            Lecture seule [`IChartSeries`](/slides/python-net/fr/aspose.slides.charts/ichartseries). |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/presentation/) |  |

Obtient le libellé de données pour le point de données avec l'index spécifié.

## Indexeur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/hide/#) | Rendre le libellé de données masqué par défaut en définissant tous les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat à l'état false.<br/>            IsVisible sera false après cela. |
| [`index_of(self, value)`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | Renvoie un indice du DataLabel spécifié dans la collection. |


### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)