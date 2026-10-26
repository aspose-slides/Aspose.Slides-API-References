---
title: ChartDataPoint class
second_title: Aspose.Slides dla Pythona poprzez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint klasa

Reprezentuje punkt danych serii.

Typ ChartDataPoint udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`x_value`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Tylko do odczytu [`IStringOrDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Tylko do odczytu [`IDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Tylko do odczytu [`IDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Tylko do odczytu [`IDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/size_value/) | Zwraca wartość rozmiaru punktu danych wykresu.<br/>            Używany z wykresami Treemap i Sunburst. <br/>            Tylko do odczytu [`IDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/color_value/) | Zwraca wartość koloru punktu danych wykresu.<br/>            Używany z wykresami Map. <br/>            Tylko do odczytu [`IDoubleChartValue`](/slides/python-net/pl/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Reprezentuje wartości słupków błędów serii w przypadku typu wartości Custom.<br/>            Tylko do odczytu [`IErrorBarsCustomValues`](/slides/python-net/pl/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Tylko do odczytu [`IDataLabel`](/slides/python-net/pl/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Określa, że bąbelki mają zastosowany efekt 3-D.<br/>            Odczyt/zapis **bool**. |
| [`explosion`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/explosion/) | Określa ilość, o jaką punkt danych ma być przesunięty od środka koła.<br/>            Odczyt/zapis **int**. |
| [`format`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/format/) | Reprezentuje właściwości formatowania.<br/>            Odczyt/zapis [`IFormat`](/slides/python-net/pl/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/marker/) | Określa znacznik danych.<br/>            Tylko do odczytu [`IMarker`](/slides/python-net/pl/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/set_as_total/) | Ustawia punkt danych jako sumę całkowitą. Stosowane wyłącznie dla typu serii Waterfall. |
| [`related_legend_entry`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Właściwości odpowiadającego wpisu legendy w przypadku typu wykresu z tej listy:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Tylko do odczytu [`ILegendEntryProperties`](/slides/python-net/pl/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/data_point_levels/) | Zwraca kontener poziomów punktów danych. Stosowane dla serii Treeamp i Sunburst.<br/>            Indeksowanie poziomów punktów danych zaczyna się od zera. |
| [`index`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Określa, że punkt danych odwróci swoje kolory, jeśli wartość jest ujemna.<br/>            Odczyt/zapis **bool**. |
| [`actual_x`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/actual_x/) | Określa rzeczywistą pozycję x (lewy) elementu wykresu względem lewego górnego rogu wykresu.<br/>            Wywołaj metodę IChart.ValidateChartLayout() przed uzyskaniem rzeczywistych wartości. <br/>            Odczyt **float**. |
| [`actual_y`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/actual_y/) | Określa rzeczywistą górną pozycję elementu wykresu względem lewego górnego rogu wykresu.<br/>            Wywołaj metodę IChart.ValidateChartLayout() przed uzyskaniem rzeczywistych wartości. <br/>            Odczyt **float**. |
| [`actual_width`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/actual_width/) | Określa rzeczywistą szerokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed uzyskaniem rzeczywistych wartości. <br/>            Odczyt **float**. |
| [`actual_height`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/actual_height/) | Określa rzeczywistą wysokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed uzyskaniem rzeczywistych wartości. <br/>            Odczyt **float**. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`remove(self)`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/remove/#) | Usuwa DataPoint z serii wykresu. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/pl/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Zwraca automatyczny kolor punktu danych na podstawie indeksu serii, indeksu punktu danych, właściwości ParentSeriesGroup.IsColorVaried oraz stylu wykresu.<br/>            Ten kolor jest używany domyślnie, jeśli FillType jest równe NotDefined. |

### Zobacz też
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)