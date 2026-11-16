---
title: IChartDataPoint
second_title: Aspose.Sildes pour .NET Référence API
description: Représente un point de données de série.
type: docs
weight: 1840
url: /fr/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint interface

Représente un point de données de série.

```csharp
public interface IChartDataPoint : IActualLayout
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | Renvoie l'interface IActualLayout. |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | Obtient la taille de bulle d'un point de données de graphique. Lecture seule [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/ichartdatapoint/cachedbubblesize) { get; } | Obtient la taille de bulle en cache d'un point de données de graphique. Lecture seule [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/ichartdatapoint/cachedvalue) { get; } | Obtient la valeur en cache d'un point de données de graphique. Lecture seule [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/ichartdatapoint/cachedxvalue) { get; } | Obtient la valeur X en cache d'un point de données de graphique. Lecture seule [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/ichartdatapoint/cachedyvalue) { get; } | Obtient la valeur Y en cache d'un point de données de graphique. Lecture seule [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | Obtient la valeur couleur d'un point de données de graphique. Utilisé avec les graphiques cartographiques. Lecture seule [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | Renvoie le conteneur des niveaux de points de données. Appliqué aux séries Treeamp et Sunburst. L'indexation des niveaux de points de données commence à zéro. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | Représente les valeurs des barres d'erreur de la série dans le cas d'un type de valeur Custom. Lecture seule [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | Spécifie la quantité de déplacement du point de données depuis le centre du secteur. Lecture/écriture Int32. |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | Représente les propriétés de mise en forme. Lecture/écriture [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | Détermine à quelle collection d'enfants du parent ce point de données s'applique. Lecture UInt32. |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | Spécifie que le point de données doit inverser ses couleurs si la valeur est négative. Lecture/écriture Boolean. |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | Spécifie que les bulles ont un effet 3D appliqué. Lecture/écriture Boolean. |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | Représente le libellé du point de données du graphique. Lecture seule [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | Spécifie un marqueur de données. Lecture seule [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | Propriétés de l'entrée de légende correspondante dans le cas d'un type de graphique parmi cette liste : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Lecture seule [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | Définit le point de données comme total. Appliqué uniquement au type de série Waterfall. |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | Obtient la valeur de taille d'un point de données de graphique. Utilisé avec les graphiques Treemap et Sunburst. Lecture seule [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | Obtient la valeur d'un point de données de graphique. Lecture seule [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | Obtient la valeur x d'un point de données de graphique. Lecture seule [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | Obtient la valeur y d'un point de données de graphique. Lecture seule [`IDoubleChartValue`](../idoublechartvalue). |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | Renvoie une couleur automatique d'un point de données basée sur l'indice de série, l'indice du point de données, la propriété ParentSeriesGroup.IsColorVaried et le style de graphique. Cette couleur est utilisée par défaut si FillType vaut NotDefined. |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | Supprime le DataPoint de la série du graphique. |

### Voir aussi

* interface [IActualLayout](../iactuallayout)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->