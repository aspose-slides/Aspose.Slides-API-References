---
title: IAxis
second_title: Référence API Aspose.Slides pour .NET
description: Encapsule l'objet qui représente un axe de graphique.
type: docs
weight: 1630
url: /fr/aspose.slides.charts/iaxis/
---

## Interface IAxis

Encapsule l'objet qui représente un axe de graphique.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Spécifie l'unité majeure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Spécifie l'échelle de l'unité majeure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Spécifie la valeur maximale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Spécifie l'unité mineure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Spécifie l'échelle de l'unité mineure réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Spécifie la valeur minimale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Représente le type d'agrégation de l'axe de catégories (binning). S'applique aux catégories. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Permet d'obtenir l'interface de base IFormattedTextContainer. Lecture seule [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Représente si l'axe des valeurs croise l'axe des catégories entre les catégories. Cette propriété s'applique uniquement aux axes des catégories, et elle ne s'applique pas aux graphiques en 3D. Boolean en lecture/écriture. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Spécifie la plus petite unité de temps qui est représentée sur l'axe des dates. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Spécifie la largeur du bin lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. S'applique aux axes des catégories. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Spécifie le type de l'axe des catégories. Lecture/écriture [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Représente le point sur l'axe où l'axe perpendiculaire le croise. Lecture/écriture Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Représente le CrossType sur l'axe spécifié où l'autre axe le croise. Lecture/écriture [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Spécifie la valeur d'échelle des unités d'affichage pour l'axe des valeurs. Lecture/écriture [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Représente le format de l'axe. Lecture seule [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Détermine si un axe a un titre visible. Boolean en lecture/écriture. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Indique si l'unité majeure de l'axe est assignée automatiquement. Boolean en lecture/écriture. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Indique si la valeur maximale est assignée automatiquement. Boolean en lecture/écriture. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Indique si l'unité mineure de l'axe est assignée automatiquement. Boolean en lecture/écriture. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Indique si la valeur minimale est assignée automatiquement. Boolean en lecture/écriture. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Spécifie la valeur du bin de dépassement automatique. Si faux : utilisez la propriété OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Spécifie la valeur d'espacement des étiquettes de graduation automatique. Si faux : utilisez la propriété TickLabelSpacing. Boolean en lecture/écriture. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Spécifie la valeur d'espacement des marques de graduation automatique. Si faux : utilisez la propriété TickMarksSpacing. Boolean en lecture/écriture. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Spécifie la valeur du bin de sous-dépassement automatique. Si faux : utilisez la propriété UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Représente si le type d'échelle de l'axe des valeurs est logarithmique ou non. Boolean en lecture/écriture. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Indique si le format est lié aux données sources. Boolean en lecture/écriture. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Spécifie si le bin de dépassement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bin de dépassement. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Représente si MS PowerPoint trace les points de données de la fin au début. Boolean en lecture/écriture. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Spécifie si le bin de sous-dépassement est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bin de sous-dépassement. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Représente si l'axe est visible. Boolean en lecture/écriture. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Spécifie la distance des étiquettes par rapport à l'axe. S'applique à l'axe des catégories ou des dates. La valeur doit être comprise entre 0 % et 1000 %. Lecture/écriture UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Représente la base logarithmique. La valeur par défaut est 10. Lecture/écriture Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Représente le format des lignes de grille majeures sur un axe de graphique. Lecture seule [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Représente le type de marque de graduation majeure pour l'axe spécifié. Lecture/écriture [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Représente les unités majeures pour l'axe des dates ou des valeurs. Lecture/écriture Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Représente l'échelle de l'unité majeure pour l'axe des dates. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Représente la valeur maximale sur l'axe des valeurs. Lecture/écriture Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Représente le format des lignes de grille mineures sur un axe de graphique. Lecture seule [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Représente le type de marque de graduation mineure pour l'axe spécifié. Lecture/écriture [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Représente les unités mineures pour l'axe des dates ou des valeurs. Lecture/écriture Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Représente l'échelle de l'unité majeure pour l'axe des dates. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Représente la valeur minimale sur l'axe des valeurs. Lecture/écriture Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Représente la chaîne de format pour les étiquettes d'axe. Lecture/écriture String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Spécifie le nombre de bins lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. S'applique aux axes des catégories. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Spécifie la valeur personnalisée du bin de dépassement. Appliqué lorsque la propriété IsAutomaticOverflowBin est définie sur false et que la propriété IsOverflowBin est égale à true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Représente la position de l'axe. Lecture/écriture [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Représente si les lignes de grille majeures sont affichées. Boolean en lecture seule. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Représente si les lignes de grille mineures sont affichées. Boolean en lecture seule. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Représente la position des étiquettes de marques de graduation sur l'axe spécifié. Lecture/écriture [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Représente l'angle de rotation des étiquettes de graduation. Lecture/écriture Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Spécifie combien d'étiquettes de marques de graduation doivent être sautées entre chaque étiquette dessinée. Lecture/écriture UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Spécifie combien de marques de graduation doivent être sautées avant que la suivante ne soit tracée. S'applique à l'axe des catégories ou des séries. Lecture/écriture UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Obtient le titre de l'axe. Lecture seule [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Spécifie la valeur personnalisée du bin de sous-dépassement. Appliqué lorsque la propriété IsAutomaticUnderflowBin est définie sur false et que la propriété IsUnderflowBin est égale à true. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Définit la propriété IAxis.CategoryAxisType avec une valeur automatiquement déterminée sur la base des données de l'axe. |

### Voir aussi

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../) 

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->