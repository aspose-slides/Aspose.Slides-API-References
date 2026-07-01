---
title: ChartDataPoint
second_title: Aspose.Sildes pro .NET API Referenci
description: Představuje datový bod řady.
type: docs
weight: 1310
url: /cs/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint třída

Představuje datový bod řady.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Vlastnosti

| Name | Description |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Určuje skutečnou výšku prvku grafu. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. Číst Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Určuje skutečnou šířku prvku grafu. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. Číst Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Určuje skutečnou polohu x (levá) prvku grafu vzhledem k levému hornímu rohu grafu. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. Číst Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Určuje skutečnou horní pozici prvku grafu vzhledem k levému hornímu rohu grafu. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. Číst Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Pouze pro čtení [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Vrací hodnotu barvy datového bodu grafu. Používá se u mapových grafů. Pouze pro čtení [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Vrací kontejner úrovní datových bodů. Používá se pro řady Treeamp a Sunburst. Indexování úrovní datových bodů začíná od nuly. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Zastupuje hodnoty chybových úseků řady v případě typu hodnoty Custom. Pouze pro čtení [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Určuje, o kolik má být datový bod přesunut od středu koláče. Číst/zapisovat Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Zastupuje vlastnosti formátování. Číst/zapisovat [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Určuje, že datový bod invertuje své barvy, pokud je hodnota záporná. Číst/zapisovat Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Určuje, že bubliny mají aplikovaný 3-D efekt. Číst/zapisovat Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Pouze pro čtení [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Určuje značku dat. Pouze pro čtení [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Vlastnosti odpovídající položky legendy v případě typů grafu z tohoto seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Pouze pro čtení [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Nastaví datový bod jako součet. Používá se pouze pro typ řady Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Vrací hodnotu velikosti datového bodu grafu. Používá se u grafů Treemap a Sunburst. Pouze pro čtení [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. Pouze pro čtení [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Pouze pro čtení [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Pouze pro čtení [`IDoubleChartValue`](../idoublechartvalue). |

## Metody

| Name | Description |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Vrací automatickou barvu datového bodu na základě indexu řady, indexu datového bodu, vlastnosti ParentSeriesGroup.IsColorVaried a stylu grafu. Tato barva se použije jako výchozí, pokud je FillType rovno NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Odstraní DataPoint ze série grafu. |

### Viz také

* rozhraní [IChartDataPoint](../ichartdatapoint)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->