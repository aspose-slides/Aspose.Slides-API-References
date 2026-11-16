---
title: IChartDataPoint
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje datový bod řady.
type: docs
weight: 1840
url: /cs/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint rozhraní

Represents series data point.

```csharp
public interface IChartDataPoint : IActualLayout
```

## Vlastnosti

| Name | Description |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | Vrací rozhraní IActualLayout. |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | Získá velikost bubliny datového bodu grafu. Pouze ke čtení [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/ichartdatapoint/cachedbubblesize) { get; } | Získá uloženou velikost bubliny datového bodu grafu. Pouze ke čtení [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/ichartdatapoint/cachedvalue) { get; } | Získá uloženou hodnotu datového bodu grafu. Pouze ke čtení [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/ichartdatapoint/cachedxvalue) { get; } | Získá uloženou hodnotu X datového bodu grafu. Pouze ke čtení [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/ichartdatapoint/cachedyvalue) { get; } | Získá uloženou hodnotu Y datového bodu grafu. Pouze ke čtení [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | Získá hodnotu barvy datového bodu grafu. Používá se u mapových grafů. Pouze ke čtení [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | Vrací kontejner úrovní datových bodů. Použito pro řady Treeamp a Sunburst. Indexování úrovní datových bodů začíná nulou. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | Představuje hodnoty chybových pruhů řady v případě typu hodnoty Custom. Pouze ke čtení [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | Určuje množství, o které má být datový bod posunut od středu výsečového grafu. Čtení/zápis Int32. |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | Představuje vlastnosti formátování. Čtení/zápis [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | Určuje, ke které kolekci podřízených objektů rodiče se tento datový bod vztahuje. Čtení UInt32. |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | Určuje, že datový bod invertuje své barvy, pokud je hodnota záporná. Čtení/zápis Boolean. |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | Určuje, že bubliny mají aplikovaný 3D efekt. Čtení/zápis Boolean. |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | Představuje popisek datového bodu grafu. Pouze ke čtení [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | Určuje datový marker. Pouze ke čtení [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | Vlastnosti odpovídající položky legendy v případě typu grafu z tohoto seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Pouze ke čtení [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | Nastaví datový bod jako souhrn. Použito pouze pro řadu typu Waterfall. |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | Získá hodnotu velikosti datového bodu grafu. Používá se u grafů Treemap a Sunburst. Pouze ke čtení [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | Získá hodnotu datového bodu grafu. Pouze ke čtení [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | Získá hodnotu x datového bodu grafu. Pouze ke čtení [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | Získá hodnotu y datového bodu grafu. Pouze ke čtení [`IDoubleChartValue`](../idoublechartvalue). |

## Metody

| Name | Description |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | Vrací automatickou barvu datového bodu na základě indexu řady, indexu datového bodu, vlastnosti ParentSeriesGroup.IsColorVaried a stylu grafu. Tato barva se použije jako výchozí, pokud je FillType nastaven na NotDefined. |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | Odstraní DataPoint ze série grafu. |

### Viz také

* rozhraní [IActualLayout](../iactuallayout)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* assemblie [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->