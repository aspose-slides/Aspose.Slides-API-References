---
title: IAxis
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Encapsule l'objet qui représente l'axe d'un graphique.
type: docs
weight: 1710
url: /fr/aspose.slides.charts/iaxis/
---
## IAxis interface

Encapsule l'objet qui représente l'axe d'un graphique.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Spécifie l'unité principale réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Spécifie l'échelle de l'unité principale réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Spécifie la valeur maximale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Spécifie l'unité secondaire réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Spécifie l'échelle de l'unité secondaire réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Spécifie la valeur minimale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Représente le type d'agrégation de l'axe de catégorie (regroupement). Appliqué à la catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Permet d'obtenir l'interface de base IFormattedTextContainer. Lecture seule [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Indique si l'axe de valeurs croise l'axe de catégorie entre les catégories. Cette propriété s'applique uniquement aux axes de catégorie et ne s'applique pas aux graphiques 3D. Lecture/écriture Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Spécifie la plus petite unité de temps représentée sur l'axe de date. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Spécifie la largeur du bin lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Spécifie le type de l'axe de catégorie. Lecture/écriture [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Représente le point sur l'axe où l'axe perpendiculaire le croise. Lecture/écriture Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Représente le CrossType sur l'axe spécifié où l'autre axe le croise. Lecture/écriture [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Spécifie la valeur d'échelle des unités d'affichage pour l'axe de valeur. Lecture/écriture [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Représente le format de l'axe. Lecture seule [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Détermine si un axe possède un titre visible. Lecture/écriture Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Indique si l'unité principale de l'axe est assignée automatiquement. Lecture/écriture Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Indique si la valeur maximale est assignée automatiquement. Lecture/écriture Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Indique si l'unité secondaire de l'axe est assignée automatiquement. Lecture/écriture Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Indique si la valeur minimale est assignée automatiquement. Lecture/écriture Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Spécifie la valeur du bin de débordement automatique. Si false : utilisez la propriété OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Spécifie la valeur de l'espacement automatique des étiquettes de graduation. Si false : utilisez la propriété TickLabelSpacing. Lecture/écriture Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Spécifie la valeur de l'espacement automatique des marques de graduation. Si false : utilisez la propriété TickMarksSpacing. Lecture/écriture Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Spécifie la valeur du bin de sous-débordement automatique. Si false : utilisez la propriété UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Indique si le type d'échelle de l'axe de valeur est logarithmique ou non. Lecture/écriture Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Indique si le format est lié aux données source. Lecture/écriture Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Spécifie si le bin de débordement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bin de débordement. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Indique si MS PowerPoint trace les points de données du dernier au premier. Lecture/écriture Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Spécifie si le bin de sous-débordement est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bin de sous-débordement. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Indique si l'axe est visible. Lecture/écriture Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Spécifie la distance des étiquettes par rapport à l'axe. Appliqué aux axes de catégorie ou de date. La valeur doit être comprise entre 0% et 1000%. Lecture/écriture UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Représente la base logarithmique. La valeur par défaut est 10. Lecture/écriture Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Représente le format des lignes de quadrillage majeures sur un axe de graphique. Lecture seule [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Représente le type de marque de graduation majeure pour l'axe spécifié. Lecture/écriture [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Représente les unités majeures pour l'axe de date ou de valeur. Lecture/écriture Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Représente l'échelle de l'unité majeure pour l'axe de date. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Représente la valeur maximale sur l'axe de valeur. Lecture/écriture Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Représente le format des lignes de quadrillage mineures sur un axe de graphique. Lecture seule [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Représente le type de marque de graduation mineure pour l'axe spécifié. Lecture/écriture [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Représente les unités mineures pour l'axe de date ou de valeur. Lecture/écriture Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Représente l'échelle de l'unité majeure pour l'axe de date. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Représente la valeur minimale sur l'axe de valeur. Lecture/écriture Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Représente la chaîne de format pour les étiquettes d'axe. Lecture/écriture String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Spécifie le nombre de bins lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Spécifie la valeur personnalisée du bin de débordement. Appliqué lorsque la propriété IsAutomaticOverflowBin est définie sur false et que la propriété IsOverflowBin vaut true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Représente la position de l'axe. Lecture/écriture [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Indique si les lignes de quadrillage majeures sont affichées. Lecture seule Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Indique si les lignes de quadrillage mineures sont affichées. Lecture seule Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Représente la position des étiquettes de marques de graduation sur l'axe spécifié. Lecture/écriture [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Représente l'angle de rotation des étiquettes de graduation. Lecture/écriture Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Spécifie le nombre d'étiquettes de graduation à ignorer entre les étiquettes affichées. Lecture/écriture UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Spécifie le nombre de marques de graduation à sauter avant que la suivante ne soit dessinée. Appliqué à l'axe de catégorie ou de série. Lecture/écriture UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Obtient le titre de l'axe. Lecture seule [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Spécifie la valeur personnalisée du bin de sous-débordement. Appliqué lorsque la propriété IsAutomaticUnderflowBin est définie sur false et que la propriété IsUnderflowBin vaut true. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Définit la propriété IAxis.CategoryAxisType avec une valeur automatiquement déterminée en fonction des données de l'axe. |

### Voir aussi

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->