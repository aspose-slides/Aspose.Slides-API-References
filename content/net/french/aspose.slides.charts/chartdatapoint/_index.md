---
title: ChartDataPoint
second_title: Référence API Aspose.Sildes pour .NET
description: Représente un point de données de série.
type: docs
weight: 1330
url: /fr/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint classe

Représente un point de données de série.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Spécifie la hauteur réelle de l'élément de graphique. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir les valeurs réelles. Lecture Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Spécifie la largeur réelle de l'élément de graphique. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir les valeurs réelles. Lecture Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Spécifie la position x (gauche) réelle de l'élément de graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir les valeurs réelles. Lecture Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Spécifie le haut réel de l'élément de graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir les valeurs réelles. Lecture Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Lecture seule [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Renvoie la valeur couleur du point de données du graphique. Utilisé avec les graphiques cartographiques. Lecture seule [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Renvoie le conteneur des niveaux du point de données. Appliqué aux séries Treeamp et Sunburst. L'indexation des niveaux de point de données commence à zéro. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Représente les valeurs des barres d'erreur de la série dans le cas d'un type de valeur Custom. Lecture seule [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Spécifie la quantité dont le point de données doit être déplacé depuis le centre du camembert. Lecture/écriture Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Représente les propriétés de mise en forme. Lecture/écriture [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Spécifie que le point de données doit inverser ses couleurs si la valeur est négative. Lecture/écriture Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Spécifie que les bulles ont un effet 3-D appliqué. Lecture/écriture Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Lecture seule [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Spécifie un marqueur de données. Lecture seule [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Propriétés de l'entrée de légende correspondante pour les types de graphique suivants : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Lecture seule [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Définit le point de données comme total. Appliqué uniquement au type de série Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Renvoie la valeur de taille du point de données du graphique. Utilisé avec les graphiques Treemap et Sunburst. Lecture seule [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Valeur. Lecture seule [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Lecture seule [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Lecture seule [`IDoubleChartValue`](../idoublechartvalue). |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Renvoie une couleur automatique du point de données basée sur l'index de la série, l'index du point de données, la propriété ParentSeriesGroup.IsColorVaried et le style du graphique. Cette couleur est utilisée par défaut si FillType vaut NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Supprime le DataPoint de la série du graphique. |

### Voir aussi

* interface [IChartDataPoint](../ichartdatapoint)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->