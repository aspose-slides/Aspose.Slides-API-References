---
title: ChartCategory
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente les catégories de graphique.
type: docs
weight: 1150
url: /fr/net/aspose.slides.charts/chartcategory/
---
## ChartCategory class

Représente les catégories de graphique.

```csharp
public class ChartCategory : IChartCategory
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AsCell](../../aspose.slides.charts/chartcategory/ascell) { get; set; } | Renvoie ou définit l'objet IChartDataCell. Si la catégorie est à plusieurs niveaux, utilisez alors l'objet IChartDataCell pour le niveau "0". Lecture/écriture[`IChartDataCell`](../ichartdatacell) . |
| [AsLiteral](../../aspose.slides.charts/chartcategory/asliteral) { get; set; } | Renvoie ou définit l'objet AsLiteral. Lecture/écritureObject . |
| [GroupingLevels](../../aspose.slides.charts/chartcategory/groupinglevels) { get; } | Conteneur géré des valeurs des niveaux de regroupement de la catégorie de graphique. La catégorie à plusieurs niveaux contient plus d'un niveau de regroupement. L'indexation des niveaux de regroupement est basée sur zéro. Lecture seule[`IChartCategoryLevelsManager`](../ichartcategorylevelsmanager) . |
| [UseCell](../../aspose.slides.charts/chartcategory/usecell) { get; } | Si vrai, la propriété AsCell est réelle. En d'autres termes, la feuille de calcul est utilisée pour la catégorie de stockage (ce cas prend en charge une catégorie à plusieurs niveaux). Si false, la propriété AsLiteral est réelle. En d'autres termes, la feuille de calcul n'est PAS utilisée pour stocker la catégorie (et ce cas ne prend pas en charge les catégories à plusieurs niveaux). Lecture seuleBoolean . |
| [Value](../../aspose.slides.charts/chartcategory/value) { get; set; } | Si UseCell est vrai alors cette propriété représente la propriété AsCell.Value. Si UseCell est faux alors cette propriété représente la propriété AsLiteral. Lecture/écritureObject . |

## Méthodes

| Nom | La description |
| --- | --- |
| [Remove](../../aspose.slides.charts/chartcategory/remove)() | Supprime la catégorie du graphique. |

### Voir également

* interface [IChartCategory](../ichartcategory)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->