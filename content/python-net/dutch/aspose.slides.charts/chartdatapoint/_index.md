---
title: ChartDataPoint class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint klasse

Stelt een seriedatapunt voor.

Het type ChartDataPoint biedt de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`x_value`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Alleen-lezen [`IStringOrDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/size_value/) | Geeft de groottewaarde van het grafiekdatapunt terug.<br/>            Wordt gebruikt met Treemap- en Sunburst-grafieken.<br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/color_value/) | Geeft de kleurwaarde van het grafiekdatapunt terug.<br/>            Wordt gebruikt met kaart-grafieken.<br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Stelt de waarden van de foutbalken van de serie in voor type Custom.<br/>            Alleen-lezen [`IErrorBarsCustomValues`](/slides/python-net/nl/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Alleen-lezen [`IDataLabel`](/slides/python-net/nl/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Geeft aan dat de bubbels een 3-D-effect hebben.<br/>            Lezen/Schrijven **bool**. |
| [`explosion`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/explosion/) | Geeft de hoeveelheid aan waarmee het datapunt moet worden verplaatst vanaf het middelpunt van de taart.<br/>            Lezen/Schrijven **int**. |
| [`format`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/format/) | Stelt de opmaak-eigenschappen in.<br/>            Lezen/Schrijven [`IFormat`](/slides/python-net/nl/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/marker/) | Geeft een datamarker aan.<br/>            Alleen-lezen [`IMarker`](/slides/python-net/nl/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/set_as_total/) | Stelt het datapunt in als totaal. Alleen toegepast voor Waterfall-serietype. |
| [`related_legend_entry`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Eigenschappen van het overeenkomstige legenda-item in het geval van een grafiektype uit deze lijst:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Alleen-lezen [`ILegendEntryProperties`](/slides/python-net/nl/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/data_point_levels/) | Geeft de container van datapunt-niveaus terug. Toegepast voor Treeamp- en Sunburst-series.<br/>            Indexering van datapuntniveaus begint bij nul. |
| [`index`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Geeft aan dat het datapunt zijn kleuren moet omkeren als de waarde negatief is.<br/>            Lezen/Schrijven **bool**. |
| [`cached_value`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/cached_value/) | Haalt de gecachte waarde van een grafiekdatapunt op.<br/>            Alleen-lezen [`ICachedChartValue`](/slides/python-net/nl/aspose.slides.charts/icachedchartvalue). |
| [`cached_x_value`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/cached_x_value/) | Haalt de gecachte X-waarde van een grafiekdatapunt op.<br/>            Alleen-lezen [`ICachedChartValue`](/slides/python-net/nl/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/cached_y_value/) | Haalt de gecachte Y-waarde van een grafiekdatapunt op.<br/>            Alleen-lezen [`ICachedChartValue`](/slides/python-net/nl/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/cached_bubble_size/) | Haalt de gecachte bubble-grootte van een grafiekdatapunt op.<br/>            Alleen-lezen [`ICachedChartValue`](/slides/python-net/nl/aspose.slides.charts/icachedchartvalue). |
| [`actual_x`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/actual_x/) | Geeft de werkelijke x-locatie (links) van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek aan.<br/>            Roep methode IChart.ValidateChartLayout() aan vóór het verkrijgen van werkelijke waarden.<br/>            Lees **float**. |
| [`actual_y`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/actual_y/) | Geeft de werkelijke bovenkant van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek aan.<br/>            Roep methode IChart.ValidateChartLayout() aan vóór het verkrijgen van werkelijke waarden.<br/>            Lees **float**. |
| [`actual_width`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/actual_width/) | Geeft de werkelijke breedte van het grafiekelement aan. Roep methode IChart.ValidateChartLayout() aan vóór het verkrijgen van werkelijke waarden.<br/>            Lees **float**. |
| [`actual_height`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/actual_height/) | Geeft de werkelijke hoogte van het grafiekelement aan. Roep methode IChart.ValidateChartLayout() aan vóór het verkrijgen van werkelijke waarden.<br/>            Lees **float**. |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`remove(self)`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/remove/#) | Verwijdert DataPoint uit de grafiekserie. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/nl/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Geeft een automatische kleur van het datapunt terug op basis van seriëindex, datapuntindex, de eigenschap ParentSeriesGroup.IsColorVaried en de grafiekstijl.<br/>            Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined. |

### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)