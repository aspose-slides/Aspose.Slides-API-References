---
title: ChartCategory class
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.charts/chartcategory/
---
## ChartCategory classe

Représente les catégories de graphique.

Le type ChartCategory expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/fr/aspose.slides.charts/chartcategory/use_cell/) | Si vrai alors la propriété AsCell est effective. En d'autres termes, worksheet est utilisé pour <br/>            stocker la catégorie (ce cas prend en charge une catégorie à plusieurs niveaux).<br/>            Si faux alors la propriété AsLiteral est effective. En d'autres termes, worksheet n'est PAS utilisé <br/>            pour stocker la catégorie (et ce cas ne prend pas en charge des catégories à plusieurs niveaux).<br/>            Lecture seule **bool**. |
| [`as_cell`](/slides/python-net/fr/aspose.slides.charts/chartcategory/as_cell/) | Renvoie ou définit l'objet IChartDataCell.<br/>            Si la catégorie est à plusieurs niveaux alors utilise l'objet IChartDataCell pour le niveau "0".<br/>            Lecture/écriture [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/fr/aspose.slides.charts/chartcategory/as_literal/) | Renvoie ou définit l'objet AsLiteral.<br/>            Lecture/écriture **any**. |
| [`value`](/slides/python-net/fr/aspose.slides.charts/chartcategory/value/) | Si UseCell est vrai alors cette propriété représente la propriété AsCell.Value.<br/>            Si UseCell est faux alors cette propriété représente la propriété AsLiteral.<br/>            Lecture/écriture **any**. |
| [`grouping_levels`](/slides/python-net/fr/aspose.slides.charts/chartcategory/grouping_levels/) | Conteneur géré des valeurs des niveaux de regroupement de la catégorie du graphique.<br/>            Une catégorie à plusieurs niveaux contient plus d'un niveau de regroupement.<br/>            L'indexation des niveaux de regroupement commence à zéro.<br/>            Lecture seule [`IChartCategoryLevelsManager`](/slides/python-net/fr/aspose.slides.charts/ichartcategorylevelsmanager). |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/fr/aspose.slides.charts/chartcategory/remove/#) | Supprime la catégorie du graphique. |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)