---
title: ChartDataPoint
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje datový bod řady.
type: docs
weight: 1340
url: /cs/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint třída

Representuje datový bod řady.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Určuje skutečnou výšku prvku grafu. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. Číst Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Určuje skutečnou šířku prvku grafu. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. Číst Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Určuje skutečnou polohu x (levá) prvku grafu vzhledem k levému hornímu rohu grafu. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. Číst Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Určuje skutečnou horní polohu prvku grafu vzhledem k levému hornímu rohu grafu. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. Číst Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Pouze ke čtení [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/chartdatapoint/cachedbubblesize) { get; } | Získá uloženou velikost bubliny datového bodu grafu. Pouze ke čtení [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/chartdatapoint/cachedvalue) { get; } | Získá uloženou hodnotu datového bodu grafu. Pouze ke čtení [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/chartdatapoint/cachedxvalue) { get; } | Získá uloženou hodnotu X datového bodu grafu. Pouze ke čtení [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/chartdatapoint/cachedyvalue) { get; } | Získá uloženou hodnotu Y datového bodu grafu. Pouze ke čtení [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Vrací hodnotu barvy datového bodu grafu. Používá se u mapových grafů. Pouze ke čtení [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Vrací kontejner úrovní datových bodů. Používá se u řad Treeamp a Sunburst. Indexování úrovní datových bodů začíná nulou. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Představuje hodnoty chybových úseček řady v případě typu Custom. Pouze ke čtení [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Určuje, o kolik má být datový bod posunut od středu výseče. Čtení/zápis Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Představuje vlastnosti formátování. Čtení/zápis [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Určuje, že datový bod má invertovat barvy, pokud je hodnota záporná. Čtení/zápis Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Určuje, že bubliny mají aplikován 3D efekt. Čtení/zápis Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Pouze ke čtení [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Určuje datový marker. Pouze ke čtení [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Vlastnosti odpovídající položky legendy v případě typů grafu z tohoto seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Pouze ke čtení [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Nastaví datový bod jako součet. Používá se pouze pro typ řady Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Vrací hodnotu velikosti datového bodu grafu. Používá se u grafů Treemap a Sunburst. Pouze ke čtení [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. Pouze ke čtení [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Pouze ke čtení [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Pouze ke čtení [`IDoubleChartValue`](../idoublechartvalue). |

## Metody

| Název | Popis |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Vrací automatickou barvu datového bodu na základě indexu řady, indexu datového bodu, vlastnosti ParentSeriesGroup.IsColorVaried a stylu grafu. Tato barva je použita jako výchozí, pokud je FillType rovno NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Odstraní DataPoint ze série grafu. |

### Viz také

* rozhraní [IChartDataPoint](../ichartdatapoint)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->