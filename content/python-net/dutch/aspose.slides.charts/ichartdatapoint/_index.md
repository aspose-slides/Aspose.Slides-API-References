---
title: IChartDataPoint class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint klasse

Stelt een seriedatapunt voor.

Het IChartDataPoint-type bevat de volgende leden:

## Eigenschappen

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/x_value/) | Geeft de x-waarde van het grafiekdatapunt terug.<br/>            Alleen-lezen [`IStringOrDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/y_value/) | Geeft de y-waarde van het grafiekdatapunt terug.<br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/bubble_size/) | Geeft de grootte van de bubbel van het grafiekdatapunt terug.<br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/value/) | Geeft de waarde van het grafiekdatapunt terug.<br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/size_value/) | Geeft de groottewaarde van het grafiekdatapunt terug.<br/>            Wordt gebruikt met Treemap- en Sunburst-diagrammen. <br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/color_value/) | Geeft de kleurwaarde van het grafiekdatapunt terug.<br/>            Wordt gebruikt met kaartdiagrammen. <br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Stelt de waarden van seriefoutenbalken voor in het geval van een aangepast waardetype.<br/>            Alleen-lezen [`IErrorBarsCustomValues`](/slides/python-net/nl/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/label/) | Stelt het label van het grafiekdatapunt voor.<br/>            Alleen-lezen [`IDataLabel`](/slides/python-net/nl/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Specificeert dat de bubbels een 3D-effect hebben.<br/>            Lezen/Schrijven **bool**. |
| [`explosion`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/explosion/) | Specificeert de hoeveelheid waarmee het datapunt van het midden van de taartgrafiek moet worden verplaatst.<br/>            Lezen/Schrijven **int**. |
| [`format`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/format/) | Stelt de opmaak-eigenschappen voor.<br/>            Lezen/Schrijven [`IFormat`](/slides/python-net/nl/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/marker/) | Specificeert een datamarker.<br/>            Alleen-lezen [`IMarker`](/slides/python-net/nl/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Eigenschappen van het overeenkomstige legende-item in het geval van een grafiektype uit deze lijst:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Alleen-lezen [`ILegendEntryProperties`](/slides/python-net/nl/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/set_as_total/) | Stelt het datapunt in als totaal. Alleen toepasbaar op Waterfall-serietype. |
| [`invert_if_negative`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Specificeert dat het datapunt zijn kleuren moet omkeren als de waarde negatief is.<br/>            Lezen/Schrijven **bool**. |
| [`data_point_levels`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Geeft de container van datapuntniveaus terug. Wordt gebruikt voor Treeamp- en Sunburst-series.<br/>            Indexering van datapuntniveaus begint bij nul. |
| [`index`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/index/) | Bepaalt op welke collectie van het kind van de ouder dit datapunt van toepassing is.<br/>            Alleen-lezen **int**. |
| [`actual_x`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/remove/#) | Verwijdert DataPoint uit de grafieksreeks. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Geeft een automatische kleur van het datapunt terug op basis van serië-index, datapunt-index, ParentSeriesGroup.IsColorVaried-eigenschap en grafiekstijl. <br/>            Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined. |


### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)