---
title: ChartDataPoint
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente le point de données de la série.
type: docs
weight: 1210
url: /fr/net/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint class

Représente le point de données de la série.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Propriétés

| Nom | La description |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Spécifie la hauteur réelle de l'élément de graphique. Appelez la méthode IChart.ValidateChartLayout() avant d'obtenir les valeurs réelles. LireSingle . |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Spécifie la largeur réelle de l'élément de graphique. Appelez la méthode IChart.ValidateChartLayout() avant d'obtenir les valeurs réelles. LireSingle . |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Spécifie l'emplacement x réel (à gauche) de l'élément de graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant d'obtenir les valeurs réelles. LireSingle . |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Spécifie le haut réel de l'élément de graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant d'obtenir les valeurs réelles. LireSingle . |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Lecture seule[`IDoubleChartValue`](../idoublechartvalue) . |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Renvoie la valeur de couleur du point de données du graphique. Utilisé avec les graphiques Map. Lecture seule[`IDoubleChartValue`](../idoublechartvalue) . |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Renvoie le conteneur des niveaux de points de données. Appliqué pour les séries Treeamp et Sunburst. L'indexation des niveaux de points de données est basée sur zéro. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Représente les valeurs des barres d'erreur de série en cas de type de valeur personnalisée. Lecture seule[`IErrorBarsCustomValues`](../ierrorbarscustomvalues) . |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Spécifie la distance à laquelle le point de données doit être déplacé du centre du secteur. Lecture/écritureInt32 . |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Représente les propriétés de formatage. Lecture/écriture[`IFormat`](../iformat) . |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Spécifie que le point de données doit inverser ses couleurs si la valeur est négative. Lecture/écritureBoolean . |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Spécifie qu'un effet 3D est appliqué aux bulles. Lecture/écritureBoolean . |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Libellé. Lecture seule[`IDataLabel`](../idatalabel) . |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Spécifie un marqueur de données. Lecture seule[`IMarker`](../imarker) . |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Propriétés de l'entrée de légende correspondante en cas de type de graphique de cette liste : ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Lecture seule[`ILegendEntryProperties`](../ilegendentryproperties) . |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Définit le point de données comme total. Appliqué pour le type de série Waterfall uniquement. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Renvoie la valeur de taille du point de données du graphique. Utilisé avec les graphiques Treemap et Sunburst. Lecture seule[`IDoubleChartValue`](../idoublechartvalue) . |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Valeur. Lecture seule[`IDoubleChartValue`](../idoublechartvalue) . |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Lecture seule[`IStringOrDoubleChartValue`](../istringordoublechartvalue) . |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Lecture seule[`IDoubleChartValue`](../idoublechartvalue) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Renvoie une couleur automatique du point de données en fonction de l'index de série, de l'index de point de données, de la propriété ParentSeriesGroup.IsColorVaried et du style de graphique. Cette couleur est utilisée par défaut si FillType vaut NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Supprime DataPoint de la série de graphiques. |

### Voir également

* interface [IChartDataPoint](../ichartdatapoint)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
