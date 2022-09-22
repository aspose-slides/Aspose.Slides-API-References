---
title: IAxis
second_title: Aspose.Slides für .NET-API-Referenz
description: Kapselt das Objekt das die Achse eines Diagramms darstellt.
type: docs
weight: 1590
url: /de/net/aspose.slides.charts/iaxis/
---
## IAxis interface

Kapselt das Objekt, das die Achse eines Diagramms darstellt.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Gibt die tatsächliche Haupteinheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Gibt die tatsächliche Haupteinheitsskala der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Gibt den tatsächlichen Maximalwert auf der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Gibt die tatsächliche Nebeneinheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Gibt die tatsächliche kleinere Einheitenskalierung der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Gibt den tatsächlichen Minimalwert auf der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Repräsentiert den Aggregationstyp der Kategorieachse (Binning). Auf Kategorie angewendet. Wird nur mit Histogram- oder HistogramPareto-Serien verwendet. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Ermöglicht das Abrufen der Basis-IFormattedTextContainer-Schnittstelle. Schreibgeschützt[`IFormattedTextContainer`](../iformattedtextcontainer) . |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Stellt dar, ob die Wertachse die Kategorieachse zwischen Kategorien schneidet. Diese Eigenschaft gilt nur für Kategorieachsen und nicht für 3D-Diagramme. Lesen/SchreibenBoolean . |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Lesen/Schreiben[`TimeUnitType`](../timeunittype) . |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Gibt die Bin-Breite an, wenn der AggregationType-Eigenschaftswert auf AxisAggregationType.ByBinWidth gesetzt ist. Auf Kategorieachsen angewendet. Wird nur mit Histogram- oder HistogramPareto-Serien verwendet. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Gibt den Typ der Kategorieachse an. Lesen/Schreiben[`CategoryAxisType`](./categoryaxistype) . |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Repräsentiert den Punkt auf der Achse, an dem die senkrechte Achse diese schneidet. Lesen/SchreibenSingle . |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Repräsentiert den CrossType auf der angegebenen Achse, wo die andere Achse kreuzt. Lesen/Schreiben[`CrossesType`](../crossestype) . |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Legt den Skalierungswert der Anzeigeeinheiten für die Wertachse fest. Lesen/Schreiben[`DisplayUnitType`](../displayunittype) . |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Repräsentiert das Format der Achse. Schreibgeschützt[`IAxisFormat`](../iaxisformat) . |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Bestimmt, ob eine Achse einen sichtbaren Titel hat. Lesen/SchreibenBoolean . |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. Lesen/SchreibenBoolean . |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Gibt an, ob der Maximalwert automatisch zugewiesen wird. Lesen/SchreibenBoolean . |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Gibt an, ob die Untereinheit der Achse automatisch zugewiesen wird. Lesen/SchreibenBoolean . |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Gibt an, ob der Min-Wert automatisch zugewiesen wird. Lesen/SchreibenBoolean . |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Gibt den Wert für den automatischen Überlaufbehälter an. Wenn falsch: OverflowBin-Eigenschaft verwenden. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Legt den automatischen Abstandswert für Teilstrichbeschriftungen fest. Wenn falsch: TickLabelSpacing-Eigenschaft verwenden. Lesen/SchreibenBoolean . |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Gibt den automatischen Abstandswert für Teilstriche an. Wenn falsch: TickMarksSpacing-Eigenschaft verwenden. Lesen/SchreibenBoolean . |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Gibt den automatischen Unterlauf-Bin-Wert an. Wenn falsch: UnderflowBin-Eigenschaft verwenden. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Stellt dar, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. Lesen/SchreibenBoolean . |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Gibt an, ob es sich bei dem Format um verknüpfte Quelldaten handelt. Lesen/SchreibenBoolean . |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Gibt an, ob ein Überlaufbehälter angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Wert des Überlaufbehälters anzupassen. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Stellt dar, ob MS PowerPoint Datenpunkte vom letzten zum ersten darstellt. Lesen/SchreibenBoolean . |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Gibt an, ob ein Unterlaufbehälter angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Unterlauf-Bin-Wert anzupassen. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Stellt dar, ob die Achse sichtbar ist. Lesen/SchreibenBoolean . |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Gibt den Abstand der Beschriftungen von der Achse an. Auf Kategorie- oder Datumsachse angewendet. Wert muss zwischen 0 % und 1000 % liegen. Lesen/SchreibenUInt16 . |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Repräsentiert die logarithmische Basis. Der Standardwert ist 10. Lesen/SchreibenDouble . |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Repräsentiert das Hauptgitternetzformat auf einer Diagrammachse. Schreibgeschützt[`IChartLinesFormat`](../ichartlinesformat) . |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Repräsentiert den Typ des Hauptteilstrichs für die angegebene Achse. Lesen/Schreiben[`TickMarkType`](../tickmarktype) . |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Repräsentiert die Haupteinheiten für die Datums- oder Werteachse. Lesen/SchreibenDouble . |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Repräsentiert die Haupteinheitsskala für die Datumsachse. Lesen/Schreiben[`TimeUnitType`](../timeunittype) . |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Stellt den Maximalwert auf der Werteachse dar. Lesen/SchreibenDouble . |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Repräsentiert das kleinere Gitterlinienformat auf einer Diagrammachse. Schreibgeschützt[`IChartLinesFormat`](../ichartlinesformat) . |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Repräsentiert den Typ des Nebenteilstrichs für die angegebene Achse. Lesen/Schreiben[`TickMarkType`](../tickmarktype) . |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Repräsentiert die kleineren Einheiten für die Datums- oder Werteachse. Lesen/SchreibenDouble . |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Repräsentiert die Haupteinheitsskala für die Datumsachse. Lesen/Schreiben[`TimeUnitType`](../timeunittype) . |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Stellt den Mindestwert auf der Werteachse dar. Lesen/SchreibenDouble . |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Repräsentiert die Formatzeichenfolge für die Achsenbeschriftungen. Lesen/SchreibenString . |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Gibt die Anzahl der Bins an, wenn der Eigenschaftswert AggregationType auf AxisAggregationType.ByNumberOfBins gesetzt ist. Auf Kategorieachsen angewendet. Wird nur mit Histogram- oder HistogramPareto-Serien verwendet. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Gibt den benutzerdefinierten Wert des Überlaufbehälters an. Wird angewendet, wenn die Eigenschaft „IsAutomaticOverflowBin“ auf „false“ gesetzt ist und die Eigenschaft „IsOverflowBin“ gleich „true“ ist. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Repräsentiert die Position der Achse. Lesen/Schreiben[`AxisPositionType`](../axispositiontype) . |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Stellt dar, ob die Hauptgitterlinien angezeigt wurden. SchreibgeschütztBoolean . |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Stellt dar, ob die Nebengitterlinien angezeigt wurden. SchreibgeschütztBoolean . |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Repräsentiert die Position von Teilstrichbeschriftungen auf der angegebenen Achse. Lesen/Schreiben[`TickLabelPositionType`](../ticklabelpositiontype) . |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Repräsentiert den Rotationswinkel von Tick-Labels Lesen/SchreibenSingle . |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Gibt an, wie viele Tick-Labels zwischen gezeichneten Labels übersprungen werden sollen. Lesen/SchreibenUInt32 . |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Gibt an, wie viele Teilstriche übersprungen werden sollen, bevor der nächste gezeichnet werden soll. Auf Kategorie- oder Serienachse angewendet. Lesen/SchreibenUInt16 . |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Ruft den Titel der Achse ab. Schreibgeschützt[`IChartTitle`](../icharttitle) . |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Gibt den benutzerdefinierten Wert des Unterlaufbehälters an. Wird angewendet, wenn die Eigenschaft „IsAutomaticUnderflowBin“ auf „false“ gesetzt ist und die Eigenschaft „IsUnderflowBin“ gleich „true“ ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Legt die Eigenschaft IAxis.CategoryAxisType mit einem Wert fest, der basierend auf den Achsendaten automatisch bestimmt wird. |

### Siehe auch

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
