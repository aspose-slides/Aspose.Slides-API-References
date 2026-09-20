---
title: ChartDataPoint class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint třída

Reprezentuje datový bod řady.

The ChartDataPoint type exposes the following members:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Pouze ke čtení [`IStringOrDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Pouze ke čtení [`IDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Pouze ke čtení [`IDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Pouze ke čtení [`IDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/size_value/) | Vrací hodnotu velikosti datového bodu grafu.<br/>            Používá se s grafy Treemap a Sunburst. <br/>            Pouze ke čtení [`IDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/color_value/) | Vrací hodnotu barvy datového bodu grafu.<br/>            Používá se s mapovými grafy. <br/>            Pouze ke čtení [`IDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Reprezentuje hodnoty chybových úseček řady v případě typu Custom value.<br/>            Pouze ke čtení [`IErrorBarsCustomValues`](/slides/python-net/cs/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Pouze ke čtení [`IDataLabel`](/slides/python-net/cs/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Určuje, že bubliny mají aplikovaný 3-D efekt.<br/>            Čtení/zápis **bool**. |
| [`explosion`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/explosion/) | Určuje množství, o které se datový bod má posunout od středu koláčového grafu.<br/>            Čtení/zápis **int**. |
| [`format`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/format/) | Reprezentuje vlastnosti formátování.<br/>            Čtení/zápis [`IFormat`](/slides/python-net/cs/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/marker/) | Určuje datový značkovač.<br/>            Pouze ke čtení [`IMarker`](/slides/python-net/cs/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/set_as_total/) | Nastaví datový bod jako součet. Používá se pouze pro typ řady Waterfall. |
| [`related_legend_entry`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Vlastnosti odpovídající položky legendy v případě typu grafu z tohoto seznamu:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Pouze ke čtení [`ILegendEntryProperties`](/slides/python-net/cs/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/data_point_levels/) | Vrací kontejner úrovní datových bodů. Používá se pro řady Treeamp a Sunburst.<br/>            Indexování úrovní datových bodů je založeno na nule. |
| [`index`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Určuje, že datový bod má invertovat své barvy, pokud je hodnota záporná.<br/>            Čtení/zápis **bool**. |
| [`actual_x`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/actual_x/) | Určuje aktuální umístění x (vlevo) grafického prvku vzhledem k levému hornímu rohu grafu.<br/>            Před získáním skutečných hodnot zavolejte metodu IChart.ValidateChartLayout(). <br/>            Čtení **float**. |
| [`actual_y`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/actual_y/) | Určuje aktuální horní pozici grafického prvku vzhledem k levému hornímu rohu grafu.<br/>            Před získáním skutečných hodnot zavolejte metodu IChart.ValidateChartLayout(). <br/>            Čtení **float**. |
| [`actual_width`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/actual_width/) | Určuje aktuální šířku grafického prvku. Před získáním skutečných hodnot zavolejte metodu IChart.ValidateChartLayout(). <br/>            Čtení **float**. |
| [`actual_height`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/actual_height/) | Určuje aktuální výšku grafického prvku. Před získáním skutečných hodnot zavolejte metodu IChart.ValidateChartLayout(). <br/>            Čtení **float**. |

## Metody

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/remove/#) | Odstraní DataPoint ze série grafu. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Vrací automatickou barvu datového bodu na základě indexu řady, indexu datového bodu, vlastnosti ParentSeriesGroup.IsColorVaried a stylu grafu.<br/>            Tato barva se použije jako výchozí, pokud je FillType rovno NotDefined. |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)