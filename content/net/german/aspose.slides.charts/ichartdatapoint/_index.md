---
title: IChartDataPoint
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt einen Datenpunkt einer Serie dar.
type: docs
weight: 1840
url: /de/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint Schnittstelle

Stellt einen Datenpunkt einer Serie dar.

```csharp
public interface IChartDataPoint : IActualLayout
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | Gibt die IActualLayout Schnittstelle zurück. |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | Ruft die Blasengröße eines Diagrammdatenpunkts ab. Nur lesbar [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/ichartdatapoint/cachedbubblesize) { get; } | Ruft die zwischengespeicherte Blasengröße eines Diagrammdatenpunkts ab. Nur lesbar [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/ichartdatapoint/cachedvalue) { get; } | Ruft den zwischengespeicherten Wert eines Diagrammdatenpunkts ab. Nur lesbar [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/ichartdatapoint/cachedxvalue) { get; } | Ruft den zwischengespeicherten X-Wert eines Diagrammdatenpunkts ab. Nur lesbar [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/ichartdatapoint/cachedyvalue) { get; } | Ruft den zwischengespeicherten Y-Wert eines Diagrammdatenpunkts ab. Nur lesbar [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | Ruft den Farbwert eines Diagrammdatenpunkts ab. Wird mit Map charts verwendet. Nur lesbar [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | Gibt den Container der Datenpunkt-Ebenen zurück. Wird für Treeamp und Sunburst Serien verwendet. Die Indizierung der Datenpunkt-Ebenen ist nullbasiert. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | Stellt die Fehlerbalken-Werte der Serie im Fall des Custom Werttyps dar. Nur lesbar [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | Gibt die Menge an, um die der Datenpunkt vom Mittelpunkt des Kreisdiagramms verschoben werden soll. Lesbar/Schreibbar Int32. |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | Stellt die Formatierungseigenschaften dar. Lesbar/Schreibbar [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | Bestimmt, auf welche Kindersammlung des Elternteils dieser Datenpunkt angewendet wird. Lesbar UInt32. |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | Gibt an, dass der Datenpunkt seine Farben invertiert, wenn der Wert negativ ist. Lesbar/Schreibbar Boolean. |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | Gibt an, dass die Blasen einen 3-D-Effekt erhalten. Lesbar/Schreibbar Boolean. |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | Stellt das Etikett des Diagrammdatenpunkts dar. Nur lesbar [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | Gibt einen Datenmarker an. Nur lesbar [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | Eigenschaften des entsprechenden Legendeintrags im Fall des Diagrammtyps aus dieser Liste: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Nur lesbar [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | Setzt den Datenpunkt als Gesamtwert. Wird ausschließlich für Waterfall Serien verwendet. |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | Ruft den Größenwert eines Diagrammdatenpunkts ab. Wird mit Treemap und Sunburst Charts verwendet. Nur lesbar [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | Ruft den Wert eines Diagrammdatenpunkts ab. Nur lesbar [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | Ruft den x-Wert eines Diagrammdatenpunkts ab. Nur lesbar [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | Ruft den y-Wert eines Diagrammdatenpunkts ab. Nur lesbar [`IDoubleChartValue`](../idoublechartvalue). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | Gibt eine automatische Farbe des Datenpunkts zurück, basierend auf dem Serienindex, dem Datenpunktindex, der Eigenschaft ParentSeriesGroup.IsColorVaried und dem Diagrammstil. Diese Farbe wird standardmäßig verwendet, wenn FillType gleich NotDefined ist. |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | Entfernt den DataPoint aus der Diagrammserie. |

### Siehe auch

* Schnittstelle [IActualLayout](../iactuallayout)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->