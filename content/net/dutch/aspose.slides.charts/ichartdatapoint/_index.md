---
title: IChartDataPoint
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een gegevenspunt van een reeks voor.
type: docs
weight: 1840
url: /nl/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint interface

Represents series data point.

```csharp
public interface IChartDataPoint : IActualLayout
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | Retourneert IActualLayout interface. |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | Haalt de bubbelgrootte van een grafiekgegevenspunt op. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/ichartdatapoint/cachedbubblesize) { get; } | Haalt de gecachte bubbelgrootte van een grafiekgegevenspunt op. Alleen-lezen [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/ichartdatapoint/cachedvalue) { get; } | Haalt de gecachte waarde van een grafiekgegevenspunt op. Alleen-lezen [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/ichartdatapoint/cachedxvalue) { get; } | Haalt de gecachte X-waarde van een grafiekgegevenspunt op. Alleen-lezen [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/ichartdatapoint/cachedyvalue) { get; } | Haalt de gecachte Y-waarde van een grafiekgegevenspunt op. Alleen-lezen [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | Haalt de kleurwaarde van een grafiekgegevenspunt op. Wordt gebruikt met Kaart-grafieken. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | Retourneert container van gegevenspuntniveaus. Toegepast voor Treeamp- en Sunburst-reeksen. Indexering van gegevenspuntniveaus begint bij nul. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | Stelt waarden van foutenbalken van de reeks voor in het geval van een Aangepast-waardetype. Alleen-lezen [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | Specificeert de hoeveelheid waarmee het gegevenspunt van het middelpunt van de taart moet worden verplaatst. Lezen/schrijven Int32. |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | Stelt de opmaak-eigenschappen voor. Lezen/schrijven [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | Bepaalt tot welke verzameling van onderliggende elementen van de ouder dit gegevenspunt behoort. Alleen-lezen UInt32. |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | Specificeert dat het gegevenspunt zijn kleuren moet omkeren als de waarde negatief is. Lezen/schrijven Boolean. |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | Specificeert dat de bellen een 3-D-effect hebben. Lezen/schrijven Boolean. |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | Stelt het label van een grafiekgegevenspunt voor. Alleen-lezen [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | Specificeert een gegevensmarker. Alleen-lezen [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | Eigenschappen van het overeenkomstige legenda-item in het geval van een grafiektype uit deze lijst: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Alleen-lezen [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | Stelt het gegevenspunt in als totaal. Alleen van toepassing op Waterfall-reeks. |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | Haalt de groottewaarde van een grafiekgegevenspunt op. Wordt gebruikt met Treemap- en Sunburst-grafieken. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | Haalt de waarde van een grafiekgegevenspunt op. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | Haalt de x-waarde van een grafiekgegevenspunt op. Alleen-lezen [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | Haalt de y-waarde van een grafiekgegevenspunt op. Alleen-lezen [`IDoubleChartValue`](../idoublechartvalue). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | Retourneert een automatische kleur van het gegevenspunt op basis van reeks-index, gegevenspunt-index, ParentSeriesGroup.IsColorVaried-eigenschap en grafiekstijl. Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined. |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | Verwijdert DataPoint uit de grafieksreeks. |

### Zie ook

* interface [IActualLayout](../iactuallayout)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->