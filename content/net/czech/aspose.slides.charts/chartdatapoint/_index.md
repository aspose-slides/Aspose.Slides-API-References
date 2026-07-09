---
title: ChartDataPoint
second_title: Aspose.Sildes pro .NET – referenční dokumentace API
description: Reprezentuje datový bod řady.
type: docs
weight: 1330
url: /cs/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint třída

Reprezentuje datový bod řady.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Určuje skutečnou výšku prvku grafu. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. Pouze ke čtení Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Určuje skutečnou šířku prvku grafu. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. Pouze ke čtení Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Určuje skutečnou polohu x (vlevo) prvku grafu vzhledem k levému hornímu rohu grafu. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. Pouze ke čtení Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Určuje skutečnou horní pozici prvku grafu vzhledem k levému hornímu rohu grafu. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. Pouze ke čtení Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Pouze pro čtení [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Vrací hodnotu barvy datového bodu grafu. Používá se u mapových grafů. Pouze pro čtení [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Vrací kontejner úrovní datových bodů. Používá se pro řady Treeamp a Sunburst. Indexování úrovní datových bodů začíná od nuly. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Reprezentuje hodnoty čar chyb řady v případě typu Custom. Pouze pro čtení [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Určuje množství, o které má být datový bod posunut od středu koláče. Čtení/zápis Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Reprezentuje vlastnosti formátování. Čtení/zápis [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Určuje, že datový bod invertuje své barvy, pokud je hodnota záporná. Čtení/zápis Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Určuje, že bubliny mají aplikován 3-D efekt. Čtení/zápis Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Pouze pro čtení [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Určuje datový marker. Pouze pro čtení [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Vlastnosti odpovídající položky legendy v případě typů grafu z tohoto seznamu: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Pouze pro čtení [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Nastavuje datový bod jako celkový. Používá se pouze pro řadu typu Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Vrací hodnotu velikosti datového bodu grafu. Používá se u grafů Treemap a Sunburst. Pouze pro čtení [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. Pouze pro čtení [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Pouze pro čtení [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Pouze pro čtení [`IDoubleChartValue`](../idoublechartvalue). |

## Metody

| Název | Popis |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Vrací automatickou barvu datového bodu na základě indexu řady, indexu datového bodu, vlastnosti ParentSeriesGroup.IsColorVaried a stylu grafu. Tato barva se použije jako výchozí, pokud je FillType rovno NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Odstraňuje DataPoint ze série grafu. |

### Viz také

* rozhraní [IChartDataPoint](../ichartdatapoint)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->