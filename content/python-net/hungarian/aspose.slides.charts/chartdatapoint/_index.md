---
title: ChartDataPoint class
second_title: Aspose.Slides Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint osztály

Sorozat adatpontot reprezentál.

A ChartDataPoint típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`x_value`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Csak olvasható [`IStringOrDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Csak olvasható [`IDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Csak olvasható [`IDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Csak olvasható [`IDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/size_value/) | Visszaadja a diagram adatpont méretértékét.<br/>            Treemap és Sunburst diagramoknál használható. <br/>            Csak olvasható [`IDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/color_value/) | Visszaadja a diagram adatpont színértékét.<br/>            Map diagramoknál használható. <br/>            Csak olvasható [`IDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | Sorozat hibasáv értékeket reprezentál Custom értéktípus esetén.<br/>            Csak olvasható [`IErrorBarsCustomValues`](/slides/python-net/hu/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/label/) | Label.<br/>            Csak olvasható [`IDataLabel`](/slides/python-net/hu/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Megadja, hogy a buborékokra 3-D hatás legyen alkalmazva.<br/>            Olvasás/írás **bool**. |
| [`explosion`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/explosion/) | Megadja, hogy mekkora mértékben legyen az adatpont eltolva a kördiagram középpontjától.<br/>            Olvasás/írás **int**. |
| [`format`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/format/) | Formázási tulajdonságokat reprezentál.<br/>            Olvasás/írás [`IFormat`](/slides/python-net/hu/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/marker/) | Megad egy adatjelölőt.<br/>            Csak olvasható [`IMarker`](/slides/python-net/hu/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/set_as_total/) | Az adatpontot összegként állítja be. Csak Waterfall sorozattípusnál alkalmazható. |
| [`related_legend_entry`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/related_legend_entry/) | A megfelelő jelmagyarázat bejegyzés tulajdonságai az alábbi diagramtípusok esetén:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Csak olvasható [`ILegendEntryProperties`](/slides/python-net/hu/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/data_point_levels/) | Visszaadja az adatpont szintek tárolóját. Treeamp és Sunburst sorozatoknál alkalmazható.<br/>            Az adatpont szintek indexelése nulláról indul. |
| [`index`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Megadja, hogy az adatpont fordítsa meg színeit, ha az érték negatív.<br/>            Olvasás/írás **bool**. |
| [`cached_value`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/cached_value/) | Lekéri a diagram adatpont gyorsítótárazott értékét.<br/>            Csak olvasható [`ICachedChartValue`](/slides/python-net/hu/aspose.slides.charts/icachedchartvalue). |
| [`cached_x_value`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/cached_x_value/) | Lekéri a diagram adatpont gyorsítótárazott X értékét.<br/>            Csak olvasható [`ICachedChartValue`](/slides/python-net/hu/aspose.slides.charts/icachedchartvalue). |
| [`cached_y_value`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/cached_y_value/) | Lekéri a diagram adatpont gyorsítótárazott Y értékét.<br/>            Csak olvasható [`ICachedChartValue`](/slides/python-net/hu/aspose.slides.charts/icachedchartvalue). |
| [`cached_bubble_size`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/cached_bubble_size/) | Lekéri a diagram adatpont gyorsítótárazott buborékméretét.<br/>            Csak olvasható [`ICachedChartValue`](/slides/python-net/hu/aspose.slides.charts/icachedchartvalue). |
| [`actual_x`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/actual_x/) | Megadja a diagram elem tényleges x helyzetét (bal), a diagram bal felső sarkához viszonyítva.<br/>            Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. <br/>            Olvas **float**. |
| [`actual_y`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/actual_y/) | Megadja a diagram elem tényleges felső pozícióját a diagram bal felső sarkához viszonyítva.<br/>            Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. <br/>            Olvas **float**. |
| [`actual_width`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/actual_width/) | Megadja a diagram elem tényleges szélességét. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. <br/>            Olvas **float**. |
| [`actual_height`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/actual_height/) | Megadja a diagram elem tényleges magasságát. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. <br/>            Olvas **float**. |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`remove(self)`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/remove/#) | Eltávolítja a DataPoint-ot a diagram sorozatból. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Visszaad egy automatikus színt az adatponthoz a sorozat index, adatpont index, a ParentSeriesGroup.IsColorVaried tulajdonság és a diagram stílus alapján.<br/>            Ez a szín alapértelmezésként használatos, ha a FillType értéke NotDefined. |

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)