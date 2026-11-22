---
title: IChartCategory class
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.charts/ichartcategory/
---
## IChartCategory classe

Représente les catégories de graphique.

Le type IChartCategory expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/fr/aspose.slides.charts/ichartcategory/use_cell/) | Si true alors la propriété AsCell est effective. En d'autres termes, la feuille de calcul est utilisée pour <br/>            le stockage de la catégorie (ce cas prend en charge une catégorie à plusieurs niveaux).<br/>            Si false alors la propriété AsLiteral est effective. En d'autres termes, la feuille de calcul n'est PAS utilisée <br/>            pour le stockage de la catégorie (et ce cas ne prend pas en charge les catégories à plusieurs niveaux).<br/>            Lecture seule **bool**. |
| [`as_cell`](/slides/python-net/fr/aspose.slides.charts/ichartcategory/as_cell/) | Renvoie ou définit l'objet IChartDataCell.<br/>            Si la catégorie est à plusieurs niveaux alors l'objet IChartDataCell utilisé pour le niveau "0".<br/>            Lecture/écriture [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/fr/aspose.slides.charts/ichartcategory/as_literal/) | Renvoie ou définit AsLiteral si UseCell est false.<br/>            Lecture/écriture **any**. |
| [`value`](/slides/python-net/fr/aspose.slides.charts/ichartcategory/value/) | Si UseCell est true alors cette propriété représente la propriété AsCell.Value.<br/>            Si UseCell est false alors cette propriété représente la propriété AsLiteral.<br/>            Lecture/écriture **any**. |
| [`cached_value`](/slides/python-net/fr/aspose.slides.charts/ichartcategory/cached_value/) | Obtient la valeur mise en cache d'une catégorie de graphique.<br/>            Lecture seule [`ICachedChartValue`](/slides/python-net/fr/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/fr/aspose.slides.charts/ichartcategory/grouping_levels/) | Conteneur géré des valeurs des niveaux de regroupement de la catégorie de graphique.<br/>            Une catégorie à plusieurs niveaux contient plus d'un niveau de regroupement.<br/>            L'indexation des niveaux de regroupement démarre à zéro.<br/>            Lecture seule [`IChartCategoryLevelsManager`](/slides/python-net/fr/aspose.slides.charts/ichartcategorylevelsmanager). |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/fr/aspose.slides.charts/ichartcategory/remove/#) | Supprime la catégorie du graphique. |


### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)