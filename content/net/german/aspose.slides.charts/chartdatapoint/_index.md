---
title: ChartDataPoint
second_title: Aspose.Slides für .NET-API-Referenz
description: Repräsentiert Seriendatenpunkt.
type: docs
weight: 1210
url: /de/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint class

Repräsentiert Seriendatenpunkt.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Gibt die tatsächliche Höhe des Diagrammelements an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. LesenSingle . |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Gibt die tatsächliche Breite des Diagrammelements an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. LesenSingle . |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Gibt die tatsächliche x-Position (links) des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. LesenSingle . |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Gibt die tatsächliche Oberkante des Diagrammelements relativ zur linken oberen Ecke des Diagramms an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um die tatsächlichen Werte zu erhalten. LesenSingle . |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Schreibgeschützt[`IDoubleChartValue`](../idoublechartvalue) . |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Gibt den Farbwert des Diagrammdatenpunkts zurück. Wird mit Kartendiagrammen verwendet. Schreibgeschützt[`IDoubleChartValue`](../idoublechartvalue) . |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Gibt einen Container mit Datenpunktebenen zurück. Wird für die Serien Treeamp und Sunburst angewendet. Die Indizierung der Datenpunktebenen ist nullbasiert. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Repräsentiert Reihenfehlerbalkenwerte im Falle des benutzerdefinierten Werttyps. Schreibgeschützt[`IErrorBarsCustomValues`](../ierrorbarscustomvalues) . |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Gibt den Betrag an, um den der Datenpunkt von der Mitte des Kreises verschoben werden soll. Lesen/SchreibenInt32 . |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Repräsentiert die Formatierungseigenschaften. Lesen/Schreiben[`IFormat`](../iformat) . |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Gibt an, dass der Datenpunkt seine Farben invertieren soll, wenn der Wert negativ ist. Lesen/SchreibenBoolean . |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Gibt an, dass auf die Blasen ein 3D-Effekt angewendet wird. Lesen/SchreibenBoolean . |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Schreibgeschützt[`IDataLabel`](../idatalabel) . |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Gibt einen Datenmarker an. Schreibgeschützt[`IMarker`](../imarker) . |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Eigenschaften des entsprechenden Legendeneintrags bei Diagrammtypen aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Nur lesen[`ILegendEntryProperties`](../ilegendentryproperties) . |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Legt den Datenpunkt als Summe fest. Gilt nur für den Typ Wasserfallserie. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Gibt den Größenwert des Diagrammdatenpunkts zurück. Wird mit Treemap- und Sunburst-Diagrammen verwendet. Schreibgeschützt[`IDoubleChartValue`](../idoublechartvalue) . |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Wert. Schreibgeschützt[`IDoubleChartValue`](../idoublechartvalue) . |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Schreibgeschützt[`IStringOrDoubleChartValue`](../istringordoublechartvalue) . |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Schreibgeschützt[`IDoubleChartValue`](../idoublechartvalue) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Gibt eine automatische Farbe des Datenpunkts basierend auf dem Reihenindex, dem Datenpunktindex, der Eigenschaft ParentSeriesGroup.IsColorVaried und dem Diagrammstil zurück. Diese Farbe wird standardmäßig verwendet, wenn FillType gleich NotDefined ist. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Entfernt DataPoint aus Diagrammreihen. |

### Siehe auch

* interface [IChartDataPoint](../ichartdatapoint)
* namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
