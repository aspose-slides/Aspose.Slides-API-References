---
title: IChartDataPoint class
second_title: Referencja API Aspose.Slides dla Pythona za pośrednictwem .NET
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
| [`x_value`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/x_value/) | Pobiera wartość x punktu danych wykresu.<br/>            Tylko do odczytu [`IStringOrDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/y_value/) | Pobiera wartość y punktu danych wykresu.<br/>            Tylko do odczytu [`IDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/bubble_size/) | Pobiera rozmiar bąbelka punktu danych wykresu.<br/>            Tylko do odczytu [`IDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/value/) | Pobiera wartość punktu danych wykresu.<br/>            Tylko do odczytu [`IDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/idoublechartvalue). |
| [`cached_x_value`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/cached_x_value/) | Pobiera buforowaną wartość X punktu danych wykresu.<br/>            Tylko do odczytu [`ICachedChartValue`](/slides/python-net/pl/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/cached_y_value/) | Pobiera buforowaną wartość Y punktu danych wykresu.<br/>            Tylko do odczytu [`ICachedChartValue`](/slides/python-net/pl/aspose.slides.charts/icachedchartvalue). |
| [`cached_value`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/cached_value/) | Pobiera buforowaną wartość punktu danych wykresu.<br/>            Tylko do odczytu [`ICachedChartValue`](/slides/python-net/pl/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/cached_bubble_size/) | Pobiera buforowany rozmiar bąbelka punktu danych wykresu.<br/>            Tylko do odczytu [`ICachedChartValue`](/slides/python-net/pl/aspose.slides.charts/icachedchartvalue). |
| [`size_value`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/size_value/) | Pobiera wartość rozmiaru punktu danych wykresu.<br/>            Używane w wykresach Treemap i Sunburst.<br/>            Tylko do odczytu [`IDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/color_value/) | Pobiera wartość koloru punktu danych wykresu.<br/>            Używane w wykresach map.<br/>            Tylko do odczytu [`IDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Reprezentuje wartości słupków błędów serii w przypadku typu Custom.<br/>            Tylko do odczytu [`IErrorBarsCustomValues`](/slides/python-net/pl/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/label/) | Reprezentuje etykietę punktu danych wykresu.<br/>            Tylko do odczytu [`IDataLabel`](/slides/python-net/pl/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Określa, że bąbelki mają zastosowany efekt 3D.<br/>            Odczyt/zapis **bool**. |
| [`explosion`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/explosion/) | Określa odległość, o jaką punkt danych ma być przesunięty od środka wykresu kołowego.<br/>            Odczyt/zapis **int**. |
| [`format`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/format/) | Reprezentuje właściwości formatowania.<br/>            Odczyt/zapis [`IFormat`](/slides/python-net/pl/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/marker/) | Określa znacznik danych.<br/>            Tylko do odczytu [`IMarker`](/slides/python-net/pl/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Właściwości odpowiadającego wpisu legendy w przypadku typu wykresu z tej listy:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Tylko do odczytu [`ILegendEntryProperties`](/slides/python-net/pl/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/set_as_total/) | Ustawia punkt danych jako sumę. Stosowane wyłącznie dla typu serii Waterfall. |
| [`invert_if_negative`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Określa, że punkt danych odwróci swoje kolory, jeśli wartość jest ujemna.<br/>            Odczyt/zapis **bool**. |
| [`data_point_levels`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Zwraca kontener poziomów punktu danych. Stosowane dla serii Treeamp i Sunburst.<br/>            Indeksowanie poziomów punktu danych jest zerowe. |
| [`index`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/index/) | Określa, do której kolekcji dzieci rodzica ten punkt danych się odnosi.<br/>            Odczyt **int**. |
| [`actual_x`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/remove/#) | Usuwa DataPoint z serii wykresu. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/pl/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Zwraca automatyczny kolor punktu danych w oparciu o indeks serii, indeks punktu danych, właściwość ParentSeriesGroup.IsColorVaried i styl wykresu.<br/>            Ten kolor jest używany domyślnie, jeśli FillType ma wartość NotDefined. |

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)