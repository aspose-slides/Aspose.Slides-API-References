---
title: DataLabelCollection class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection classe

Représente les étiquettes d’une série.

Le type DataLabelCollection expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/chart/) | Renvoie le graphique parent.<br/>            Lecture seule [`IChart`](/slides/python-net/fr/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/is_visible/) | False signifie que l’étiquette de données n’est pas visible par défaut (et donc que tous les <br/>            drapeaux Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sont à false).<br/>            Lecture seule **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | Obtient le nombre d’étiquettes de données visibles dans la collection.<br/>            Lecture seule **int**. |
| [`count`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/count/) | Obtient le nombre total d’étiquettes de données dans la collection.<br/>            Lecture seule **int**. |
| [`default_data_label_format`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/default_data_label_format/) | Obtient le format d’étiquette de données par défaut.<br/>            Lecture seule [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/leader_lines_format/) | Représente le format des lignes de repère des étiquettes de données.<br/>             Lecture seule [`IChartLinesFormat`](/slides/python-net/fr/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/parent_series/) | Obtient la série parent.<br/>            Lecture seule [`IChartSeries`](/slides/python-net/fr/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/default_label_shape_type/) | Obtient ou définit le type de forme par défaut pour les étiquettes de données.<br/>             Renvoie [`ShapeType.NOT_DEFINED`](/slides/python-net/fr/aspose.slides/shapetype/NOT_DEFINED) si aucune forme n’est définie. |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/presentation/) |  |

Obtient l’étiquette de données pour le point de données avec l’index spécifié.

## Indexeur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/hide/#) | Masque l’étiquette de données par défaut en définissant tous les drapeaux Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat à l’état false.<br/>            IsVisible sera false après cela. |
| [`index_of(self, value)`](/slides/python-net/fr/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | Renvoie l’index du DataLabel spécifié dans la collection. |


### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)