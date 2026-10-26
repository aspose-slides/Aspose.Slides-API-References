---
title: IAxis
second_title: Aspose.Sildes für .NET API-Referenz
description: Kapselt das Objekt, das die Achse eines Diagramms darstellt.
type: docs
weight: 1710
url: /de/aspose.slides.charts/iaxis/
---
## IAxis Schnittstelle

Kapselt das Objekt, das die Achse eines Diagramms darstellt.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Gibt die tatsächliche Haupteinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Gibt die tatsächliche Skalierung der Haupteinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Gibt den tatsächlichen Maximalwert auf der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Gibt die tatsächliche Nebeneinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Gibt die tatsächliche Skalierung der Nebeneinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Gibt den tatsächlichen Minimalwert auf der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Stellt den Aggregationstyp der Kategorienachse (Binning) dar. Auf Kategorie angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Ermöglicht das Abrufen der Basis-IFormattedTextContainer-Schnittstelle. Nur-Lesen [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Gibt an, ob die Werteachse die Kategorienachse zwischen Kategorien schneidet. Diese Eigenschaft gilt nur für Kategorienachsen und nicht für 3-D-Diagramme. Lesen/Schreiben Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Lesen/Schreiben [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Gibt die Bin-Breite an, wenn der AggregationType-Eigenschaftswert auf AxisAggregationType.ByBinWidth gesetzt ist. Auf Kategorienachsen angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Gibt den Typ der Kategorienachse an. Lesen/Schreiben [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Stellt den Punkt auf der Achse dar, an dem die senkrechte Achse sie schneidet. Lesen/Schreiben Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Stellt den CrossType auf der angegebenen Achse dar, an dem die andere Achse schneidet. Lesen/Schreiben [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. Lesen/Schreiben [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Stellt das Format der Achse dar. Nur-Lesen [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Bestimmt, ob eine Achse einen sichtbaren Titel hat. Lesen/Schreiben Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. Lesen/Schreiben Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Gibt an, ob der Maximalwert automatisch zugewiesen wird. Lesen/Schreiben Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Gibt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. Lesen/Schreiben Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Gibt an, ob der Minimalwert automatisch zugewiesen wird. Lesen/Schreiben Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Gibt den automatischen Überlauf-Bin-Wert an. Wenn false: verwenden Sie die OverflowBin-Eigenschaft. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Gibt den automatischen Abstand zwischen Tick-Beschriftungen an. Wenn false: verwenden Sie die TickLabelSpacing-Eigenschaft. Lesen/Schreiben Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Gibt den automatischen Abstand zwischen Tick-Markierungen an. Wenn false: verwenden Sie die TickMarksSpacing-Eigenschaft. Lesen/Schreiben Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Gibt den automatischen Unterlauf-Bin-Wert an. Wenn false: verwenden Sie die UnderflowBin-Eigenschaft. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Gibt an, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. Lesen/Schreiben Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Gibt an, ob das Format mit Quelldaten verknüpft ist. Lesen/Schreiben Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Gibt an, ob ein Überlauf-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Überlauf-Bin-Wert anzupassen. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Gibt an, ob MS PowerPoint Datenpunkte von hinten nach vorne plottet. Lesen/Schreiben Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Gibt an, ob ein Unterlauf-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Unterlauf-Bin-Wert anzupassen. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Gibt an, ob die Achse sichtbar ist. Lesen/Schreiben Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Gibt den Abstand der Beschriftungen von der Achse an. Auf Kategorie- oder Datumsachse angewendet. Der Wert muss zwischen 0 % und 1000 % liegen. Lesen/Schreiben UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Stellt die logarithmische Basis dar. Standardwert ist 10. Lesen/Schreiben Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Stellt das Format der Hauptgitternetzlinien auf einer Diagrammachse dar. Nur-Lesen [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Stellt den Typ der Haupt-Tick-Markierung für die angegebene Achse dar. Lesen/Schreiben [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Stellt die Haupteinheiten für die Datums- oder Werteachse dar. Lesen/Schreiben Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Stellt die Skalierung der Haupteinheit für die Datumsachse dar. Lesen/Schreiben [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Stellt den Maximalwert auf der Werteachse dar. Lesen/Schreiben Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Stellt das Format der Nebengitternetzlinien auf einer Diagrammachse dar. Nur-Lesen [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Stellt den Typ der Neben-Tick-Markierung für die angegebene Achse dar. Lesen/Schreiben [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Stellt die Nebeneinheiten für die Datums- oder Werteachse dar. Lesen/Schreiben Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Stellt die Skalierung der Haupteinheit für die Datumsachse dar. Lesen/Schreiben [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Stellt den Minimalwert auf der Werteachse dar. Lesen/Schreiben Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Stellt die Formatzeichenkette für die Achsen-Beschriftungen dar. Lesen/Schreiben String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Gibt die Anzahl der Bins an, wenn der AggregationType-Eigenschaftswert auf AxisAggregationType.ByNumberOfBins gesetzt ist. Auf Kategorienachsen angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Gibt den benutzerdefinierten Wert des Überlauf-Bins an. Wird angewendet, wenn IsAutomaticOverflowBin false ist und IsOverflowBin true ist. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Stellt die Position der Achse dar. Lesen/Schreiben [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Gibt an, ob die Hauptgitternetzlinien angezeigt werden. Nur-Lesen Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Gibt an, ob die Nebengitternetzlinien angezeigt werden. Nur-Lesen Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Stellt die Position der Tick-Beschriftungen auf der angegebenen Achse dar. Lesen/Schreiben [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Stellt den Rotationswinkel der Tick-Beschriftungen dar. Lesen/Schreiben Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Gibt an, wie viele Tick-Beschriftungen zwischen gezeichneten Beschriftungen übersprungen werden. Lesen/Schreiben UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Gibt an, wie viele Tick-Markierungen übersprungen werden sollen, bevor die nächste gezeichnet wird. Auf Kategorie- oder Serienachse angewendet. Lesen/Schreiben UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Liefert den Titel der Achse. Nur-Lesen [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Gibt den benutzerdefinierten Wert des Unterlauf-Bins an. Wird angewendet, wenn IsAutomaticUnderflowBin false ist und IsUnderflowBin true ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Setzt die IAxis.CategoryAxisType-Eigenschaft mit einem Wert, der automatisch anhand der Achsendaten bestimmt wird. |

### Siehe Auch

* Schnittstelle [IFormattedTextContainer](../iformattedtextcontainer)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->