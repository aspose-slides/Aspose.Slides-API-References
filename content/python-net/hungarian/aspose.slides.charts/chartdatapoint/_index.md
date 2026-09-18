---
title: ChartDataPoint class
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint osztály

A sor adatszám pontot képviseli.

A ChartDataPoint típus a következő tagokat teszi közzé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`x_value`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/x_value/) | XValue.<br/>            Csak olvasható [`IStringOrDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/y_value/) | YValue.<br/>            Csak olvasható [`IDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/bubble_size/) | BubbleSize.<br/>            Csak olvasható [`IDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/value/) | Value.<br/>            Csak olvasható [`IDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/size_value/) | Visszaadja a diagram adatszám pont méretértékét.<br/>            A Treemap és Sunburst diagramoknál használható.<br/>            Csak olvasható [`IDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/color_value/) | Visszaadja a diagram adatszám pont színértékét.<br/>            A Térképdiagramoknál használható.<br/>            Csak olvasható [`IDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/error_bars_custom_values/) | A sor hibasáv értékeit ábrázolja egyedi értéktípus esetén.<br/>            Csak olvasható [`IErrorBarsCustomValues`](/slides/python-net/hu/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/label/) | Címke.<br/>            Csak olvasható [`IDataLabel`](/slides/python-net/hu/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/is_bubble_3d/) | Meghatározza, hogy a buborékokra 3D hatás legyen alkalmazva.<br/>            Olvasás/írás **bool**. |
| [`explosion`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/explosion/) | Megadja, hogy az adatpont mennyivel legyen eltolva a kördiagram középpontjától.<br/>            Olvasás/írás **int**. |
| [`format`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/format/) | A formázási tulajdonságokat képviseli.<br/>            Olvasás/írás [`IFormat`](/slides/python-net/hu/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/marker/) | Adatjelölőt határoz meg.<br/>            Csak olvasható [`IMarker`](/slides/python-net/hu/aspose.slides.charts/imarker). |
| [`set_as_total`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/set_as_total/) | Beállítja az adatpontot összegként. Csak a Waterfall sor típusnál alkalmazható. |
| [`related_legend_entry`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/related_legend_entry/) | Az adott diagramtípushoz tartozó jelmagyarázat bejegyzés tulajdonságai:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Csak olvasható [`ILegendEntryProperties`](/slides/python-net/hu/aspose.slides.charts/ilegendentryproperties). |
| [`data_point_levels`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/data_point_levels/) | Visszaadja az adatpont szintek tárolóját. Treeamp és Sunburst soroknál alkalmazható.<br/>            Az adatpont szintek indexelése nullától indul. |
| [`index`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/index/) |  |
| [`invert_if_negative`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/invert_if_negative/) | Megadja, hogy a negatív érték esetén a színek invertálódjanak.<br/>            Olvasás/írás **bool**. |
| [`actual_x`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/actual_x/) | Meghatározza a diagram elem tényleges x helyzetét (balra) a diagram bal felső sarkához képest.<br/>            Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez.<br/>            Csak **float**. |
| [`actual_y`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/actual_y/) | Meghatározza a diagram elem tényleges felső helyzetét a diagram bal felső sarkához képest.<br/>            Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez.<br/>            Csak **float**. |
| [`actual_width`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/actual_width/) | Meghatározza a diagram elem tényleges szélességét. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez.<br/>            Csak **float**. |
| [`actual_height`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/actual_height/) | Meghatározza a diagram elem tényleges magasságát. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez.<br/>            Csak **float**. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`remove(self)`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/remove/#) | Eltávolítja a DataPoint-ot a diagram sorból. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/hu/aspose.slides.charts/chartdatapoint/get_automatic_data_point_color/#) | Visszaad egy automatikus színt az adatponthoz a sor index, adatpont index, ParentSeriesGroup.IsColorVaried tulajdonság és a diagram stílus alapján.<br/>            Ez a szín lesz az alapértelmezett, ha a FillType NotDefined értékre van állítva. |

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)