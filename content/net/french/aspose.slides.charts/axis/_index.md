---
title: Axis
second_title: Référence API Aspose.Slides pour .NET
description: Encapsule l'objet qui représente l'axe des graphiques.
type: docs
weight: 1100
url: /fr/aspose.slides.charts/axis/
---

## Classe Axe

Encapsule l'objet qui représente l'axe d'un graphique.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Spécifie l'unité majeure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Spécifie l'échelle de l'unité majeure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Spécifie la valeur maximale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Spécifie l'unité mineure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Spécifie l'échelle de l'unité mineure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Spécifie la valeur minimale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() auparavant pour obtenir la valeur réelle. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Représente le type d'agrégation de l'axe de catégorie (binning). Appliqué à la catégorie. Utilisé uniquement avec les séries Histogramme ou HistogrammePareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Représente si l'axe des valeurs traverse l'axe des catégories entre les catégories. Cette propriété s'applique uniquement aux axes de catégorie et ne s'applique pas aux graphiques 3-D. Booléen en lecture/écriture. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Spécifie la plus petite unité de temps représentée sur l'axe des dates. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Spécifie la largeur de bin lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogramme ou HistogrammePareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Spécifie le type de l'axe de catégorie. Lecture/écriture [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Renvoie le graphique parent. Lecture seule [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Représente le point sur l'axe où l'axe perpendiculaire le traverse. Lecture/écriture Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Représente le CrossType sur l'axe spécifié où l'autre axe croise. Lecture/écriture [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Spécifie la valeur d'échelle des unités d'affichage pour l'axe des valeurs. Lecture/écriture [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Représente le format de l'axe. Lecture seule [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Détermine si un axe a un titre visible. Booléen en lecture/écriture. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Indique si l'unité majeure de l'axe est assignée automatiquement. Booléen en lecture/écriture. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Indique si la valeur maximale est assignée automatiquement. Booléen en lecture/écriture. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Indique si l'unité mineure de l'axe est assignée automatiquement. Booléen en lecture/écriture. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Indique si la valeur minimale est assignée automatiquement. Booléen en lecture/écriture. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Spécifie la valeur du bin de débordement automatique. Si faux : utiliser la propriété OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Spécifie la valeur d'espacement des étiquettes de ticks automatique. Si faux : utiliser la propriété TickLabelSpacing. Booléen en lecture/écriture. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Spécifie la valeur d'espacement des marques de ticks automatique. Si faux : utiliser la propriété TickMarksSpacing. Booléen en lecture/écriture. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Spécifie la valeur du bin de sous-dépassement automatique. Si faux : utiliser la propriété UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Représente si le type d'échelle de l'axe des valeurs est logarithmique ou non. Booléen en lecture/écriture. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Indique si le format est lié à des données sources. Booléen en lecture/écriture. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Spécifie si un bin de débordement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bin de débordement. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Représente si MS PowerPoint trace les points de données du dernier au premier. Booléen en lecture/écriture. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Spécifie si un bin de sous-dépassement est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bin de sous-dépassement. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Représente si l'axe est visible. Booléen en lecture/écriture. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Spécifie la distance des étiquettes par rapport à l'axe. Appliqué à l'axe de catégorie ou de date. La valeur doit être comprise entre 0 % et 1000 %. Lecture/écriture UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Représente la base logarithmique. La valeur par défaut est 10. Lecture/écriture Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Représente le format des lignes de grille majeures sur un axe de graphique. Lecture seule [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Représente le type de marque de tick majeur pour l'axe spécifié. Lecture/écriture [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Représente les unités majeures pour l'axe de date ou de valeur. Lecture/écriture Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Représente l'échelle de l'unité majeure pour l'axe des dates. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Représente la valeur maximale sur l'axe des valeurs. Lecture/écriture Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Représente le format des lignes de grille mineures sur un axe de graphique. Lecture seule [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Représente le type de marque de tick mineur pour l'axe spécifié. Lecture/écriture [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Représente les unités mineures pour l'axe de date ou de valeur. Lecture/écriture Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Représente l'échelle de l'unité majeure pour l'axe des dates. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Représente la valeur minimale sur l'axe des valeurs. Lecture/écriture Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Représente la chaîne de format pour les étiquettes de l'axe. Lecture/écriture String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Spécifie le nombre de bins lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogramme ou HistogrammePareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Spécifie la valeur personnalisée du bin de débordement. Appliqué lorsque la propriété IsAutomaticOverflowBin est définie sur faux et que la propriété IsOverflowBin est égale à vrai. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Représente la position de l'axe. Lecture/écriture [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Pour cacher la ligne de grille majeure, définissez MajorGridLinesFormat.Line.FillFormat.FillType sur FillType.NoFill. Booléen en lecture seule. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Pour cacher la ligne de grille mineure, définissez MinorGridLinesFormat.Line.FillFormat.FillType sur FillType.NoFill. Booléen en lecture seule. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Représente le format du texte. Lecture seule [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Représente la position des étiquettes de marque de tick sur l'axe spécifié. Lecture/écriture [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Représente l'angle de rotation des étiquettes de ticks. Lecture/écriture Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Spécifie combien d'étiquettes de ticks sauter entre l'étiquette qui est dessinée. Appliqué à l'axe de catégorie ou de série. Lecture/écriture UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Spécifie combien de marques de ticks doivent être sautées avant que la suivante ne soit dessinée. Appliqué à l'axe de catégorie ou de série. Lecture/écriture UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Obtient le titre de l'axe. Lecture seule [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Spécifie la valeur personnalisée du bin de sous-dépassement. Appliqué lorsque la propriété IsAutomaticUnderflowBin est définie sur faux et que la propriété IsUnderflowBin est égale à vrai. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Définit la propriété IAxis.CategoryAxisType avec une valeur qui est déterminée automatiquement en fonction des données de l'axe. |

### Voir aussi

* classe [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* classe [AxesManager](../axesmanager)
* interface [IAxis](../iaxis)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->