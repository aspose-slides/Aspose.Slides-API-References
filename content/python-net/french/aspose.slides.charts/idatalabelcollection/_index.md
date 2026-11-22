---
title: IDataLabelCollection class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection classe

Représente les libellés d’une série.

Le type IDataLabelCollection expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | Retourne le format par défaut de tous les libellés de données de la collection.<br/>            Lecture seule [`IDataLabelFormat`](/slides/python-net/fr/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | Représente le format des lignes de repère des libellés de données.<br/>             Lecture seule [`IChartLinesFormat`](/slides/python-net/fr/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/is_visible/) | False signifie que le libellé de données n’est pas visible par défaut (et donc tous les indicateurs Show*- (ShowValue, …) de la propriété DefaultDataLabelFormat sont faux).<br/>            Lecture seule **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | Obtient le nombre de libellés de données visibles dans la collection.<br/>            Lecture seule **int**. |
| [`count`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/count/) | Obtient le nombre total de libellés de données dans la collection.<br/>            Lecture seule **int**. |
| [`parent_series`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/parent_series/) | Retourne la série du graphique parent.<br/>            Lecture seule [`IChartSeries`](/slides/python-net/fr/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/default_label_shape_type/) | Obtient ou définit le type de forme par défaut pour les libellés de données.<br/>             Retourne [`ShapeType.NOT_DEFINED`](/slides/python-net/fr/aspose.slides/shapetype/NOT_DEFINED) si aucune forme n’est définie. |
| [`chart`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/presentation/) |  |

Obtient le libellé de données pour le point de données avec l’index spécifié.

## Indexeur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/hide/#) | Masque le libellé de données par défaut en définissant toutes les options Show*- (ShowValue, …) de la propriété DefaultDataLabelFormat sur l’état faux.<br/>            IsVisible sera false après cela. |
| [`index_of(self, value)`](/slides/python-net/fr/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | Retourne l’index du DataLabel spécifié dans la collection. |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)