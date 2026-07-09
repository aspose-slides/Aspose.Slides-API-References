---
title: Axis
second_title: Référence API Aspose.Sildes pour .NET
description: Encapsule l'objet qui représente l'axe d'un graphique.
type: docs
weight: 1180
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
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Spécifie l'unité principale réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Spécifie l'échelle réelle de l'unité principale de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Spécifie la valeur maximale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Spécifie l'unité secondaire réelle de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Spécifie l'échelle réelle de l'unité secondaire de l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Spécifie la valeur minimale réelle sur l'axe. Appelez la méthode IChart.ValidateChartLayout() au préalable pour obtenir la valeur réelle. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Représente le type d'agrégation de l'axe de catégorie (groupement). Appliqué aux catégories. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Indique si l'axe des valeurs croise l'axe des catégories entre les catégories. Cette propriété s'applique uniquement aux axes de catégorie et ne s'applique pas aux graphiques 3D. Lecture/écriture Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Spécifie la plus petite unité de temps représentée sur l'axe des dates. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Spécifie la largeur du bin lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByBinWidth. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Spécifie le type de l'axe de catégorie. Lecture/écriture [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Renvoie le graphique parent. Lecture seule [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Représente le point sur l'axe où l'axe perpendiculaire le croise. Lecture/écriture Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Représente le CrossType sur l'axe spécifié où l'autre axe le croise. Lecture/écriture [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Spécifie la valeur de mise à l'échelle des unités d'affichage pour l'axe des valeurs. Lecture/écriture [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Représente le format de l'axe. Lecture seule [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Détermine si un axe possède un titre visible. Lecture/écriture Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Indique si l'unité principale de l'axe est attribuée automatiquement. Lecture/écriture Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Indique si la valeur maximale est attribuée automatiquement. Lecture/écriture Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Indique si l'unité secondaire de l'axe est attribuée automatiquement. Lecture/écriture Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Indique si la valeur minimale est attribuée automatiquement. Lecture/écriture Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Spécifie la valeur du bin de dépassement automatique. Si false : utilisez la propriété OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Spécifie la valeur de l'espacement automatique des étiquettes de repère. Si false : utilisez la propriété TickLabelSpacing. Lecture/écriture Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Spécifie la valeur de l'espacement automatique des marques de repère. Si false : utilisez la propriété TickMarksSpacing. Lecture/écriture Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Spécifie la valeur du bin de sous-flux automatique. Si false : utilisez la propriété UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Indique si le type d'échelle de l'axe des valeurs est logarithmique ou non. Lecture/écriture Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Indique si le format est lié aux données sources. Lecture/écriture Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Indique si le bin de dépassement est appliqué. Utilisez IsAutomaticOverflowBin et OverflowBin pour ajuster la valeur du bin de dépassement. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Indique si MS PowerPoint trace les points de données du dernier au premier. Lecture/écriture Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Indique si le bin de sous-flux est appliqué. Utilisez IsAutomaticUnderflowBin et UnderflowBin pour ajuster la valeur du bin de sous-flux. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Indique si l'axe est visible. Lecture/écriture Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Spécifie la distance des étiquettes par rapport à l'axe. Appliqué aux axes de catégorie ou de date. La valeur doit être comprise entre 0% et 1000%. Lecture/écriture UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Représente la base logarithmique. La valeur par défaut est 10. Lecture/écriture Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Représente le format des lignes de grille majeures sur un axe de graphique. Lecture seule [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Représente le type de repère majeur pour l'axe spécifié. Lecture/écriture [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Représente les unités majeures pour l'axe de date ou de valeur. Lecture/écriture Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Représente l'échelle de l'unité majeure pour l'axe de date. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Représente la valeur maximale sur l'axe des valeurs. Lecture/écriture Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Représente le format des lignes de grille secondaires sur un axe de graphique. Lecture seule [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Représente le type de repère secondaire pour l'axe spécifié. Lecture/écriture [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Représente les unités secondaires pour l'axe de date ou de valeur. Lecture/écriture Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Représente l'échelle de l'unité majeure pour l'axe de date. Lecture/écriture [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Représente la valeur minimale sur l'axe des valeurs. Lecture/écriture Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Représente la chaîne de format pour les étiquettes d'axe. Lecture/écriture String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Spécifie le nombre de bins lorsque la valeur de la propriété AggregationType est définie sur AxisAggregationType.ByNumberOfBins. Appliqué aux axes de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Spécifie la valeur personnalisée du bin de dépassement. Appliqué lorsque la propriété IsAutomaticOverflowBin est définie sur false et que la propriété IsOverflowBin vaut true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Représente la position de l'axe. Lecture/écriture [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Pour masquer la ligne de grille majeure, définissez MajorGridLinesFormat.Line.FillFormat.FillType sur FillType.NoFill. Lecture seule Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Pour masquer la ligne de grille secondaire, définissez MinorGridLinesFormat.Line.FillFormat.FillType sur FillType.NoFill. Lecture seule Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Représente le format du texte. Lecture seule [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Représente la position des étiquettes de repère sur l'axe spécifié. Lecture/écriture [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Représente l'angle de rotation des étiquettes de repère. Lecture/écriture Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Spécifie combien d'étiquettes de repère doivent être sautées entre les étiquettes dessinées. Appliqué à l'axe de catégorie ou de série. Lecture/écriture UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Spécifie combien de marques de repère doivent être sautées avant que la suivante ne soit dessinée. Appliqué à l'axe de catégorie ou de série. Lecture/écriture UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Obtient le titre de l'axe. Lecture seule [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Spécifie la valeur personnalisée du bin de sous-flux. Appliqué lorsque la propriété IsAutomaticUnderflowBin est définie sur false et que la propriété IsUnderflowBin vaut true. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Définit la propriété IAxis.CategoryAxisType avec une valeur déterminée automatiquement en fonction des données de l'axe. |

### Voir aussi

* classe [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* classe [AxesManager](../axesmanager)
* interface [IAxis](../iaxis)
* espace de noms [Aspose.Slides.Charts](../../aspose.slides.charts)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->