---
title: IChartCategory class
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.charts/ichartcategory/
---
## classe IChartCategory

Représente les catégories de graphique.

Le type IChartCategory expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/fr/aspose.slides.charts/ichartcategory/use_cell/) | Si vrai, la propriété AsCell est effective. En d'autres termes, la feuille de calcul est utilisée pour stocker la catégorie (ce cas prend en charge une catégorie à plusieurs niveaux).<br/>            Si faux, la propriété AsLiteral est effective. En d'autres termes, la feuille de calcul n'est PAS utilisée pour stocker la catégorie (et ce cas ne prend pas en charge des catégories à plusieurs niveaux).<br/>            Lecture seule **bool**. |
| [`as_cell`](/slides/python-net/fr/aspose.slides.charts/ichartcategory/as_cell/) | Renvoie ou définit l'objet IChartDataCell.<br/>            Si la catégorie est à plusieurs niveaux, alors l'objet IChartDataCell est utilisé pour le niveau "0".<br/>            Lecture/écriture [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/fr/aspose.slides.charts/ichartcategory/as_literal/) | Renvoie ou définit AsLiteral si UseCell est faux.<br/>            Lecture/écriture **any**. |
| [`value`](/slides/python-net/fr/aspose.slides.charts/ichartcategory/value/) | Si UseCell est vrai, alors cette propriété représente la propriété AsCell.Value.<br/>            Si UseCell est faux, alors cette propriété représente la propriété AsLiteral.<br/>            Lecture/écriture **any**. |
| [`grouping_levels`](/slides/python-net/fr/aspose.slides.charts/ichartcategory/grouping_levels/) | Conteneur géré des valeurs des niveaux de regroupement des catégories de graphique.<br/>            Une catégorie à plusieurs niveaux contient plus d'un niveau de regroupement.<br/>            L'indexation des niveaux de regroupement commence à zéro.<br/>            Lecture seule [`IChartCategoryLevelsManager`](/slides/python-net/fr/aspose.slides.charts/ichartcategorylevelsmanager). |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/fr/aspose.slides.charts/ichartcategory/remove/#) | Supprime la catégorie du graphique. |


### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)