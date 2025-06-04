---
title: ChartDataPoint
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt Punktdaten einer Serie dar.
type: docs
weight: 1250
url: /de/aspose.slides.charts/chartdatapoint/
---

## ChartDataPoint-Klasse

Stellt Punktdaten einer Serie dar.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, um tatsächliche Werte zu erhalten. Einzelwert lesen. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, um tatsächliche Werte zu erhalten. Einzelwert lesen. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, um tatsächliche Werte zu erhalten. Einzelwert lesen. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Gibt die tatsächliche Oberkante des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie die Methode IChart.ValidateChartLayout() auf, um tatsächliche Werte zu erhalten. Einzelwert lesen. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Nur-Lese [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Gibt den Farbwert des Diagramm-Datenpunkts zurück. Wird mit Karten-Diagrammen verwendet. Nur-Lese [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Gibt den Container für Datenpunktstufen zurück. Gilt für Treeamp- und Sunburst-Serien. Die Indizierung der Datenpunktstufen erfolgt nullbasiert. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Stellt die Werte der Fehlerbalken der Serie im Falle von benutzerdefinierter Wertart dar. Nur-Lese [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Gibt an, wie weit der Datenpunkt vom Zentrum des Tortendiagramms verschoben werden soll. Lese-/Schreib-Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Stellt die Formatierungs Eigenschaften dar. Lese-/Schreib [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Gibt an, dass der Datenpunkt seine Farben umkehren soll, wenn der Wert negativ ist. Lese-/Schreib-Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Gibt an, dass auf die Blasen ein 3D-Effekt angewendet wird. Lese-/Schreib-Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Beschriftung. Nur-Lese [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Gibt einen Datenmarker an. Nur-Lese [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Eigenschaften des entsprechenden Legendeintrags im Falle von Diagrammtypen aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Nur-Lese [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Setzt den Datenpunkt als Gesamtwert. Gilt nur für den Serie-Typ Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Gibt den Größenwert des Diagramm-Datenpunkts zurück. Wird mit Treemap- und Sunburst-Diagrammen verwendet. Nur-Lese [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Wert. Nur-Lese [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Nur-Lese [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Nur-Lese [`IDoubleChartValue`](../idoublechartvalue). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Gibt eine automatische Farbe des Datenpunkts basierend auf dem Serienindex, dem Datenpunktindex, der Eigenschaft ParentSeriesGroup.IsColorVaried und dem Diagrammstil zurück. Diese Farbe wird standardmäßig verwendet, wenn FillType Unbestimmt ist. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Entfernt den Datenpunkt aus der Diagrammserie. |

### Siehe auch

* interface [IChartDataPoint](../ichartdatapoint)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->