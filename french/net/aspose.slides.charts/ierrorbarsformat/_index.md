---
title: IErrorBarsFormat
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente les barres derreur des séries de graphiques. Les valeurs personnalisées ErrorBars sont dans IChartDataPointCollection dansErrorBarsCustomValues./ichartdatapoint/errorbarscustomvalues propriété.
type: docs
weight: 1970
url: /fr/net/aspose.slides.charts/ierrorbarsformat/
---
## IErrorBarsFormat interface

Représente les barres d'erreur des séries de graphiques. Les valeurs personnalisées ErrorBars sont dans IChartDataPointCollection (dans[`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) propriété).

```csharp
public interface IErrorBarsFormat : IChartComponent
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ierrorbarsformat/asichartcomponent) { get; } | Renvoie l'interface IChartComponent. Lecture seule[`IChartComponent`](../ichartcomponent) . |
| [Format](../../aspose.slides.charts/ierrorbarsformat/format) { get; set; } | Représente le format des barres d'erreur. Lecture/écriture[`IFormat`](../iformat) . |
| [HasEndCap](../../aspose.slides.charts/ierrorbarsformat/hasendcap) { get; set; } | Spécifie qu'un capuchon de fin n'est pas dessiné sur les barres d'erreur. Lecture/écritureBoolean . |
| [IsVisible](../../aspose.slides.charts/ierrorbarsformat/isvisible) { get; set; } | Obtient ou définit la visibilité des barres d'erreur. Lecture/écritureBoolean . |
| [Type](../../aspose.slides.charts/ierrorbarsformat/type) { get; set; } | Obtient ou définit le type de barres d'erreur. Lecture/écriture[`ErrorBarType`](../errorbartype) . |
| [Value](../../aspose.slides.charts/ierrorbarsformat/value) { get; set; } | Obtient ou définit la valeur qui est utilisée avec les types de valeur Fixed, Percentage et StandardDeviation pour déterminer la longueur des barres d'erreur. Lecture/écritureSingle . |
| [ValueType](../../aspose.slides.charts/ierrorbarsformat/valuetype) { get; set; } | Représente les manières possibles de déterminer la longueur des barres d'erreur. En cas de type de valeur personnalisé pour spécifier l'utilisation de la valeur[`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) propriété d'un point de données spécifique dans la collection de séries DataPoints. Lecture/écriture[`ErrorBarValueType`](../errorbarvaluetype) . |

### Voir également

* interface [IChartComponent](../ichartcomponent)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->