---
title: DataLabelCollection
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente une série détiquettes.
type: docs
weight: 1440
url: /fr/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection class

Représente une série d'étiquettes.

```csharp
public class DataLabelCollection : DomObject<ChartSeries>, IDataLabelCollection
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Chart](../../aspose.slides.charts/datalabelcollection/chart) { get; } | Renvoie le graphique parent. Lecture seule[`IChart`](../ichart) . |
| [Count](../../aspose.slides.charts/datalabelcollection/count) { get; } | Obtient le nombre de toutes les étiquettes de données dans la collection. Lecture seuleInt32 . |
| [CountOfVisibleDataLabels](../../aspose.slides.charts/datalabelcollection/countofvisibledatalabels) { get; } | Obtient le nombre d'étiquettes de données visibles dans la collection. Lecture seuleInt32 . |
| [DefaultDataLabelFormat](../../aspose.slides.charts/datalabelcollection/defaultdatalabelformat) { get; } | Obtient le format d'étiquette de données par défaut. Lecture seule[`IDataLabelFormat`](../idatalabelformat) . |
| [IsVisible](../../aspose.slides.charts/datalabelcollection/isvisible) { get; } | False signifie que l'étiquette de données n'est pas visible par défaut (et donc tous les indicateurs Show* (ShowValue, ...) de la propriété DefaultDataLabelFormat sont faux). Lecture seuleBoolean . |
| [Item](../../aspose.slides.charts/datalabelcollection/item) { get; } | Obtient l'étiquette de données pour le point de données avec l'index spécifié. |
| [ParentSeries](../../aspose.slides.charts/datalabelcollection/parentseries) { get; } | Obtient la série parente. Lecture seule[`IChartSeries`](../ichartseries) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [GetEnumerator](../../aspose.slides.charts/datalabelcollection/getenumerator)() | Renvoie un énumérateur qui parcourt la collection. |
| [Hide](../../aspose.slides.charts/datalabelcollection/hide)() | Faites en sorte que l'étiquette de données soit masquée par défaut en définissant tous les indicateurs Show* (ShowValue, ...) de la propriété DefaultDataLabelFormat sur l'état faux. IsVisible sera faux après cela. |
| [IndexOf](../../aspose.slides.charts/datalabelcollection/indexof)(IDataLabel) | Renvoie un index du DataLabel spécifié dans la collection. |

### Voir également

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [ChartSeries](../chartseries)
* interface [IDataLabelCollection](../idatalabelcollection)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
