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
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Spécifie l'unité majeure actuelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur actuelle. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Spécifie l'échelle de l'unité majeure actuelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur actuelle. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Spécifie la valeur maximale actuelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur actuelle. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Spécifie l'unité mineure actuelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur actuelle. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Spécifie l'échelle de l'unité mineure actuelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur actuelle. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Spécifie la valeur minimale actuelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur actuelle. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Représente le type d'agrégation de l'axe de catégorie (binnage). Appliqué à la catégorie. Utilisé uniquement avec les séries Histogramme ou HistogrammePareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Permet d'obtenir l'interface de base IFormattedTextContainer. Lecture seule [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Représente si l'axe des valeurs croise l'axe des catégories entre les catégories. Cette propriété s'applique uniquement aux axes de catégorie et ne s'applique pas aux graphiques 3-D. Lecture/écriture Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Spécifie la plus petite unité de temps représentée sur l'axe des dates. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Spécifie la largeur des bacs lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogramme ou HistogrammePareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Spécifie le type de l'axe des catégories. Lecture/écriture [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Représente le point sur l'axe où l'axe perpendiculaire le croise. Lecture/écriture Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Représente le type de croisement sur l'axe spécifié où l'autre axe croise. Lecture/écriture [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Spécifie la valeur d'échelle des unités d'affichage pour l'axe des valeurs. Lecture/écriture [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Représente le format de l'axe. Lecture seule [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Détermine si un axe a un titre visible. Lecture/écriture Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Indique si l'unité majeure de l'axe est automatiquement assignée. Lecture/écriture Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Indique si la valeur maximale est automatiquement assignée. Lecture/écriture Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Indique si l'unité mineure de l'axe est automatiquement assignée. Lecture/écriture Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Indique si la valeur minimale est automatiquement assignée. Lecture/écriture Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Spécifie la valeur du bac de débordement automatique. Si faux : utilisez la propriété OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Spécifie la valeur d'espacement des étiquettes de graduation automatique. Si faux : utilisez la propriété TickLabelSpacing. Lecture/écriture Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Spécifie la valeur d'espacement des marques de graduation automatique. Si faux : utilisez la propriété TickMarksSpacing. Lecture/écriture Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Spécifie la valeur du bac de sous-flux automatique. Si faux : utilisez la propriété UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Représente si le type d'échelle de l'axe des valeurs est logarithmique ou non. Lecture/écriture Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Indique si le format est lié aux données source. Lecture/écriture Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Spécifie si le bac de débordement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bac de débordement. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Représente si MS PowerPoint trace les points de données de la fin au début. Lecture/écriture Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Spécifie si le bac de sous-flux est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bac de sous-flux. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Représente si l'axe est visible. Lecture/écriture Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Spécifie la distance des étiquettes par rapport à l'axe. Appliqué aux axes de catégorie ou de date. La valeur doit être comprise entre 0 % et 1000 %. Lecture/écriture UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Représente la base logarithmique. La valeur par défaut est 10. Lecture/écriture Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Représente le format des principales lignes de grille sur un axe de graphique. Lecture seule [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Représente le type de marque de graduation majeure pour l'axe spécifié. Lecture/écriture [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Représente les unités majeures pour l'axe des dates ou des valeurs. Lecture/écriture Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Représente l'échelle de l'unité majeure pour l'axe des dates. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Représente la valeur maximale sur l'axe des valeurs. Lecture/écriture Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Représente le format des lignes de grille mineures sur un axe de graphique. Lecture seule [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Représente le type de marque de graduation mineure pour l'axe spécifié. Lecture/écriture [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Représente les unités mineures pour l'axe des dates ou des valeurs. Lecture/écriture Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Représente l'échelle de l'unité majeure pour l'axe des dates. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Représente la valeur minimale sur l'axe des valeurs. Lecture/écriture Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Représente la chaîne de format pour les étiquettes de l'axe. Lecture/écriture String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Spécifie le nombre de bacs lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogramme ou HistogrammePareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Spécifie la valeur personnalisée du bac de débordement. Appliqué lorsque la propriété IsAutomaticOverflowBin est définie sur faux et que la propriété IsOverflowBin est égale à vrai. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Représente la position de l'axe. Lecture/écriture [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Représente si les principales lignes de grille sont affichées. Lecture seule Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Représente si les lignes de grille mineures sont affichées. Lecture seule Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Représente la position des étiquettes de marques de graduation sur l'axe spécifié. Lecture/écriture [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Représente l'angle de rotation des étiquettes de graduation. Lecture/écriture Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Spécifie combien d'étiquettes de graduation sauter entre l'étiquette dessinée. Lecture/écriture UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Spécifie combien de marques de graduation doivent être sautées avant que la suivante soit dessinée. Appliqué aux axes de catégorie ou de séries. Lecture/écriture UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Obtient le titre de l'axe. Lecture seule [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Spécifie la valeur personnalisée du bac de sous-flux. Appliqué lorsque la propriété IsAutomaticUnderflowBin est définie sur faux et que la propriété IsUnderflowBin est égale à vrai. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Définit la propriété IAxis.CategoryAxisType avec une valeur qui est automatiquement déterminée en fonction des données de l'axe. |

### Voir aussi

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->