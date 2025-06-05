---
title: IAxis
second_title: Aspose.Sildes für .NET API Referenz
description: Kapselt das Objekt, das eine Achse des Diagramms darstellt.
type: docs
weight: 1630
url: /de/aspose.slides.charts/iaxis/
---

## IAxis-Schnittstelle

Kapselt das Objekt, das eine Achse eines Diagramms darstellt.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Gibt die tatsächliche Hauptgröße der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Gibt die tatsächliche Skala der Hauptgröße der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Gibt den tatsächlichen maximalen Wert auf der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Gibt die tatsächliche Neben-Unit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Gibt die tatsächliche Skala der Neben-Unit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Gibt den tatsächlichen minimalen Wert auf der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Stellt den Aggregationstyp der Kategorieneachse (Binning) dar. Wird auf Kategorien angewendet. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Ermöglicht den Zugriff auf die Basis-IFormattedTextContainer-Schnittstelle. Nur-Lesen [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Stellt dar, ob die Werteachse die Kategorieneachse zwischen den Kategorien kreuzt. Diese Eigenschaft gilt nur für Kategorieneachsen und nicht für 3D-Diagramme. Lese-/Schreibbare Boolesche Variable. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Lese-/schreibbar [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Gibt die Breite des Behälters an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByBinWidth gesetzt ist. Wird auf Kategorieneachsen angewendet. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Gibt den Typ der Kategorieneachse an. Lese-/schreibbar [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Stellt den Punkt auf der Achse dar, an dem sich die senkrechte Achse kreuzt. Lese-/schreibbar Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Stellt den CrossType auf der angegebenen Achse dar, wo die andere Achse kreuzt. Lese-/schreibbar [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. Lese-/schreibbar [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Stellt das Format der Achse dar. Nur-Lesen [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Bestimmt, ob eine Achse einen sichtbaren Titel hat. Lese-/schreibbare Boolesche Variable. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Gibt an, ob die Hauptgröße der Achse automatisch zugewiesen ist. Lese-/schreibbare Boolesche Variable. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Gibt an, ob der maximale Wert automatisch zugewiesen ist. Lese-/schreibbare Boolesche Variable. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Gibt an, ob die Nebeneinheit der Achse automatisch zugewiesen ist. Lese-/schreibbare Boolesche Variable. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Gibt an, ob der minimale Wert automatisch zugewiesen ist. Lese-/schreibbare Boolesche Variable. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Gibt den automatischen Überlaufbehälterwert an. Wenn false: verwenden Sie die OverflowBin-Eigenschaft. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Gibt den automatischen Abstand der Tick-Labels an. Wenn false: verwenden Sie die TickLabelSpacing-Eigenschaft. Lese-/schreibbare Boolesche Variable. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Gibt den automatischen Abstand der Tick-Marken an. Wenn false: verwenden Sie die TickMarksSpacing-Eigenschaft. Lese-/schreibbare Boolesche Variable. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Gibt den automatischen Unterlaufbehälterwert an. Wenn false: verwenden Sie die UnderflowBin-Eigenschaft. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Stellt dar, ob der Skalentyp der Werteachse logarithmisch ist oder nicht. Lese-/schreibbare Boolesche Variable. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Gibt an, ob das Format an die Quelldaten gebunden ist. Lese-/schreibbare Boolesche Variable. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Gibt an, ob der Überlaufbehälter angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Überlaufbehälterwert anzupassen. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Stellt dar, ob MS PowerPoint die Datenpunkte von zuletzt nach zuerst darstellt. Lese-/schreibbare Boolesche Variable. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Gibt an, ob der Unterlaufbehälter angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Unterlaufbehälterwert anzupassen. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Stellt dar, ob die Achse sichtbar ist. Lese-/schreibbare Boolesche Variable. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Gibt den Abstand der Labels von der Achse an. Wird auf die Kategorie- oder Datumsachse angewendet. Der Wert muss zwischen 0 % und 1000 % liegen. Lese-/schreibbar UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Stellt die logarithmische Basis dar. Der Standardwert ist 10. Lese-/schreibbar Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Stellt das Format der Hauptgitterlinien auf einer Diagrammachse dar. Nur-Lesen [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Stellt den Typ der Haupttickmark für die angegebene Achse dar. Lese-/schreibbar [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Stellt die Hauptgrößen für die Datums- oder Werteachse dar. Lese-/schreibbar Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Stellt die Hauptunitskala für die Datumsachse dar. Lese-/schreibbar [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Stellt den maximalen Wert auf der Werteachse dar. Lese-/schreibbar Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Stellt das Format der Nebengitterlinien auf einer Diagrammachse dar. Nur-Lesen [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Stellt den Typ der Nebentickmark für die angegebene Achse dar. Lese-/schreibbar [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Stellt die Nebeneinheiten für die Datums- oder Werteachse dar. Lese-/schreibbar Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Stellt die Hauptunitskala für die Datumsachse dar. Lese-/schreibbar [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Stellt den minimalen Wert auf der Werteachse dar. Lese-/schreibbar Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Stellt die Formatzeichenfolge für die Achsenbeschriftungen dar. Lese-/schreibbar String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Gibt die Anzahl der Behälter an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByNumberOfBins gesetzt ist. Wird auf Kategorieneachsen angewendet. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Gibt den benutzerdefinierten Wert des Überlaufbehälters an. Wird angewendet, wenn die Eigenschaft IsAutomaticOverflowBin auf false gesetzt ist und die IsOverflowBin-Eigenschaft den Wert true hat. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Stellt die Position der Achse dar. Lese-/schreibbar [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Stellt dar, ob die Hauptgitterlinien angezeigt werden. Nur-Lesen Boolesche Variable. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Stellt dar, ob die Nebengitterlinien angezeigt werden. Nur-Lesen Boolesche Variable. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Stellt die Position der Tickmark-Beschriftungen auf der angegebenen Achse dar. Lese-/schreibbar [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Stellt den Rotationswinkel der Tick-Beschriftungen dar. Lese-/schreibbar Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Gibt an, wie viele Tick-Beschriftungen zwischen den gezeichneten Beschriftungen übersprungen werden sollen. Lese-/schreibbar UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Gibt an, wie viele Tick-Marken übersprungen werden sollen, bevor die nächste gezeichnet wird. Wird auf Kategorie- oder Serienachsen angewendet. Lese-/schreibbar UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Gibt den Titel der Achse zurück. Nur-Lesen [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Gibt den benutzerdefinierten Wert des Unterlaufbehälters an. Wird angewendet, wenn die Eigenschaft IsAutomaticUnderflowBin auf false gesetzt ist und die IsUnderflowBin-Eigenschaft den Wert true hat. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Setzt die IAxis.CategoryAxisType-Eigenschaft mit einem Wert, der automatisch auf Basis der Achsendaten bestimmt wird. |

### Siehe auch

* Schnittstelle [IFormattedTextContainer](../iformattedtextcontainer)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->