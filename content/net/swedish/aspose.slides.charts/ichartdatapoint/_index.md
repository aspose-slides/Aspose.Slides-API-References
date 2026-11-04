---
title: IChartDataPoint
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en datapunkt i en serie.
type: docs
weight: 1840
url: /sv/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint gränssnitt

Representerar en serie datapunkt.

```csharp
public interface IChartDataPoint : IActualLayout
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | Returnerar gränssnittet IActualLayout. |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | Hämtar bubbelförstoringen för en diagramdatapunkt. Skrivskyddad [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/ichartdatapoint/cachedbubblesize) { get; } | Hämtar den cachade bubbelförstoringen för en diagramdatapunkt. Skrivskyddad [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/ichartdatapoint/cachedvalue) { get; } | Hämtar det cachade värdet för en diagramdatapunkt. Skrivskyddad [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/ichartdatapoint/cachedxvalue) { get; } | Hämtar det cachade X-värdet för en diagramdatapunkt. Skrivskyddad [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/ichartdatapoint/cachedyvalue) { get; } | Hämtar det cachade Y-värdet för en diagramdatapunkt. Skrivskyddad [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | Hämtar färgvärdet för en diagramdatapunkt. Används med kartdiagram. Skrivskyddad [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | Returnerar behållare för datapunktsnivåer. Tillämpas för Treeamp- och Sunburst-serier. Indexering av datapunktsnivåer är nollbaserad. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | Representerar seriens felstaplarvärden för anpassad värdetyp. Skrivskyddad [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | Anger hur mycket datapunkten ska flyttas från mitten av pajen. Läs/skriv Int32. |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | Representerar formaterings-egenskaperna. Läs/skriv [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | Bestämmer vilken av förälderns barnsamling denna datapunkt gäller för. Läs UInt32. |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | Anger att datapunkten ska invertera sina färger om värdet är negativt. Läs/skriv Boolean. |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | Anger att bubblorna har en 3-D-effekt tillämpad. Läs/skriv Boolean. |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | Representerar etiketten för diagramdatapunkten. Skrivskyddad [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | Anger en datamarkör. Skrivskyddad [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | Egenskaper för motsvarande legendpost för diagramtyperna i följande lista: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Skrivskyddad [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | Anger datapunkten som total. Endast tillämpad för Waterfall-serietyp. |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | Hämtar storleksvärdet för en diagramdatapunkt. Används med Treemap- och Sunburst-diagram. Skrivskyddad [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | Hämtar värdet för en diagramdatapunkt. Skrivskyddad [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | Hämtar x-värdet för en diagramdatapunkt. Skrivskyddad [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | Hämtar y-värdet för en diagramdatapunkt. Skrivskyddad [`IDoubleChartValue`](../idoublechartvalue). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | Returnerar en automatisk färg för datapunkten baserat på serieindex, datapunktindex, ParentSeriesGroup.IsColorVaried-egenskapen och diagramstil. Denna färg används som standard om FillType är lika med NotDefined. |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | Tar bort DataPoint från diagramserie. |

### Se även

* gränssnitt [IActualLayout](../iactuallayout)
* namnrymd [Aspose.Slides.Charts](../../aspose.slides.charts)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->