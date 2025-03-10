---
title: IChartCategoryCollection
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une collection deIChartCategory./ichartcategory
type: docs
weight: 1640
url: /fr/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection interface

Représente une collection de[`IChartCategory`](../ichartcategory)

```csharp
public interface IChartCategoryCollection : IGenericCollection<IChartCategory>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [GroupingLevelCount](../../aspose.slides.charts/ichartcategorycollection/groupinglevelcount) { get; } | Renvoie le nombre de niveaux de regroupement de catégories utilisés. Est supérieur à un pour les catégories à plusieurs niveaux. En lecture seuleInt32 . |
| [Item](../../aspose.slides.charts/ichartcategorycollection/item) { get; } | Obtient l'élément à l'index spécifié. |
| [UseCells](../../aspose.slides.charts/ichartcategorycollection/usecells) { get; set; } | Si true, la feuille de calcul est utilisée pour stocker les catégories (ce cas prend en charge les catégories à plusieurs niveaux). Si false, la feuille de calcul n'est PAS utilisée pour stocker les valeurs (et ce cas ne prend pas en charge les catégories à plusieurs niveaux). Lire /écrivezBoolean . |

## Méthodes

| Nom | La description |
| --- | --- |
| [Add](../../aspose.slides.charts/ichartcategorycollection/add#add)(IChartDataCell) | Si la catégorie existe dans la collection, renvoyez-la. Sinon crée une nouvelle catégorie de graphique à partir de [`IChartDataCell`](../ichartdatacell) et l'ajoute à la collection. |
| [Add](../../aspose.slides.charts/ichartcategorycollection/add#add_1)(object) | Crée un nouveau[`IChartCategory`](../ichartcategory) de la valeur et l'ajoute à la collection. |
| [Clear](../../aspose.slides.charts/ichartcategorycollection/clear)() | Supprime tous les éléments de la collection. |
| [IndexOf](../../aspose.slides.charts/ichartcategorycollection/indexof)(IChartCategory) | Recherche le spécifié[`IChartCategory`](../ichartcategory) et renvoie l'index de base zéro de la première occurrence dans toute la Collection |
| [Remove](../../aspose.slides.charts/ichartcategorycollection/remove)(IChartCategory) | Supprime la valeur spécifiée. |
| [RemoveAt](../../aspose.slides.charts/ichartcategorycollection/removeat)(int) | Supprime l'élément à l'index donné. |

### Voir également

* interface [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* interface [IChartCategory](../ichartcategory)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
