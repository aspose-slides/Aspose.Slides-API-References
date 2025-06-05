---
title: Axis
second_title: Référence API Aspose.Slides pour .NET
description: Encapsule l'objet qui représente un axe de graphique.
type: docs
weight: 1100
url: /fr/aspose.slides.charts/axis/
---

## Classe Axis

Encapsule l'objet qui représente l'axe d'un graphique.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Spécifie l'unité principale réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Spécifie l'échelle d'unité principale réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Spécifie la valeur maximale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Spécifie l'unité mineure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Spécifie l'échelle d'unité mineure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Spécifie la valeur minimale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Représente le type d'agrégation de l'axe de catégorie (binning). S'applique à la catégorie. Utilisé uniquement avec des séries Histogram ou HistogramPareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Représente si l'axe des valeurs croise l'axe des catégories entre les catégories. Cette propriété s'applique uniquement aux axes de catégorie et ne s'applique pas aux graphiques 3-D. Lecture/écriture Booléen. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Spécifie la plus petite unité de temps représentée sur l'axe des dates. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Spécifie la largeur de bin lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. S'applique aux axes de catégorie. Utilisé uniquement avec des séries Histogram ou HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Spécifie le type de l'axe de catégorie. Lecture/écriture [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Retourne le graphique parent. Lecture seule [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Représente le point sur l'axe où l'axe perpendiculaire le croise. Lecture/écriture Simple. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Représente le CrossType sur l'axe spécifié où l'autre axe croise. Lecture/écriture [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Spécifie la valeur d'échelle des unités d'affichage pour l'axe des valeurs. Lecture/écriture [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Représente le format de l'axe. Lecture seule [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Détermine si un axe a un titre visible. Lecture/écriture Booléen. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Indique si l'unité principale de l'axe est automatiquement assignée. Lecture/écriture Booléen. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Indique si la valeur maximale est automatiquement assignée. Lecture/écriture Booléen. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Indique si l'unité mineure de l'axe est automatiquement assignée. Lecture/écriture Booléen. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Indique si la valeur minimale est automatiquement assignée. Lecture/écriture Booléen. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Spécifie la valeur de bin de débordement automatique. Si faux : utilisez la propriété OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Spécifie la valeur d'espacement des étiquettes de graduation automatique. Si faux : utilisez la propriété TickLabelSpacing. Lecture/écriture Booléen. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Spécifie la valeur d'espacement des marques de graduation automatique. Si faux : utilisez la propriété TickMarksSpacing. Lecture/écriture Booléen. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Spécifie la valeur de bin de sous-dépassement automatique. Si faux : utilisez la propriété UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Représente si le type d'échelle de l'axe des valeurs est logarithmique ou non. Lecture/écriture Booléen. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Indique si le format est lié aux données source. Lecture/écriture Booléen. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Spécifie si le bin de débordement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bin de débordement. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Représente si MS PowerPoint trace les points de données de la fin au début. Lecture/écriture Booléen. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Spécifie si le bin de sous-dépassement est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bin de sous-dépassement. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Représente si l'axe est visible. Lecture/écriture Booléen. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Spécifie la distance des étiquettes par rapport à l'axe. S'applique à l'axe de catégorie ou de date. La valeur doit être comprise entre 0 % et 1000 %. Lecture/écriture UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Représente la base logarithmique. La valeur par défaut est 10. Lecture/écriture Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Représente le format des lignes de grille majeures sur un axe de graphique. Lecture seule [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Représente le type de marque principale pour l'axe spécifié. Lecture/écriture [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Représente les unités principales pour l'axe de date ou de valeur. Lecture/écriture Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Représente l'échelle d'unité principale pour l'axe des dates. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Représente la valeur maximale sur l'axe des valeurs. Lecture/écriture Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Représente le format des lignes de grille mineures sur un axe de graphique. Lecture seule [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Représente le type de marque mineure pour l'axe spécifié. Lecture/écriture [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Représente les unités mineures pour l'axe de date ou de valeur. Lecture/écriture Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Représente l'échelle d'unité mineure pour l'axe des dates. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Représente la valeur minimale sur l'axe des valeurs. Lecture/écriture Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Représente la chaîne de format pour les étiquettes d'axe. Lecture/écriture String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Spécifie le nombre de bins lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. S'applique aux axes de catégorie. Utilisé uniquement avec des séries Histogram ou HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Spécifie la valeur personnalisée du bin de débordement. S'applique lorsque la propriété IsAutomaticOverflowBin est définie sur faux et que la propriété IsOverflowBin est égale à vrai. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Représente la position de l'axe. Lecture/écriture [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Pour masquer la ligne de grille majeure, définissez MajorGridLinesFormat.Line.FillFormat.FillType sur FillType.NoFill. Lecture seule Booléen. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Pour masquer la ligne de grille mineure, définissez MinorGridLinesFormat.Line.FillFormat.FillType sur FillType.NoFill. Lecture seule Booléen. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Représente le format de texte. Lecture seule [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Représente la position des étiquettes de marque de graduation sur l'axe spécifié. Lecture/écriture [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Représente l'angle de rotation des étiquettes de graduation. Lecture/écriture Simple. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Spécifie combien d'étiquettes de graduation doivent être sautées entre chaque étiquette dessinée. S'applique à l'axe de catégorie ou de série. Lecture/écriture UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Spécifie combien de marques de graduation doivent être sautées avant que la suivante ne soit dessinée. S'applique à l'axe de catégorie ou de série. Lecture/écriture UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Obtient le titre de l'axe. Lecture seule [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Spécifie la valeur personnalisée du bin de sous-dépassement. S'applique lorsque la propriété IsAutomaticUnderflowBin est définie sur faux et que la propriété IsUnderflowBin est égale à vrai. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Définit la propriété IAxis.CategoryAxisType avec une valeur qui est automatiquement déterminée en fonction des données de l'axe. |

### Voir aussi

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [AxesManager](../axesmanager)
* interface [IAxis](../iaxis)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)