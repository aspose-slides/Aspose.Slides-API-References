---
title: ChartDataPoint
second_title: Aspose.Slides für .NET API Referenz
description: Repräsentiert einen Datenpunkt in einer Serie.
type: docs
weight: 1250
url: /de/aspose.slides.charts/chartdatapoint/
---

## ChartDataPoint-Klasse

Repräsentiert einen Datenpunkt in einer Serie.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Lese Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Lese Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur oberen linken Ecke des Diagramms an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Lese Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Gibt die tatsächliche obere Position des Diagrammelements relativ zur oberen linken Ecke des Diagramms an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. Lese Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Nur-Lese [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Gibt den Farbwert des Diagrammdatenpunkts zurück. Wird mit Karten-Diagrammen verwendet. Nur-Lese [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Gibt den Container der Datenpunkt-Ebenen zurück. Anwendbar auf Treeamp und Sunburst-Serien. Die Indizierung der Datenpunkt-Ebenen ist nullbasiert. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Stellt die Werte der Fehlerbalken der Serie im Falle des benutzerdefinierten Wertetyps dar. Nur-Lese [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Gibt an, um wie viel der Datenpunkt vom Mittelpunkt des Kuchendiagramms verschoben werden soll. Lese/Schreibe Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Stellt die Formatierungseigenschaften dar. Lese/Schreibe [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Gibt an, dass der Datenpunkt seine Farben invertieren soll, wenn der Wert negativ ist. Lese/Schreibe Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Gibt an, dass die Blasen einen 3D-Effekt haben. Lese/Schreibe Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Etikett. Nur-Lese [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Gibt einen Datenmarker an. Nur-Lese [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Eigenschaften des entsprechenden Legendeneintrags im Falle von Diagrammtypen aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Nur-Lese [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Setzt den Datenpunkt als Gesamtwert. Nur anwendbar für den Typ Waterfall-Serie. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Gibt den Größenwert des Diagrammdatenpunkts zurück. Wird mit Treemap- und Sunburst-Diagrammen verwendet. Nur-Lese [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Wert. Nur-Lese [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Nur-Lese [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Nur-Lese [`IDoubleChartValue`](../idoublechartvalue). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Gibt eine automatische Farbe des Datenpunkts basierend auf dem Serienindex, dem Datenpunktindex, der ParentSeriesGroup.IsColorVaried-Eigenschaft und dem Diagrammstil zurück. Diese Farbe wird standardmäßig verwendet, wenn FillType gleich NotDefined ist. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Entfernt den Datenpunkt aus der Diagrammreihe. |

### Siehe auch

* Schnittstelle [IChartDataPoint](../ichartdatapoint)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->