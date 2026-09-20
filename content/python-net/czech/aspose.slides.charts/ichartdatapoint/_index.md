---
title: IChartDataPoint class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint třída

Představuje datový bod řady.

Typ IChartDataPoint poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`x_value`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/x_value/) | Vrací hodnotu x datového bodu grafu.<br/>            Pouze pro čtení [`IStringOrDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/y_value/) | Vrací hodnotu y datového bodu grafu.<br/>            Pouze pro čtení [`IDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/bubble_size/) | Vrací velikost bubliny datového bodu grafu.<br/>            Pouze pro čtení [`IDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/value/) | Vrací hodnotu datového bodu grafu.<br/>            Pouze pro čtení [`IDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/size_value/) | Vrací velikostní hodnotu datového bodu grafu.<br/>            Používá se s grafy Treemap a Sunburst. <br/>            Pouze pro čtení [`IDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/color_value/) | Vrací hodnotu barvy datového bodu grafu.<br/>            Používá se s mapovými grafy. <br/>            Pouze pro čtení [`IDoubleChartValue`](/slides/python-net/cs/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Reprezentuje hodnoty chybových úseček řady v případě typu Custom.<br/>            Pouze pro čtení [`IErrorBarsCustomValues`](/slides/python-net/cs/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/label/) | Reprezentuje popisek datového bodu grafu.<br/>            Pouze pro čtení [`IDataLabel`](/slides/python-net/cs/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Určuje, že bubliny mají aplikovaný 3-D efekt.<br/>            Čtení/Zápis **bool**. |
| [`explosion`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/explosion/) | Určuje, o kolik má být datový bod posunut od středu koláče.<br/>            Čtení/Zápis **int**. |
| [`format`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/format/) | Reprezentuje vlastnosti formátování.<br/>            Čtení/Zápis [`IFormat`](/slides/python-net/cs/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/marker/) | Určuje značku dat.<br/>            Pouze pro čtení [`IMarker`](/slides/python-net/cs/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Vlastnosti odpovídající položky legendy v případě typu grafu z tohoto seznamu:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Pouze pro čtení [`ILegendEntryProperties`](/slides/python-net/cs/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/set_as_total/) | Nastaví datový bod jako součet. Používá se pouze pro typ řady Waterfall. |
| [`invert_if_negative`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Určuje, že datový bod má invertovat barvy, pokud je hodnota záporná.<br/>            Čtení/Zápis **bool**. |
| [`data_point_levels`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Vrací kontejner úrovní datových bodů. Používá se pro řady Treeamp a Sunburst.<br/>            Indexování úrovní datových bodů začíná od nuly. |
| [`index`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/index/) | Určuje, ke které kolekci potomků rodiče tento datový bod patří.<br/>            Pouze pro čtení **int**. |
| [`actual_x`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`remove(self)`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/remove/#) | Odstraní DataPoint z řady grafu. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Vrací automatickou barvu datového bodu na základě indexu řady, indexu datového bodu, vlastnosti ParentSeriesGroup.IsColorVaried a stylu grafu.<br/>            Tato barva se použije jako výchozí, pokud je FillType nastaven na NotDefined. |


### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)