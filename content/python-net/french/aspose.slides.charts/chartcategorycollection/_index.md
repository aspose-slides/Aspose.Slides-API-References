---
title: ChartCategoryCollection class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection classe

Représente la collection de [`ChartCategory`](/slides/python-net/fr/aspose.slides.charts/chartcategory)

Le type ChartCategoryCollection expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`use_cells`](/slides/python-net/fr/aspose.slides.charts/chartcategorycollection/use_cells/) | Si vrai alors la feuille de calcul est utilisée pour stocker les catégories (ce cas prend en charge des catégories à plusieurs niveaux).<br/>            Si faux alors la feuille de calcul N'EST PAS utilisée pour stocker les valeurs (et ce cas ne prend pas en charge des <br/>            catégories à plusieurs niveaux).<br/>            Lecture/écriture **bool**. |
| [`grouping_level_count`](/slides/python-net/fr/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | Renvoie le nombre de niveaux de regroupement de catégories utilisés.<br/>            Est supérieur à un pour les catégories à plusieurs niveaux.<br/>            Lecture seule **int**. |

Obtient l'élément à l'index spécifié.

## Indexeur

| Nom | Description |
| :- | :- |
| [`[index]`](/slides/python-net/fr/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/fr/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | Si la catégorie existe dans la collection, la renvoie. Sinon crée une nouvelle catégorie de graphique à partir de <br/>            [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell) et l'ajoute à la collection. |
| [`add(self, value)`](/slides/python-net/fr/aspose.slides.charts/chartcategorycollection/add/#any) | Crée un nouveau [`ChartCategory`](/slides/python-net/fr/aspose.slides.charts/chartcategory) à partir de la valeur et l'ajoute à la collection. |
| [`index_of(self, value)`](/slides/python-net/fr/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | Recherche le [`ChartCategory`](/slides/python-net/fr/aspose.slides.charts/chartcategory) spécifié et renvoie l'index de base zéro de la première occurrence dans l'ensemble de la Collection. |
| [`remove(self, value)`](/slides/python-net/fr/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | Supprime la valeur spécifiée. |
| [`remove_at(self, index)`](/slides/python-net/fr/aspose.slides.charts/chartcategorycollection/remove_at/#int) | Supprime l'élément à l'index donné. |
| [`clear(self)`](/slides/python-net/fr/aspose.slides.charts/chartcategorycollection/clear/#) | Supprime tous les éléments de la collection. |

### Voir aussi
* classe [`ChartCategory`](/slides/python-net/fr/aspose.slides.charts/chartcategory)
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)