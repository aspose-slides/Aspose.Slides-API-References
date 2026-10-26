---
title: IChartDataPoint class
second_title: Aspose.Slides dla Pythona w .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint klasa

Reprezentuje punkt danych serii.

Typ IChartDataPoint udostępnia następujące elementy:

## Właściwości

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/x_value/) | Zwraca wartość x punktu danych wykresu.<br/>            tylko do odczytu [`IStringOrDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/y_value/) | Zwraca wartość y punktu danych wykresu.<br/>            tylko do odczytu [`IDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/bubble_size/) | Zwraca rozmiar bąbelka punktu danych wykresu.<br/>            tylko do odczytu [`IDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/value/) | Zwraca wartość punktu danych wykresu.<br/>            tylko do odczytu [`IDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/size_value/) | Zwraca wartość rozmiaru punktu danych wykresu.<br/>            Used with Treemap and Sunburst charts. <br/>            tylko do odczytu [`IDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/color_value/) | Zwraca wartość koloru punktu danych wykresu.<br/>            Used with Map charts. <br/>            tylko do odczytu [`IDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Reprezentuje wartości słupków błędów serii w przypadku typu wartości Custom.<br/>            tylko do odczytu [`IErrorBarsCustomValues`](/slides/python-net/pl/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/label/) | Reprezentuje etykietę punktu danych wykresu.<br/>            tylko do odczytu [`IDataLabel`](/slides/python-net/pl/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Określa, że bąbelki mają zastosowany efekt 3D.<br/>            odczyt/zapis **bool**. |
| [`explosion`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/explosion/) | Określa, o ile punkt danych ma być przesunięty od środka koła.<br/>            odczyt/zapis **int**. |
| [`format`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/format/) | Reprezentuje właściwości formatowania.<br/>            odczyt/zapis [`IFormat`](/slides/python-net/pl/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/marker/) | Określa znacznik danych.<br/>            tylko do odczytu [`IMarker`](/slides/python-net/pl/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Właściwości odpowiadającego wpisu legendy w przypadku typu wykresu z tej listy:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            tylko do odczytu [`ILegendEntryProperties`](/slides/python-net/pl/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/set_as_total/) | Ustawia punkt danych jako sumę. Stosowane wyłącznie dla typu serii Waterfall. |
| [`invert_if_negative`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Określa, że punkt danych odwróci swoje kolory, jeśli wartość jest ujemna.<br/>            odczyt/zapis **bool**. |
| [`data_point_levels`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Zwraca kontener poziomów punktu danych. Stosowane dla serii Treeamp i Sunburst.<br/>            Indeksowanie poziomów punktów danych zaczyna się od zera. |
| [`index`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/index/) | Określa, do której kolekcji dzieci rodzica stosuje się ten punkt danych.<br/>            odczyt **int**. |
| [`actual_x`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/remove/#) | Usuwa DataPoint z serii wykresu. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Zwraca automatyczny kolor punktu danych w oparciu o indeks serii, indeks punktu danych, właściwość ParentSeriesGroup.IsColorVaried oraz styl wykresu.<br/>            Ten kolor jest używany domyślnie, jeśli FillType równa się NotDefined. |

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)