---
title: Axis
second_title: Aspose.Slides für .NET API Referenz
description: Kapselt das Objekt, das eine Achse eines Diagramms darstellt.
type: docs
weight: 1100
url: /de/aspose.slides.charts/axis/
---

## Axis-Klasse

Kapselt das Objekt, das eine Achse eines Diagramms darstellt.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Gibt die tatsächliche Hauptgröße der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Gibt die tatsächliche Hauptgrößenskala der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Gibt den tatsächlichen maximalen Wert auf der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Gibt die tatsächliche kleinere Einheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Gibt die tatsächliche kleinere Einheitsskala der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Gibt den tatsächlichen minimalen Wert auf der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Repräsentiert den Aggregationstyp der Kategoriemachse (Binning). Anwendbar auf Kategorien. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Repräsentiert, ob die Wertachse die Kategoriemachse zwischen den Kategorien schneidet. Diese Eigenschaft gilt nur für Kategoriemachen und nicht für 3D-Diagramme. Lese-/schreibbares Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Lese-/schreibbar [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Gibt die Breite der Bins an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByBinWidth gesetzt ist. Anwendbar auf Kategoriemachen. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Gibt den Typ der Kategoriemachse an. Lese-/schreibbar [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Gibt das übergeordnete Diagramm zurück. Nur lesbar [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Repräsentiert den Punkt auf der Achse, an dem die senkrechte Achse sie schneidet. Lese-/schreibbares Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Repräsentiert den CrossType auf der angegebenen Achse, wo die andere Achse kreuzt. Lese-/schreibbar [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Gibt den Skalierungswert der Anzeigeeinheiten für die Wertachse an. Lese-/schreibbar [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Repräsentiert das Format der Achse. Nur lesbar [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Bestimmt, ob eine Achse einen sichtbaren Titel hat. Lese-/schreibbares Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Gibt an, ob die Hauptgröße der Achse automatisch zugewiesen wird. Lese-/schreibbares Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Gibt an, ob der max Wert automatisch zugewiesen wird. Lese-/schreibbares Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Gibt an, ob die kleinere Einheit der Achse automatisch zugewiesen wird. Lese-/schreibbares Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Gibt an, ob der min Wert automatisch zugewiesen wird. Lese-/schreibbares Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Gibt den automatischen Überlaufbin-Wert an. Wenn false: verwenden Sie die OverflowBin-Eigenschaft. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Gibt den automatischen Abstand der Tick-Labels an. Wenn false: verwenden Sie die TickLabelSpacing-Eigenschaft. Lese-/schreibbares Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Gibt den automatischen Abstand der Tick-Markierungen an. Wenn false: verwenden Sie die TickMarksSpacing-Eigenschaft. Lese-/schreibbares Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Gibt den automatischen Unterlauf-Bin-Wert an. Wenn false: verwenden Sie die UnderflowBin-Eigenschaft. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Gibt an, ob der Wertachsentyp logarithmisch ist oder nicht. Lese-/schreibbares Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Gibt an, ob das Format mit Quelldaten verknüpft ist. Lese-/schreibbares Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Gibt an, ob der Überlauf-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Überlauf-Bin-Wert anzupassen. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Gibt an, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst darstellt. Lese-/schreibbares Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Gibt an, ob der Unterlauf-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Unterlauf-Bin-Wert anzupassen. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Gibt an, ob die Achse sichtbar ist. Lese-/schreibbares Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Gibt den Abstand der Beschriftungen von der Achse an. Anwendbar auf die Kategorie- oder Datumsachse. Der Wert muss zwischen 0 % und 1000 % liegen. Lese-/schreibbares UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Repräsentiert die logarithmische Basis. Der Standardwert ist 10. Lese-/schreibbares Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Repräsentiert das Format der Hauptgitterlinien auf einer Diagrammachse. Nur lesbar [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Repräsentiert den Typ der Haupttickmarke für die angegebene Achse. Lese-/schreibbar [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Repräsentiert die Hauptgrößen für die Daten- oder Wertachse. Lese-/schreibbares Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Repräsentiert die Hauptgrößenskala für die Datumsachse. Lese-/schreibbar [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Repräsentiert den maximalen Wert auf der Wertachse. Lese-/schreibbares Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Repräsentiert das Format der kleineren Gitterlinien auf einer Diagrammachse. Nur lesbar [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Repräsentiert den Typ der kleinen Tickmarke für die angegebene Achse. Lese-/schreibbar [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Repräsentiert die kleinen Einheiten für die Daten- oder Wertachse. Lese-/schreibbares Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Repräsentiert die Hauptgrößenskala für die Datumsachse. Lese-/schreibbar [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Repräsentiert den minimalen Wert auf der Wertachse. Lese-/schreibbares Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Repräsentiert die Formatzeichenfolge für die Achsenbeschriftungen. Lese-/schreibbare Zeichenfolge. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Gibt die Anzahl der Bins an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByNumberOfBins gesetzt ist. Anwendbar auf Kategoriemachen. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Gibt den benutzerdefinierten Wert des Überlauf-Bins an. Wird angewendet, wenn die Eigenschaft IsAutomaticOverflowBin auf false gesetzt ist und die Eigenschaft IsOverflowBin den Wert true hat. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Repräsentiert die Position der Achse. Lese-/schreibbar [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Um die Hauptgitterlinie zu verstecken, setzen Sie MajorGridLinesFormat.Line.FillFormat.FillType auf FillType.NoFill. Nur lesbar Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Um die kleinen Gitterlinien zu verstecken, setzen Sie MinorGridLinesFormat.Line.FillFormat.FillType auf FillType.NoFill. Nur lesbar Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Repräsentiert das Format des Textes. Nur lesbar [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Repräsentiert die Position der Tick-Markierungsbeschriftungen auf der angegebenen Achse. Lese-/schreibbar [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Repräsentiert den Drehwinkel der Tick-Beschriftungen. Lese-/schreibbares Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Gibt an, wie viele Tick-Beschriftungen zwischen den gezeichneten Beschriftungen übersprungen werden. Anwendbar auf Kategorie- oder Serienachsen. Lese-/schreibbares UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Gibt an, wie viele Tick-Markierungen übersprungen werden, bevor die nächste gezeichnet wird. Anwendbar auf Kategorie- oder Serienachsen. Lese-/schreibbares UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Gibt den Titel der Achse zurück. Nur lesbar [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Gibt den benutzerdefinierten Wert des Unterlauf-Bins an. Wird angewendet, wenn die IsAutomaticUnderflowBin-Eigenschaft auf false gesetzt ist und die IsUnderflowBin-Eigenschaft den Wert true hat. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Setzt die IAxis.CategoryAxisType-Eigenschaft mit einem Wert, der automatisch basierend auf den Achsendaten bestimmt wird. |

### Siehe auch

* Klasse [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* Klasse [AxesManager](../axesmanager)
* Schnittstelle [IAxis](../iaxis)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->