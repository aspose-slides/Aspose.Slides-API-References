---
title: Axis
second_title: Référence de l'API Aspose.Slides pour .NET
description: Encapsule lobjet qui représente laxe dun graphique.
type: docs
weight: 1060
url: /fr/net/aspose.slides.charts/axis/
---
## Axis class

Encapsule l'objet qui représente l'axe d'un graphique.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Propriétés

| Nom | La description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Spécifie l'unité principale réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() précédemment pour obtenir la valeur réelle. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Spécifie l'échelle d'unité majeure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() précédemment pour obtenir la valeur réelle. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Spécifie la valeur maximale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() précédemment pour obtenir la valeur réelle. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Spécifie l'unité mineure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() précédemment pour obtenir la valeur réelle. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Spécifie l'échelle d'unité mineure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() précédemment pour obtenir la valeur réelle. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Spécifie la valeur minimale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() précédemment pour obtenir la valeur réelle. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Représente le type d'agrégation de l'axe des catégories (binning). Appliqué à la catégorie. Utilisé avec les séries Histogram ou HistogramPareto uniquement. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Représente si l'axe des valeurs croise l'axe des catégories entre les catégories. Cette propriété s'applique uniquement aux axes des catégories et ne s'applique pas aux graphiques 3D. Lecture/écritureBoolean . |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Spécifie la plus petite unité de temps représentée sur l'axe des dates. Lecture/écriture[`TimeUnitType`](../timeunittype) . |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Spécifie la largeur du bac lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. Appliqué aux axes de catégorie. Utilisé avec les séries Histogram ou HistogramPareto uniquement. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Spécifie le type de l'axe des catégories. Lecture/écriture[`CategoryAxisType`](../categoryaxistype) . |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Renvoie le graphique parent. Lecture seule[`IChart`](../ichart) . |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Représente le point sur l'axe où l'axe perpendiculaire le croise. Lecture/écritureSingle . |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Représente le CrossType sur l'axe spécifié où l'autre axe se croise. Lecture/écriture[`CrossesType`](../crossestype) . |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Spécifie la valeur d'échelle des unités d'affichage pour l'axe des ordonnées. Lecture/écriture[`DisplayUnitType`](../displayunittype) . |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Représente le format de l'axe. Lecture seule[`IAxisFormat`](../iaxisformat) . |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Détermine si un axe a un titre visible. Lecture/écritureBoolean . |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Indique si l'unité majeure de l'axe est automatiquement affectée. Lecture/écritureBoolean . |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Indique si la valeur maximale est automatiquement attribuée. Lecture/écritureBoolean . |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Indique si l'unité mineure de l'axe est automatiquement affectée. Lecture/écritureBoolean . |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Indique si la valeur min est automatiquement attribuée. Lecture/écritureBoolean . |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Spécifie la valeur du bac de débordement automatique. Si faux : utilisez la propriété OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Spécifie la valeur d'espacement automatique des étiquettes de graduation. Si faux : utilisez la propriété TickLabelSpacing. Lecture/écritureBoolean . |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Spécifie la valeur d'espacement automatique des graduations. Si faux : utilisez la propriété TickMarksSpacing. Lecture/écritureBoolean . |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Spécifie la valeur de casier de débordement automatique. Si faux : utilisez la propriété UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Représente si le type d'échelle de l'axe des valeurs est logarithmique ou non. Lecture/écritureBoolean . |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Indique si le format est lié aux données source. Lecture/écritureBoolean . |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Spécifie si le bac de débordement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bac de débordement. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Représente si MS PowerPoint trace les points de données du dernier au premier. Lecture/écritureBoolean . |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Spécifie si le bac de débordement est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bac de dépassement inférieur. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Indique si l'axe est visible. Lecture/écritureBoolean . |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Spécifie la distance des étiquettes par rapport à l'axe. Appliqué à l'axe des catégories ou des dates. La valeur doit être comprise entre 0 % et 1 000 %. Lecture/écritureUInt16 . |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Représente la base logarithmique. La valeur par défaut est 10. Lecture/écritureDouble . |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Représente le format du quadrillage principal sur un axe de graphique. Lecture seule[`IChartLinesFormat`](../ichartlinesformat) . |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Représente le type de graduation principale pour l'axe spécifié. Lecture/écriture[`TickMarkType`](../tickmarktype) . |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Représente les unités principales de l'axe des dates ou des valeurs. Lecture/écritureDouble . |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Représente l'échelle des unités majeures pour l'axe des dates. Lecture/écriture[`TimeUnitType`](../timeunittype) . |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Représente la valeur maximale sur l'axe des valeurs. Lecture/écritureDouble . |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Représente le format de quadrillage mineur sur un axe de graphique. Lecture seule[`IChartLinesFormat`](../ichartlinesformat) . |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Représente le type de graduation mineure pour l'axe spécifié. Lecture/écriture[`TickMarkType`](../tickmarktype) . |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Représente les unités mineures pour l'axe des dates ou des valeurs. Lecture/écritureDouble . |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Représente l'échelle des unités majeures pour l'axe des dates. Lecture/écriture[`TimeUnitType`](../timeunittype) . |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Représente la valeur minimale sur l'axe des valeurs. Lecture/écritureDouble . |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Représente la chaîne de format pour les étiquettes d'axe. Lecture/écritureString . |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Spécifie le nombre de casiers lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. Appliqué aux axes de catégorie. Utilisé avec les séries Histogram ou HistogramPareto uniquement. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Spécifie la valeur personnalisée du bac de débordement. Appliqué lorsque la propriété IsAutomaticOverflowBin est définie sur false et que la propriété IsOverflowBin est égale à true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Représente la position de l'axe. Lecture/écriture[`AxisPositionType`](../axispositiontype) . |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Pour masquer le quadrillage principal, définissez MajorGridLinesFormat.Line.FillFormat.FillType sur FillType.NoFill. Lecture seuleBoolean . |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Pour masquer le quadrillage mineur, définissez MinorGridLinesFormat.Line.FillFormat.FillType sur FillType.NoFill. Lecture seuleBoolean . |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Représente le format du texte. Lecture seule[`IChartTextFormat`](../icharttextformat) . |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Représente la position des étiquettes de graduation sur l'axe spécifié. Lecture/écriture[`TickLabelPositionType`](../ticklabelpositiontype) . |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Représente l'angle de rotation des étiquettes de graduation. Lecture/écritureSingle . |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Spécifie le nombre d'étiquettes de graduation à ignorer entre les étiquettes dessinées. Appliqué à l'axe des catégories ou des séries. Lecture/écritureUInt32 . |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Spécifie combien de graduations doivent être ignorées avant que la suivante ne soit dessinée. Appliqué à l'axe des catégories ou des séries. Lecture/écritureUInt16 . |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Obtient le titre de l'axe. Lecture seule[`IChartTitle`](../icharttitle) . |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Spécifie la valeur personnalisée du bac de dépassement inférieur. Appliqué lorsque la propriété IsAutomaticUnderflowBin est définie sur false et que la propriété IsUnderflowBin est égale à true. |

## Méthodes

| Nom | La description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Définit la propriété IAxis.CategoryAxisType avec une valeur qui est automatiquement déterminée en fonction des données de l'axe. |

### Voir également

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [AxesManager](../axesmanager)
* interface [IAxis](../iaxis)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
