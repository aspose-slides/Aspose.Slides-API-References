---
title: IAxis
second_title: Aspose.Slides für .NET API Referenz
description: Kapselt das Objekt, das die Achse eines Diagramms darstellt.
type: docs
weight: 1630
url: /de/aspose.slides.charts/iaxis/
---

## IAxis-Schnittstelle

Kapselt das Objekt, das die Achse eines Diagramms darstellt.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Gibt die tatsächliche Haupt Einheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Gibt die tatsächliche Haupt Einheitsskala der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Gibt den tatsächlichen maximalen Wert auf der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Gibt die tatsächliche Neben Einheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Gibt die tatsächliche Neben Einheitsskala der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Gibt den tatsächlichen minimalen Wert auf der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Stellt den Aggregationstyp der Kategoriemetrik dar (Binning). Wird auf Kategorien angewendet. Nur mit Histogramm oder HistogrammPareto-Datenreihen verwendet. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Ermöglicht den Zugriff auf die Basis-IFormattedTextContainer-Schnittstelle. Nur-Lese [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Gibt an, ob die Wertachse die Kategorieachse zwischen den Kategorien durchquert. Diese Eigenschaft gilt nur für Kategoriemetriken und nicht für 3D-Diagramme. Lese-/Schreib-Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Lese-/Schreib [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Gibt die Binnbreite an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByBinWidth eingestellt ist. Wird auf Kategoriemetriken angewendet. Nur mit Histogramm oder HistogrammPareto-Datenreihen verwendet. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Gibt den Typ der Kategorieachse an. Lese-/Schreib [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Gibt den Punkt auf der Achse an, an dem die senkrechte Achse sie schneidet. Lese-/Schreib-Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Stellt den CrossType auf der angegebenen Achse dar, wo die andere Achse sie schneidet. Lese-/Schreib [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Gibt den Skalierungswert der Anzeigeeinheiten für die Wertachse an. Lese-/Schreib [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Stellt das Format der Achse dar. Nur-Lese [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Bestimmt, ob eine Achse einen sichtbaren Titel hat. Lese-/Schreib-Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Gibt an, ob die Haupt Einheit der Achse automatisch zugewiesen wird. Lese-/Schreib-Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Gibt an, ob der Maximalwert automatisch zugewiesen wird. Lese-/Schreib-Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Gibt an, ob die Neben Einheit der Achse automatisch zugewiesen wird. Lese-/Schreib-Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Gibt an, ob der Minimalwert automatisch zugewiesen wird. Lese-/Schreib-Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Gibt den automatischen Überlauf-Bin-Wert an. Wenn false: verwenden Sie die OverflowBin-Eigenschaft. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Gibt den automatischen Abstand der Tick-Labels an. Wenn false: verwenden Sie die TickLabelSpacing-Eigenschaft. Lese-/Schreib-Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Gibt den automatischen Abstand der Tick-Marken an. Wenn false: verwenden Sie die TickMarksSpacing-Eigenschaft. Lese-/Schreib-Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Gibt den automatischen Unterlauf-Bin-Wert an. Wenn false: verwenden Sie die UnderflowBin-Eigenschaft. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Gibt an, ob der Skalierungstyp der Wertachse logarithmisch ist oder nicht. Lese-/Schreib-Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Gibt an, ob das Format mit den Quelldaten verknüpft ist. Lese-/Schreib-Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Gibt an, ob der Überlauf-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Überlauf-Bin-Wert anzupassen. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Gibt an, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst plant. Lese-/Schreib-Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Gibt an, ob der Unterlauf-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Unterlauf-Bin-Wert anzupassen. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Gibt an, ob die Achse sichtbar ist. Lese-/Schreib-Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Gibt den Abstand der Labels von der Achse an. Wird auf Kategorien oder Datumachsen angewendet. Der Wert muss zwischen 0 % und 1000 % liegen. Lese-/Schreib-UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Stellt die logarithmische Basis dar. Der Standardwert ist 10. Lese-/Schreib-Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Stellt das Format der Hauptgitterlinien auf einer Diagrammachse dar. Nur-Lese [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Stellt den Typ der Haupt-Tickmark für die angegebene Achse dar. Lese-/Schreib [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Stellt die Haupt-Einheiten für die Daten- oder Wertachse dar. Lese-/Schreib-Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Stellt die Haupt Einheitsskala für die Datumsachse dar. Lese-/Schreib [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Stellt den maximalen Wert auf der Wertachse dar. Lese-/Schreib-Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Stellt das Format der Neben-Gitterlinien auf einer Diagrammachse dar. Nur-Lese [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Stellt den Typ der Neben-Tickmark für die angegebene Achse dar. Lese-/Schreib [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Stellt die Neben-Einheiten für die Daten- oder Wertachse dar. Lese-/Schreib-Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Stellt die Haupt Einheitsskala für die Datumsachse dar. Lese-/Schreib [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Stellt den minimalen Wert auf der Wertachse dar. Lese-/Schreib-Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Stellt die Formatzeichenfolge für die Achsenbeschriftungen dar. Lese-/Schreib-String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Gibt die Anzahl der Bins an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByNumberOfBins eingestellt ist. Wird auf Kategoriemetriken angewendet. Nur mit Histogramm oder HistogrammPareto-Datenreihen verwendet. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Gibt den benutzerdefinierten Wert für den Überlauf-Bin an. Wird angewendet, wenn die Eigenschaft IsAutomaticOverflowBin auf false eingestellt ist und die Eigenschaft IsOverflowBin gleich true ist. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Stellt die Position der Achse dar. Lese-/Schreib [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Gibt an, ob die Hauptgitterlinien angezeigt werden. Nur-Lese Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Gibt an, ob die Nebengitterlinien angezeigt werden. Nur-Lese Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Gibt die Position der Tickmark-Labels auf der angegebenen Achse an. Lese-/Schreib [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Stellt den Rotationswinkel der Tick-Labels dar. Lese-/Schreib-Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Gibt an, wie viele Tick-Labels zwischen den gezeichneten Labels übersprungen werden sollen. Lese-/Schreib-UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Gibt an, wie viele Tick-Marken übersprungen werden sollen, bevor die nächste gezeichnet wird. Wird auf Kategorien oder Serienachsen angewendet. Lese-/Schreib-UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Gibt den Titel der Achse zurück. Nur-Lese [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Gibt den benutzerdefinierten Wert für den Unterlauf-Bin an. Wird angewendet, wenn die Eigenschaft IsAutomaticUnderflowBin auf false eingestellt ist und die Eigenschaft IsUnderflowBin gleich true ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Setzt die IAxis.CategoryAxisType-Eigenschaft mit einem Wert, der automatisch basierend auf den Achsendaten bestimmt wird. |

### Siehe auch

* Schnittstelle [IFormattedTextContainer](../iformattedtextcontainer)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->