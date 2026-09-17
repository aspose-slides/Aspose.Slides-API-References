---
title: IDataLabelCollection class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection classe

Représente des étiquettes de série.

Le type IDataLabelCollection expose les membres suivants :

## Propriétés

| Property | Description |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Renvoie le format par défaut de toutes les étiquettes de données dans la collection.<br/>            Lecture seule [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Représente le format des lignes directrices des étiquettes de données.<br/>            Lecture seule [`IChartLinesFormat`](/slides/python-net/fr/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/is_visible/) | False signifie que l'étiquette de données n'est pas visible par défaut (et donc tous les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sont false).<br/>            Lecture seule **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Obtient le nombre d'étiquettes de données visibles dans la collection.<br/>            Lecture seule **int**. |
| [`count`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/count/) | Obtient le nombre total d'étiquettes de données dans la collection.<br/>            Lecture seule **int**. |
| [`parent_series`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/parent_series/) | Renvoie la série de graphique parent.<br/>            Lecture seule [`IChartSeries`](/slides/python-net/fr/aspose.slides.charts/ichartseries). |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Obtient l'étiquette de données pour le point de données avec l'index spécifié.

## Indexeur

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Méthodes

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/hide/#) | Masquer l'étiquette de données par défaut en définissant tous les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat à l'état false.<br/>            IsVisible sera false après cela. |
| [`index_of(self, value)`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Renvoie un index du DataLabel spécifié dans la collection. |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)