---
title: ChartDataPoint class
second_title: Aspose.Slides pro Python prostřednictvím .NET referenční dokumentace API
description: 
type: docs
url: /cs/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint třída

Reprezentuje datový bod řady.

Typ ChartDataPoint poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`x_value`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Pouze pro čtení [`IStringOrDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Pouze pro čtení [`IDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Pouze pro čtení [`IDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Pouze pro čtení [`IDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/size_value/) | Vrací velikostní hodnotu datového bodu grafu.<br/>            Použito s grafy Treemap a Sunburst. <br/>            Pouze pro čtení [`IDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/color_value/) | Vrací barvu datového bodu grafu.<br/>            Použito s grafy Map. <br/>            Pouze pro čtení [`IDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Reprezentuje hodnoty chybových úseků řady v případě typu Custom value.<br/>            Pouze pro čtení [`IErrorBarsCustomValues`](/slides/python-net/cs/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Pouze pro čtení [`IDataLabel`](/slides/python-net/cs/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Určuje, že bubliny mají aplikován 3-D efekt.<br/>            Čtení/zápis **bool**. |
| [`explosion`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/explosion/) | Určuje, o kolik bude datový bod posunut od středu výseče.<br/>            Čtení/zápis **int**. |
| [`format`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/format/) | Reprezentuje vlastnosti formátování.<br/>            Čtení/zápis [`IFormat`](/slides/python-net/cs/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/marker/) | Určuje datový marker.<br/>            Pouze pro čtení [`IMarker`](/slides/python-net/cs/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/set_as_total/) | Nastavuje datový bod jako součet. Použito pouze pro typ řady Waterfall. |
| [`related_legend_entry`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Vlastnosti odpovídající položky legendy v případě typu grafu z následujícího seznamu:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Pouze pro čtení [`ILegendEntryProperties`](/slides/python-net/cs/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/data_point_levels/) | Vrací kontejner úrovní datových bodů. Použito pro řady Treeamp a Sunburst.<br/>            Indexování úrovní datových bodů je nulové. |
| [`index`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Určuje, že datový bod invertuje své barvy, pokud je hodnota záporná.<br/>            Čtení/zápis **bool**. |
| [`cached_value`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/cached_value/) | Získává uloženou hodnotu datového bodu grafu.<br/>            Pouze pro čtení [`ICachedChartValue`](/slides/python-net/cs/aspose.slides.charts/icachedchartvalue). |
| [`cached_x_value`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/cached_x_value/) | Získává uloženou hodnotu X datového bodu grafu.<br/>            Pouze pro čtení [`ICachedChartValue`](/slides/python-net/cs/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/cached_y_value/) | Získává uloženou hodnotu Y datového bodu grafu.<br/>            Pouze pro čtení [`ICachedChartValue`](/slides/python-net/cs/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/cached_bubble_size/) | Získává uloženou velikost bubliny datového bodu grafu.<br/>            Pouze pro čtení [`ICachedChartValue`](/slides/python-net/cs/aspose.slides.charts/icachedchartvalue). |
| [`actual_x`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/actual_x/) | Určuje skutečnou x polohu (levá) prvku grafu vzhledem k levému hornímu rohu grafu.<br/>            Před tím volejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. <br/>            Čtení **float**. |
| [`actual_y`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/actual_y/) | Určuje skutečný horní okraj prvku grafu vzhledem k levému hornímu rohu grafu.<br/>            Před tím volejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. <br/>            Čtení **float**. |
| [`actual_width`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/actual_width/) | Určuje skutečnou šířku prvku grafu. Před tím volejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. <br/>            Čtení **float**. |
| [`actual_height`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/actual_height/) | Určuje skutečnou výšku prvku grafu. Před tím volejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. <br/>            Čtení **float**. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`remove(self)`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/remove/#) | Odstraňuje DataPoint ze série grafu. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/cs/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Vrací automatickou barvu datového bodu na základě indexu řady, indexu datového bodu, vlastnosti ParentSeriesGroup.IsColorVaried a stylu grafu.<br/>            Tato barva se použije jako výchozí, pokud je FillType rovno NotDefined. |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)