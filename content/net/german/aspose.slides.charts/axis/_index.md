---
title: Axis
second_title: Aspose.Slides für .NET API Referenz
description: Kapselt das Objekt, das eine Achse eines Diagramms darstellt.
type: docs
weight: 1100
url: /de/aspose.slides.charts/axis/
---

## Achsenklasse

Kapselt das Objekt, das die Achse eines Diagramms darstellt.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Gibt die tatsächliche Hauptgröße der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Gibt die tatsächliche Hauptgrößenskala der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Gibt den tatsächlichen Maximalwert auf der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Gibt die tatsächliche Nebenmenge der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Gibt die tatsächliche Nebenmengenskala der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Gibt den tatsächlichen Minimalwert auf der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Stellt den Aggregationstyp der Kategoriemachse (Binning) dar. Wird für Kategorien angewendet. Nur bei Histogramm- oder HistogrammPareto-Serien verwendet. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Gibt an, ob die Werteachse die Kategoriensachse zwischen den Kategorien durchschneidet. Diese Eigenschaft gilt nur für Kategoriemachen und nicht für 3-D-Diagramme. Lese-/Schreib-Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Lese-/Schreib [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Gibt die Bin-Breite an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByBinWidth gesetzt ist. Wird für Kategoriemachen angewendet. Nur bei Histogramm- oder HistogrammPareto-Serien verwendet. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Gibt den Typ der Kategoriemachse an. Lese-/Schreib [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Gibt das übergeordnete Diagramm zurück. Nur lesend [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Stellt den Punkt auf der Achse dar, an dem die senkrechte Achse diese kreuzt. Lese-/Schreib-Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Stellt den CrossType auf der angegebenen Achse dar, wo die andere Achse kreuzt. Lese-/Schreib [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. Lese-/Schreib [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Stellt das Format der Achse dar. Nur lesend [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Bestimmt, ob eine Achse einen sichtbaren Titel hat. Lese-/Schreib-Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Gibt an, ob die Hauptmenge der Achse automatisch zugewiesen ist. Lese-/Schreib-Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Gibt an, ob der Maximalwert automatisch zugewiesen ist. Lese-/Schreib-Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Gibt an, ob die Nebenmenge der Achse automatisch zugewiesen ist. Lese-/Schreib-Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Gibt an, ob der Minimalwert automatisch zugewiesen ist. Lese-/Schreib-Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Gibt den automatischen Überlauf-Bin-Wert an. Wenn falsch: verwenden Sie die OverflowBin-Eigenschaft. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Gibt den automatischen Abstand der Tick-Labels an. Wenn falsch: verwenden Sie die TickLabelSpacing-Eigenschaft. Lese-/Schreib-Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Gibt den automatischen Abstand der Tick-Marken an. Wenn falsch: verwenden Sie die TickMarksSpacing-Eigenschaft. Lese-/Schreib-Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Gibt den automatischen Unterlauf-Bin-Wert an. Wenn falsch: verwenden Sie die UnderflowBin-Eigenschaft. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Stellt dar, ob der Skalentyp der Werteachse logarithmisch ist oder nicht. Lese-/Schreib-Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Gibt an, ob das Format mit den Quelldaten verknüpft ist. Lese-/Schreib-Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Gibt an, ob der Überlauf-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Wert des Überlauf-Bins anzupassen. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Stellt dar, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst anzeigt. Lese-/Schreib-Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Gibt an, ob der Unterlauf-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Wert des Unterlauf-Bins anzupassen. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Stellt dar, ob die Achse sichtbar ist. Lese-/Schreib-Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Gibt den Abstand der Beschriftungen von der Achse an. Wird für Kategorien- oder Datumsachsen angewendet. Der Wert muss zwischen 0 % und 1000 % liegen. Lese-/Schreib-UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Stellt die logarithmische Basis dar. Standardwert ist 10. Lese-/Schreib-Doppel. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Stellt das Format der Hauptgitterlinien auf einer Diagrammachse dar. Nur lesend [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Stellt den Typ des Haupt-Tick-Marks für die angegebene Achse dar. Lese-/Schreib [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Stellt die Haupt-Einheiten für die Daten- oder Werte-Achse dar. Lese-/Schreib-Doppel. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Stellt die Hauptgrößenskala für die Datumsachse dar. Lese-/Schreib [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Stellt den Maximalwert auf der Werteachse dar. Lese-/Schreib-Doppel. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Stellt das Format der Neben-Gitterlinien auf einer Diagrammachse dar. Nur lesend [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Stellt den Typ des Neben-Tick-Marks für die angegebene Achse dar. Lese-/Schreib [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Stellt die Neben-Einheiten für die Daten- oder Werte-Achse dar. Lese-/Schreib-Doppel. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Stellt die Hauptgrößenskala für die Datumsachse dar. Lese-/Schreib [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Stellt den Minimalwert auf der Werteachse dar. Lese-/Schreib-Doppel. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Stellt die Formatzeichenfolge für die Achsenbeschriftungen dar. Lese-/Schreib-Zeichenfolge. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Gibt die Anzahl der Bins an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByNumberOfBins gesetzt ist. Wird für Kategoriemachen angewendet. Nur bei Histogramm- oder HistogrammPareto-Serien verwendet. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Gibt den benutzerdefinierten Wert des Überlauf-Bins an. Wird angewendet, wenn die IsAutomaticOverflowBin-Eigenschaft auf false gesetzt ist und die IsOverflowBin-Eigenschaft true ist. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Stellt die Position der Achse dar. Lese-/Schreib [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Um die Hauptgitterlinie auszublenden, setzen Sie MajorGridLinesFormat.Line.FillFormat.FillType auf FillType.NoFill. Nur lesend Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Um die Neben-Gitterlinie auszublenden, setzen Sie MinorGridLinesFormat.Line.FillFormat.FillType auf FillType.NoFill. Nur lesend Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Stellt das Format von Text dar. Nur lesend [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Stellt die Position der Tick-Mark-Beschriftungen auf der angegebenen Achse dar. Lese-/Schreib [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Stellt den Rotationswinkel der Tick-Beschriftungen dar. Lese-/Schreib-Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Gibt an, wie viele Tick-Beschriftungen zwischen der zu zeichnenden Beschriftung übersprungen werden sollen. Wird für Kategorien oder Serienachsen angewendet. Lese-/Schreib-UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Gibt an, wie viele Tick-Markierungen übersprungen werden sollen, bevor die nächste gezeichnet werden soll. Wird für Kategorien oder Serienachsen angewendet. Lese-/Schreib-UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Gibt den Titel der Achse zurück. Nur lesend [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Gibt den benutzerdefinierten Wert des Unterlauf-Bins an. Wird angewendet, wenn die IsAutomaticUnderflowBin-Eigenschaft auf false gesetzt ist und die IsUnderflowBin-Eigenschaft true ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Setzt die IAxis.CategoryAxisType-Eigenschaft mit einem Wert, der basierend auf den Achsendaten automatisch bestimmt wird. |

### Siehe auch

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [AxesManager](../axesmanager)
* interface [IAxis](../iaxis)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->