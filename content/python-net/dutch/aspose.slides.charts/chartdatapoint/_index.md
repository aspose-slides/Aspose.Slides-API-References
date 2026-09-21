---
title: ChartDataPoint class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint klasse

Vertegenwoordigt een serie-datapunt.

Het type ChartDataPoint heeft de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`x_value`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Alleen-lezen [`IStringOrDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/size_value/) | Retourneert de groottewaarde van een chart-datapunt.<br/>            Wordt gebruikt bij Treemap- en Sunburst-grafieken. <br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/color_value/) | Retourneert de kleurswaarde van een chart-datapunt.<br/>            Wordt gebruikt bij Map-grafieken. <br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Vertegenwoordigt waarden voor foutbalken van de serie in geval van een aangepaste (Custom) waardetype.<br/>            Alleen-lezen [`IErrorBarsCustomValues`](/slides/python-net/nl/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Alleen-lezen [`IDataLabel`](/slides/python-net/nl/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Geeft aan dat de bellen een 3-D-effect hebben.<br/>            Lezen/Schrijven **bool**. |
| [`explosion`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/explosion/) | Geeft de hoeveelheid waarmee het datapunt van het midden van de taart wordt verschoven.<br/>            Lezen/Schrijven **int**. |
| [`format`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/format/) | Vertegenwoordigt de opmaak-eigenschappen.<br/>            Lezen/Schrijven [`IFormat`](/slides/python-net/nl/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/marker/) | Specificeert een datamarker.<br/>            Alleen-lezen [`IMarker`](/slides/python-net/nl/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/set_as_total/) | Stelt datapunt in als totaal. Alleen van toepassing op Waterfall-serietype. |
| [`related_legend_entry`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Eigenschappen van overeenkomstige legenda-item in het geval van een grafiektype uit deze lijst:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Alleen-lezen [`ILegendEntryProperties`](/slides/python-net/nl/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/data_point_levels/) | Retourneert container van datapuntniveaus. Alleen van toepassing op Treeamp- en Sunburst-series.<br/>            Indexering van datapuntniveaus begint bij nul. |
| [`index`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Specificeert dat het datapunt zijn kleuren moet inverteren wanneer de waarde negatief is.<br/>            Lezen/Schrijven **bool**. |
| [`actual_x`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/actual_x/) | Specificeert de daadwerkelijke x-locatie (links) van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek.<br/>            Roep de methode IChart.ValidateChartLayout() aan vóór het verkrijgen van de daadwerkelijke waarden. <br/>            Lezen **float**. |
| [`actual_y`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/actual_y/) | Specificeert de daadwerkelijke bovenkant van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek.<br/>            Roep de methode IChart.ValidateChartLayout() aan vóór het verkrijgen van de daadwerkelijke waarden. <br/>            Lezen **float**. |
| [`actual_width`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/actual_width/) | Specificeert de daadwerkelijke breedte van het grafiekelement. Roep de methode IChart.ValidateChartLayout() aan vóór het verkrijgen van de daadwerkelijke waarden. <br/>            Lezen **float**. |
| [`actual_height`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/actual_height/) | Specificeert de daadwerkelijke hoogte van het grafiekelement. Roep de methode IChart.ValidateChartLayout() aan vóór het verkrijgen van de daadwerkelijke waarden. <br/>            Lezen **float**. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`remove(self)`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/remove/#) | Verwijdert DataPoint uit de grafiekserie. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Retourneert een automatische kleur van het datapunt op basis van de seriële index, datapuntindex, de eigenschap ParentSeriesGroup.IsColorVaried en de grafiekstijl.<br/>            Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined. |

### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)