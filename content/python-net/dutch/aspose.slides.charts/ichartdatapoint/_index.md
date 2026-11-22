---
title: IChartDataPoint class
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint klasse

Representeert een gegevenspunt van een serie.

Het type IChartDataPoint bevat de volgende leden:

## Eigenschappen

| Eigenschap | Beschrijving |
| :- | :- |
| [`x_value`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/x_value/) | Haalt de x-waarde van een diagramgegevenspunt op.<br/>            Alleen-lezen [`IStringOrDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/y_value/) | Haalt de y-waarde van een diagramgegevenspunt op.<br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/bubble_size/) | Haalt de bubbelgrootte van een diagramgegevenspunt op.<br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/value/) | Haalt de waarde van een diagramgegevenspunt op.<br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`cached_x_value`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/cached_x_value/) | Haalt de gecachte X-waarde van een diagramgegevenspunt op.<br/>            Alleen-lezen [`ICachedChartValue`](/slides/python-net/nl/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/cached_y_value/) | Haalt de gecachte Y-waarde van een diagramgegevenspunt op.<br/>            Alleen-lezen [`ICachedChartValue`](/slides/python-net/nl/aspose.slides.charts/icachedchartvalue). |
| [`cached_value`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/cached_value/) | Haalt de gecachte waarde van een diagramgegevenspunt op.<br/>            Alleen-lezen [`ICachedChartValue`](/slides/python-net/nl/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/cached_bubble_size/) | Haalt de gecachte bubbelgrootte van een diagramgegevenspunt op.<br/>            Alleen-lezen [`ICachedChartValue`](/slides/python-net/nl/aspose.slides.charts/icachedchartvalue). |
| [`size_value`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/size_value/) | Haalt de groottewaarde van een diagramgegevenspunt op.<br/>            Gebruikt met Treemap- en Sunburst-diagrammen. <br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/color_value/) | Haalt de kleurwaarde van een diagramgegevenspunt op.<br/>            Gebruikt met kaartdiagrammen. <br/>            Alleen-lezen [`IDoubleChartValue`](/slides/python-net/nl/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Stelt de waarden van foutbalken van de serie voor in het geval van een aangepast (Custom) waardetype.<br/>            Alleen-lezen [`IErrorBarsCustomValues`](/slides/python-net/nl/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/label/) | Stelt het label van een diagramgegevenspunt voor.<br/>            Alleen-lezen [`IDataLabel`](/slides/python-net/nl/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Geeft aan dat de bellen een 3-D-effect hebben.<br/>            Lezen/Schrijven **bool**. |
| [`explosion`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/explosion/) | Geeft de hoeveelheid aan waarmee het gegevenspunt vanaf het midden van de taartgrafiek moet worden verplaatst.<br/>            Lezen/Schrijven **int**. |
| [`format`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/format/) | Stelt de opmaak-eigenschappen voor.<br/>            Lezen/Schrijven [`IFormat`](/slides/python-net/nl/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/marker/) | Geeft een datamarker aan.<br/>            Alleen-lezen [`IMarker`](/slides/python-net/nl/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | Eigenschappen van het overeenkomstige legende-item in het geval van een diagramtype uit deze lijst:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Alleen-lezen [`ILegendEntryProperties`](/slides/python-net/nl/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/set_as_total/) | Stelt het gegevenspunt in als totaal. Alleen van toepassing op Waterfall-serietype. |
| [`invert_if_negative`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Geeft aan dat het gegevenspunt zijn kleuren moet omkeren als de waarde negatief is.<br/>            Lezen/Schrijven **bool**. |
| [`data_point_levels`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Retourneert de container van gegevenspuntniveaus. Van toepassing op Treeamp- en Sunburst-series.<br/>            Indexering van gegevenspuntniveaus begint bij nul. |
| [`index`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/index/) | Bepaalt op welke collectie van de onderliggende kinderen van de ouder dit gegevenspunt van toepassing is.<br/>            Lezen **int**. |
| [`actual_x`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Methoden

| Methode | Beschrijving |
| :- | :- |
| [`remove(self)`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/remove/#) | Verwijdert DataPoint uit de diagramreeks. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/nl/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Retourneert een automatische kleur van het gegevenspunt op basis van de seriële index, gegevenspuntindex, de eigenschap ParentSeriesGroup.IsColorVaried en de diagramstijl.<br/>            Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined. |

### Zie ook
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* bibliotheek [`Aspose.Slides`](/slides/python-net)