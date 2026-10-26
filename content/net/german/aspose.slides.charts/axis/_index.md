---
title: Axis
second_title: Aspose.Sildes für .NET API-Referenz
description: Kapselt das Objekt, das die Achse eines Diagramms darstellt.
type: docs
weight: 1180
url: /de/aspose.slides.charts/axis/
---
## Axis-Klasse

Kapselt das Objekt, das die Achse eines Diagramms darstellt.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Gibt die tatsächliche Haupteinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Gibt die tatsächliche Skalierung der Haupteinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Gibt den tatsächlichen Maximalwert der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Gibt die tatsächliche Nebeneinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Gibt die tatsächliche Skalierung der Nebeneinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Gibt den tatsächlichen Minimalwert der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Stellt den Aggregationstyp der Kategorie-Achse (Binning) dar. Auf Kategorie angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Gibt an, ob die Wertachse die Kategorie-Achse zwischen den Kategorien schneidet. Diese Eigenschaft gilt nur für Kategorie-Achsen und nicht für 3-D-Diagramme. Lese-/Schreib-Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Lese-/Schreib [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Gibt die Bin-Breite an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByBinWidth gesetzt ist. Auf Kategorie-Achsen angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Gibt den Typ der Kategorie-Achse an. Lese-/Schreib [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Gibt das übergeordnete Diagramm zurück. Nur-Lese [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Stellt den Punkt auf der Achse dar, an dem die senkrechte Achse sie schneidet. Lese-/Schreib Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Stellt den CrossType auf der angegebenen Achse dar, an dem die andere Achse sie schneidet. Lese-/Schreib [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Gibt den Skalierungswert der Anzeigeeinheiten für die Wertachse an. Lese-/Schreib [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Stellt das Format der Achse dar. Nur-Lese [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Bestimmt, ob eine Achse einen sichtbaren Titel hat. Lese-/Schreib Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. Lese-/Schreib Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Gibt an, ob der Maximalwert automatisch zugewiesen wird. Lese-/Schreib Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Gibt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. Lese-/Schreib Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Gibt an, ob der Minimalwert automatisch zugewiesen wird. Lese-/Schreib Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Gibt den automatischen Überlauf-Bin-Wert an. Wenn false: verwenden Sie die Eigenschaft OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Gibt den automatischen Abstand der Tick-Beschriftungen an. Wenn false: verwenden Sie die Eigenschaft TickLabelSpacing. Lese-/Schreib Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Gibt den automatischen Abstand der Tick-Markierungen an. Wenn false: verwenden Sie die Eigenschaft TickMarksSpacing. Lese-/Schreib Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Gibt den automatischen Unterlauf-Bin-Wert an. Wenn false: verwenden Sie die Eigenschaft UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Gibt an, ob der Skalierungstyp der Wertachse logarithmisch ist oder nicht. Lese-/Schreib Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Gibt an, ob das Format mit Quelldaten verknüpft ist. Lese-/Schreib Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Gibt an, ob ein Überlauf-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Überlauf-Bin-Wert anzupassen. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Gibt an, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst zeichnet. Lese-/Schreib Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Gibt an, ob ein Unterlauf-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Unterlauf-Bin-Wert anzupassen. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Gibt an, ob die Achse sichtbar ist. Lese-/Schreib Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Gibt den Abstand der Beschriftungen von der Achse an. Auf Kategorie- oder Datumsachse angewendet. Der Wert muss zwischen 0 % und 1000 % liegen. Lese-/Schreib UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Stellt die logarithmische Basis dar. Standardwert ist 10. Lese-/Schreib Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Stellt das Format der Hauptgitternetzlinien einer Diagrammachse dar. Nur-Lese [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Stellt den Typ der Haupt-Tick-Markierung für die angegebene Achse dar. Lese-/Schreib [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Stellt die Haupteinheiten für die Datums- oder Wertachse dar. Lese-/Schreib Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Stellt die Skalierung der Haupteinheit für die Datumsachse dar. Lese-/Schreib [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Stellt den Maximalwert auf der Wertachse dar. Lese-/Schreib Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Stellt das Format der Nebengitternetzlinien einer Diagrammachse dar. Nur-Lese [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Stellt den Typ der Neben-Tick-Markierung für die angegebene Achse dar. Lese-/Schreib [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Stellt die Nebeneinheiten für die Datums- oder Wertachse dar. Lese-/Schreib Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Stellt die Skalierung der Haupteinheit für die Datumsachse dar. Lese-/Schreib [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Stellt den Minimalwert auf der Wertachse dar. Lese-/Schreib Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Stellt die Formatzeichenfolge für die Achsen-Beschriftungen dar. Lese-/Schreib String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Gibt die Anzahl der Bins an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByNumberOfBins gesetzt ist. Auf Kategorie-Achsen angewendet. Nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Gibt den benutzerdefinierten Wert des Überlauf-Bins an. Wird angewendet, wenn die Eigenschaft IsAutomaticOverflowBin auf false gesetzt ist und IsOverflowBin den Wert true hat. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Stellt die Position der Achse dar. Lese-/Schreib [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Um die Hauptgitternetzlinie auszublenden, setzen Sie MajorGridLinesFormat.Line.FillFormat.FillType auf FillType.NoFill. Nur-Lese Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Um die Nebengitternetzlinie auszublenden, setzen Sie MinorGridLinesFormat.Line.FillFormat.FillType auf FillType.NoFill. Nur-Lese Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Stellt das Textformat dar. Nur-Lese [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Stellt die Position der Tick-Mark-Beschriftungen auf der angegebenen Achse dar. Lese-/Schreib [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Stellt den Rotationswinkel der Tick-Beschriftungen dar. Lese-/Schreib Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Gibt an, wie viele Tick-Beschriftungen zwischen zwei dargestellten Beschriftungen übersprungen werden. Auf Kategorie- oder Serienachse angewendet. Lese-/Schreib UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Gibt an, wie viele Tick-Markierungen übersprungen werden, bevor die nächste gezeichnet wird. Auf Kategorie- oder Serienachse angewendet. Lese-/Schreib UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Liefert den Titel der Achse. Nur-Lese [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Gibt den benutzerdefinierten Wert des Unterlauf-Bins an. Wird angewendet, wenn die Eigenschaft IsAutomaticUnderflowBin auf false gesetzt ist und IsUnderflowBin den Wert true hat. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Setzt die Eigenschaft IAxis.CategoryAxisType auf einen Wert, der basierend auf den Achsendaten automatisch ermittelt wird. |

### Siehe auch

* Klasse [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* Klasse [AxesManager](../axesmanager)
* Schnittstelle [IAxis](../iaxis)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->