---
title: IChartCategoryCollection class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection classe

Représente une collection de [`IChartCategory`](/slides/python-net/fr/aspose.slides.charts/ichartcategory)

Le type IChartCategoryCollection expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`use_cells`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection/use_cells/) | Si vrai alors la feuille de calcul est utilisée pour stocker les catégories (ce cas prend en charge des catégories à plusieurs niveaux).<br/>            Si faux alors la feuille de calcul N'EST PAS utilisée pour stocker les valeurs (et ce cas ne prend pas en charge des catégories à plusieurs niveaux).<br/>            Lecture/écriture **bool**. |
| [`grouping_level_count`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | Renvoie le nombre de niveaux de regroupement de catégories utilisés.<br/>            Est supérieur à un pour les catégories à plusieurs niveaux.<br/>            Lecture seule **int**. |

Obtient l'élément à l'index spécifié.

## Indexeur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | Si la catégorie existe dans la collection, la renvoie. Sinon crée une nouvelle catégorie de graphique à partir de <br/>            [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell) et l'ajoute à la collection. |
| [`add(self, value)`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection/add/#any) | Crée un nouveau [`IChartCategory`](/slides/python-net/fr/aspose.slides.charts/ichartcategory) à partir de la valeur et l'ajoute à la collection. |
| [`index_of(self, value)`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | Recherche le [`IChartCategory`](/slides/python-net/fr/aspose.slides.charts/ichartcategory) spécifié et renvoie l'index basé sur zéro de la première occurrence dans l'ensemble de la Collection |
| [`remove(self, value)`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | Supprime la valeur spécifiée. |
| [`remove_at(self, index)`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | Supprime l'élément à l'index donné. |
| [`clear(self)`](/slides/python-net/fr/aspose.slides.charts/ichartcategorycollection/clear/#) | Supprime tous les éléments de la collection. |


### Voir aussi
* classe [`IChartCategory`](/slides/python-net/fr/aspose.slides.charts/ichartcategory)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)