---
title: ChartCategoryCollection
second_title: Aspose.Sildes pour .NET Référence API
description: Représente une collection de ChartCategory./chartcategory
type: docs
weight: 1200
url: /fr/aspose.slides.charts/chartcategorycollection/
---

## Classe ChartCategoryCollection

Représente une collection de [`ChartCategory`](../chartcategory)

```csharp
public class ChartCategoryCollection : DomObject<ChartData>, IChartCategoryCollection
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Count](../../aspose.slides.charts/chartcategorycollection/count) { get; } | Retourne le nombre d'éléments dans la collection. Lecture seule Int32. |
| [GroupingLevelCount](../../aspose.slides.charts/chartcategorycollection/groupinglevelcount) { get; } | Retourne le nombre de niveaux de regroupement des catégories utilisés. Est supérieur à un pour les catégories multilevel. Lecture seule Int32. |
| [IsSynchronized](../../aspose.slides.charts/chartcategorycollection/issynchronized) { get; } | Retourne une valeur indiquant si l'accès à la liste est synchronisé (sécurisé pour les threads). Lecture seule Boolean. |
| [Item](../../aspose.slides.charts/chartcategorycollection/item) { get; } | Obtient l'élément à l'index spécifié. |
| [SyncRoot](../../aspose.slides.charts/chartcategorycollection/syncroot) { get; } | Retourne un objet qui peut être utilisé pour synchroniser l'accès à la collection. Lecture seule Object. |
| [UseCells](../../aspose.slides.charts/chartcategorycollection/usecells) { get; set; } | Si vrai, alors la feuille de calcul est utilisée pour stocker les catégories (ce cas prend en charge les catégories multilevel). Si faux, alors la feuille de calcul n'est PAS utilisée pour stocker les valeurs (et ce cas ne prend pas en charge les catégories multilevel). Lecture/écriture Boolean. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.slides.charts/chartcategorycollection/add#add)(IChartDataCell) | Si la catégorie existe dans la collection, la retourne. Sinon, crée une nouvelle catégorie de graphique à partir de [`IChartDataCell`](../ichartdatacell) et l'ajoute à la collection. |
| [Add](../../aspose.slides.charts/chartcategorycollection/add#add_1)(object) | Crée une nouvelle [`ChartCategory`](../chartcategory) à partir de la valeur et l'ajoute à la collection. |
| [Clear](../../aspose.slides.charts/chartcategorycollection/clear)() | Supprime tous les éléments de la collection. |
| [CopyTo](../../aspose.slides.charts/chartcategorycollection/copyto)(Array, int) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [GetEnumerator](../../aspose.slides.charts/chartcategorycollection/getenumerator)() | Retourne un énumérateur qui itère à travers la collection. |
| [IndexOf](../../aspose.slides.charts/chartcategorycollection/indexof)(IChartCategory) | Recherche la [`ChartCategory`](../chartcategory) spécifiée et retourne l'index basé sur zéro de la première occurrence dans l'ensemble de la collection. |
| [Remove](../../aspose.slides.charts/chartcategorycollection/remove)(IChartCategory) | Supprime la valeur spécifiée. |
| [RemoveAt](../../aspose.slides.charts/chartcategorycollection/removeat)(int) | Supprime l'élément à l'index donné. |

### Voir aussi

* classe [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* classe [ChartData](../chartdata)
* interface [IChartCategoryCollection](../ichartcategorycollection)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->