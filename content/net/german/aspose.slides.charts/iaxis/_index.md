---
title: IAxis
second_title: Aspose.Sildes für .NET API-Referenz
description: Kapselt das Objekt, das die Achse eines Diagramms darstellt.
type: docs
weight: 1720
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
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Gibt den tatsächlichen Maßstab der Haupteinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Gibt den tatsächlichen Maximalwert auf der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Gibt die tatsächliche Nebeneinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Gibt den tatsächlichen Maßstab der Nebeneinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Gibt den tatsächlichen Minimalwert auf der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Stellt den Aggregationstyp der Kategorieachse (Binning) dar. Auf Kategorie angewendet. Nur mit Histogram oder HistogramPareto Serien verwendet. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Ermöglicht das Abrufen der Basisschnittstelle IFormattedTextContainer. Nur lesbar [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Gibt an, ob die Werteachse die Kategorieachse zwischen den Kategorien schneidet. Diese Eigenschaft gilt nur für Kategorieachsen und nicht für 3-D-Diagramme. Lese-/Schreib-Zugriff Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Lese-/Schreib-Zugriff [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Gibt die Bin-Breite an, wenn der AggregationType-Eigenschaftswert auf AxisAggregationType.ByBinWidth gesetzt ist. Auf Kategorieachsen angewendet. Nur mit Histogram oder HistogramPareto Serien verwendet. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Gibt den Typ der Kategorieachse an. Lese-/Schreib-Zugriff [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Stellt den Punkt auf der Achse dar, an dem die senkrechte Achse sie schneidet. Lese-/Schreib-Zugriff Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Stellt den CrossType auf der angegebenen Achse dar, an dem die andere Achse kreuzt. Lese-/Schreib-Zugriff [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. Lese-/Schreib-Zugriff [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Stellt das Format der Achse dar. Nur lesbar [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Bestimmt, ob eine Achse einen sichtbaren Titel hat. Lese-/Schreib-Zugriff Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. Lese-/Schreib-Zugriff Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Gibt an, ob der Maximalwert automatisch zugewiesen wird. Lese-/Schreib-Zugriff Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Gibt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. Lese-/Schreib-Zugriff Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Gibt an, ob der Minimalwert automatisch zugewiesen wird. Lese-/Schreib-Zugriff Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Gibt den automatischen Überlauf-Bin-Wert an. Wenn false: verwenden Sie die OverflowBin-Eigenschaft. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Gibt den automatischen Abstand der Tick-Beschriftungen an. Wenn false: verwenden Sie die TickLabelSpacing-Eigenschaft. Lese-/Schreib-Zugriff Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Gibt den automatischen Abstand der Tick-Markierungen an. Wenn false: verwenden Sie die TickMarksSpacing-Eigenschaft. Lese-/Schreib-Zugriff Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Gibt den automatischen Unterlauf-Bin-Wert an. Wenn false: verwenden Sie die UnderflowBin-Eigenschaft. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Stellt dar, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. Lese-/Schreib-Zugriff Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Gibt an, ob das Format mit Quelldaten verknüpft ist. Lese-/Schreib-Zugriff Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Gibt an, ob der Überlauf-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Überlauf-Bin-Wert anzupassen. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Stellt dar, ob MS PowerPoint Datenpunkte von letzter zu erster plottet. Lese-/Schreib-Zugriff Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Gibt an, ob der Unterlauf-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Unterlauf-Bin-Wert anzupassen. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Stellt dar, ob die Achse sichtbar ist. Lese-/Schreib-Zugriff Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Gibt den Abstand der Beschriftungen von der Achse an. Auf Kategorie- oder Datumsachse angewendet. Der Wert muss zwischen 0 % und 1000 % liegen. Lese-/Schreib-Zugriff UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Stellt die logarithmische Basis dar. Standardwert ist 10. Lese-/Schreib-Zugriff Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Stellt das Format der Hauptgitternetzlinien auf einer Diagrammachse dar. Nur lesbar [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Stellt den Typ der Haupt-Tick-Markierung für die angegebene Achse dar. Lese-/Schreib-Zugriff [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Stellt die Haupteinheiten für die Datums- oder Werteachse dar. Lese-/Schreib-Zugriff Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Stellt den Maßstab der Haupteinheit für die Datumsachse dar. Lese-/Schreib-Zugriff [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Stellt den Maximalwert auf der Werteachse dar. Lese-/Schreib-Zugriff Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Stellt das Format der Nebengitternetzlinien auf einer Diagrammachse dar. Nur lesbar [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Stellt den Typ der Neben-Tick-Markierung für die angegebene Achse dar. Lese-/Schreib-Zugriff [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Stellt die Nebeneinheiten für die Datums- oder Werteachse dar. Lese-/Schreib-Zugriff Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Stellt den Maßstab der Haupteinheit für die Datumsachse dar. Lese-/Schreib-Zugriff [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Stellt den Minimalwert auf der Werteachse dar. Lese-/Schreib-Zugriff Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Stellt die Formatzeichenfolge für die Achsenbeschriftungen dar. Lese-/Schreib-Zugriff String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Gibt die Anzahl der Bins an, wenn der AggregationType-Eigenschaftswert auf AxisAggregationType.ByNumberOfBins gesetzt ist. Auf Kategorieachsen angewendet. Nur mit Histogram oder HistogramPareto Serien verwendet. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Gibt den benutzerdefinierten Wert für den Überlauf-Bin an. Wird angewendet, wenn IsAutomaticOverflowBin auf false gesetzt ist und IsOverflowBin true ist. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Stellt die Position der Achse dar. Lese-/Schreib-Zugriff [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Stellt dar, ob die Hauptgitternetzlinien angezeigt wurden. Nur lesbar Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Stellt dar, ob die Nebengitternetzlinien angezeigt wurden. Nur lesbar Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Stellt die Position der Tick-Marken-Beschriftungen auf der angegebenen Achse dar. Lese-/Schreib-Zugriff [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Stellt den Rotationswinkel der Tick-Beschriftungen dar. Lese-/Schreib-Zugriff Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Gibt an, wie viele Tick-Beschriftungen zwischen den gezeichneten Beschriftungen übersprungen werden sollen. Lese-/Schreib-Zugriff UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Gibt an, wie viele Tick-Markierungen übersprungen werden sollen, bevor die nächste gezeichnet wird. Auf Kategorie- oder Serienachse angewendet. Lese-/Schreib-Zugriff UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Liefert den Achsentitel. Nur lesbar [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Gibt den benutzerdefinierten Wert für den Unterlauf-Bin an. Wird angewendet, wenn IsAutomaticUnderflowBin auf false gesetzt ist und IsUnderflowBin true ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Setzt die Eigenschaft IAxis.CategoryAxisType mit einem Wert, der basierend auf den Achsendaten automatisch ermittelt wird. |

### Siehe auch

* Schnittstelle [IFormattedTextContainer](../iformattedtextcontainer)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->