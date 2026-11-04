---
title: ChartDataPoint
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt einen Datenpunkt einer Serie dar.
type: docs
weight: 1340
url: /de/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint Klasse

Stellt einen Datenpunkt einer Serie dar.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() vorher auf, um die tatsächlichen Werte zu erhalten. Lese Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() vorher auf, um die tatsächlichen Werte zu erhalten. Lese Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie die Methode IChart.ValidateChartLayout() vorher auf, um die tatsächlichen Werte zu erhalten. Lese Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie die Methode IChart.ValidateChartLayout() vorher auf, um die tatsächlichen Werte zu erhalten. Lese Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Nur lesbar [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/chartdatapoint/cachedbubblesize) { get; } | Gibt die zwischengespeicherte BubbleSize eines Diagrammdatenpunkts zurück. Nur lesbar [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/chartdatapoint/cachedvalue) { get; } | Gibt den zwischengespeicherten Wert eines Diagrammdatenpunkts zurück. Nur lesbar [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/chartdatapoint/cachedxvalue) { get; } | Gibt den zwischengespeicherten X-Wert eines Diagrammdatenpunkts zurück. Nur lesbar [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/chartdatapoint/cachedyvalue) { get; } | Gibt den zwischengespeicherten Y-Wert eines Diagrammdatenpunkts zurück. Nur lesbar [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Gibt den Farbwert des Diagrammdatenpunkts zurück. Wird bei Karten-Diagrammen verwendet. Nur lesbar [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Gibt den Container der Datenpunkt-Level zurück. Wird für Treeamp- und Sunburst-Serien verwendet. Die Indexierung der Datenpunkt-Level beginnt bei Null. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Stellt die Werte der Serien-Fehlerbalken im Fall des benutzerdefinierten Wertetyps dar. Nur lesbar [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Gibt an, um wie viel der Datenpunkt vom Mittelpunkt des Kuchens verschoben werden soll. Lesen/Schreiben Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Stellt die Formatierungseigenschaften dar. Lesen/Schreiben [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Gibt an, dass der Datenpunkt seine Farben invertieren soll, wenn der Wert negativ ist. Lesen/Schreiben Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Gibt an, dass die Bubbles einen 3-D-Effekt erhalten. Lesen/Schreiben Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Nur lesbar [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Gibt einen Datenmarker an. Nur lesbar [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Eigenschaften des entsprechenden Legendeintrags im Fall von Diagrammtypen aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Nur lesbar [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Legt den Datenpunkt als Gesamtwert fest. Wird ausschließlich für den Waterfall-Serientyp verwendet. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Gibt den Größenwert des Diagrammdatenpunkts zurück. Wird mit Treemap- und Sunburst-Diagrammen verwendet. Nur lesbar [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. Nur lesbar [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Nur lesbar [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Nur lesbar [`IDoubleChartValue`](../idoublechartvalue). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Gibt eine automatische Farbe des Datenpunkts zurück, basierend auf dem Serienindex, dem Datenpunktindex, der Eigenschaft ParentSeriesGroup.IsColorVaried und dem Diagrammstil. Diese Farbe wird standardmäßig verwendet, wenn FillType gleich NotDefined ist. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Entfernt den DataPoint aus der Diagrammserie. |

### Siehe auch

* Schnittstelle [IChartDataPoint](../ichartdatapoint)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->