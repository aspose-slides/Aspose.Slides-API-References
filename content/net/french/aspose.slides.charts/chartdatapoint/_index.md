---
title: ChartDataPoint
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Représente un point de données de série.
type: docs
weight: 1250
url: /fr/aspose.slides.charts/chartdatapoint/
---

## Classe ChartDataPoint

Représente un point de données de série.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Spécifie la hauteur réelle de l'élément de graphique. Appelez la méthode IChart.ValidateChartLayout() avant d'obtenir les valeurs réelles. Lisez Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Spécifie la largeur réelle de l'élément de graphique. Appelez la méthode IChart.ValidateChartLayout() avant d'obtenir les valeurs réelles. Lisez Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Spécifie la position x réelle (gauche) de l'élément de graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant d'obtenir les valeurs réelles. Lisez Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Spécifie le haut réel de l'élément de graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant d'obtenir les valeurs réelles. Lisez Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Lecture seule [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Retourne la valeur de couleur du point de données du graphique. Utilisé avec des graphiques Map. Lecture seule [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Retourne le conteneur des niveaux de points de données. Appliqué pour les séries Treeamp et Sunburst. L'indexation des niveaux de points de données est basée sur zéro. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Représente les valeurs des barres d'erreur de la série en cas de type de valeur personnalisé. Lecture seule [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Spécifie le montant dont le point de données doit être déplacé du centre du graphique. Lecture/écriture Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Représente les propriétés de formatage. Lecture/écriture [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Spécifie que le point de données doit inverser ses couleurs si la valeur est négative. Lecture/écriture Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Spécifie que les bulles ont un effet 3D appliqué. Lecture/écriture Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Étiquette. Lecture seule [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Spécifie un marqueur de données. Lecture seule [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Propriétés de l'entrée de légende correspondante en cas de type de graphique de cette liste : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Lecture seule [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Définit le point de données comme total. Appliqué uniquement pour le type de série Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Retourne la valeur de taille du point de données du graphique. Utilisé avec les graphiques Treemap et Sunburst. Lecture seule [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Valeur. Lecture seule [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Lecture seule [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Lecture seule [`IDoubleChartValue`](../idoublechartvalue). |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Retourne une couleur automatique du point de données basée sur l'index de la série, l'index du point de données, la propriété ParentSeriesGroup.IsColorVaried et le style de graphique. Cette couleur est utilisée par défaut si FillType est égal à NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Supprime le DataPoint de la série de graphiques. |

### Voir aussi

* interface [IChartDataPoint](../ichartdatapoint)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->