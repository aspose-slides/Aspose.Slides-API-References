---
title: ChartDataPoint
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt einen Datenpunkt der Serie dar.
type: docs
weight: 1330
url: /de/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint Klasse

Stellt einen Datenpunkt der Serie dar.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() vorher auf, um die tatsächlichen Werte zu erhalten. Nur lesen Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie die Methode IChart.ValidateChartLayout() vorher auf, um die tatsächlichen Werte zu erhalten. Nur lesen Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie die Methode IChart.ValidateChartLayout() vorher auf, um die tatsächlichen Werte zu erhalten. Nur lesen Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Gibt die tatsächliche obere Position des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie die Methode IChart.ValidateChartLayout() vorher auf, um die tatsächlichen Werte zu erhalten. Nur lesen Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Nur lesend [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Gibt den Farbwert des Diagrammdatenpunkts zurück. Wird mit Map charts verwendet. Nur lesend [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Gibt den Container der Datenpunktebenen zurück. Wird für Treeamp- und Sunburst-Serien angewendet. Die Indizierung der Datenpunktebenen beginnt bei null. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Stellt die Werte der Fehlerbalken der Serie im Fall des benutzerdefinierten Wertetyps dar. Nur lesend [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Gibt die Menge an, um die der Datenpunkt vom Zentrum des Kuchendiagramms verschoben wird. Lesen/Schreiben Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Stellt die Formatierungseigenschaften dar. Lesen/Schreiben [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Gibt an, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist. Lesen/Schreiben Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Gibt an, dass die Blasen einen 3D-Effekt erhalten. Lesen/Schreiben Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Nur lesend [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Gibt einen Datenmarker an. Nur lesend [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Eigenschaften des entsprechenden Legendeeintrags im Fall von Diagrammtypen aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Nur lesend [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Setzt den Datenpunkt als Gesamtsumme. Wird nur für Waterfall series type only angewendet. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Gibt den Größenwert des Diagrammdatenpunkts zurück. Wird mit Treemap- und Sunburst-Diagrammen verwendet. Nur lesend [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. Nur lesend [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Nur lesend [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Nur lesend [`IDoubleChartValue`](../idoublechartvalue). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Gibt eine automatische Farbe des Datenpunkts zurück, basierend auf dem Serienindex, dem Datenpunktindex, der Eigenschaft ParentSeriesGroup.IsColorVaried und dem Diagrammstil. Diese Farbe wird standardmäßig verwendet, wenn FillType gleich NotDefined ist. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Entfernt DataPoint aus der Diagrammserie. |

### Siehe auch

* Schnittstelle [IChartDataPoint](../ichartdatapoint)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->