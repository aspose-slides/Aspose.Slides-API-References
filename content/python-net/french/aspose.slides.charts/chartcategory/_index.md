---
title: ChartCategory class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.charts/chartcategory/
---
## ChartCategory classe

Représente les catégories de diagramme.

Le type ChartCategory expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/fr/aspose.slides.charts/chartcategory/use_cell/) | Si true alors la propriété AsCell est effective. In other words, worksheet is used for <br/>            storing category (this case supports a multi-level category).<br/>            Si false alors la propriété AsLiteral est effective. In other words, worksheet is NOT used <br/>            for storing category (and this case doesn't support a multi-level categories).<br/>            Lecture seule **bool**. |
| [`as_cell`](/slides/python-net/fr/aspose.slides.charts/chartcategory/as_cell/) | Renvoie ou définit l'objet IChartDataCell.<br/>            Si la catégorie est à plusieurs niveaux alors l'objet IChartDataCell utilisé pour le niveau "0".<br/>            Lecture/écriture [`IChartDataCell`](/slides/python-net/fr/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/fr/aspose.slides.charts/chartcategory/as_literal/) | Renvoie ou définit l'objet AsLiteral.<br/>            Lecture/écriture **any**. |
| [`value`](/slides/python-net/fr/aspose.slides.charts/chartcategory/value/) | Si UseCell est true alors cette propriété représente la propriété AsCell.Value.<br/>            Si UseCell est false alors cette propriété représente la propriété AsLiteral.<br/>            Lecture/écriture **any**. |
| [`grouping_levels`](/slides/python-net/fr/aspose.slides.charts/chartcategory/grouping_levels/) | Conteneur géré des valeurs des niveaux de regroupement de la catégorie de diagramme.<br/>            Une catégorie à plusieurs niveaux contient plus d'un niveau de regroupement.<br/>            L'indexation des niveaux de regroupement commence à zéro.<br/>            Lecture seule [`IChartCategoryLevelsManager`](/slides/python-net/fr/aspose.slides.charts/ichartcategorylevelsmanager). |
| [`cached_value`](/slides/python-net/fr/aspose.slides.charts/chartcategory/cached_value/) | Obtient la valeur mise en cache d'une catégorie de diagramme.<br/>            Lecture seule [`ICachedChartValue`](/slides/python-net/fr/aspose.slides.charts/icachedchartvalue). |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/fr/aspose.slides.charts/chartcategory/remove/#) | Supprime la catégorie du diagramme. |

### Voir aussi
* module [`aspose.slides.charts`](/slides/python-net/fr/aspose.slides.charts)
* bibliothèque [`Aspose.Slides`](/slides/python-net)