---
title: IChartDataPoint class
second_title: Aspose.Slides Pythonhoz a .NET API-n keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint osztály

A sorozat adatpontját reprezentálja.

Az IChartDataPoint típus a következő tagokat teszi közzé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`x_value`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/x_value/) | Visszaadja a diagram adatpontjának x értékét.<br/>            Csak olvasható [`IStringOrDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/istringordoublechartvalue). |
| [`y_value`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/y_value/) | Visszaadja a diagram adatpontjának y értékét.<br/>            Csak olvasható [`IDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/idoublechartvalue). |
| [`bubble_size`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/bubble_size/) | Visszaadja a diagram adatpontjának buborékméretét.<br/>            Csak olvasható [`IDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/idoublechartvalue). |
| [`value`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/value/) | Visszaadja a diagram adatpontjának értékét.<br/>            Csak olvasható [`IDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/idoublechartvalue). |
| [`size_value`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/size_value/) | Visszaadja a diagram adatpontjának méretértékét.<br/>            A Treemap és Sunburst diagramoknál használatos. <br/>            Csak olvasható [`IDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/idoublechartvalue). |
| [`color_value`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/color_value/) | Visszaadja a diagram adatpontjának színértékét.<br/>            A Térkép diagramoknál használatos. <br/>            Csak olvasható [`IDoubleChartValue`](/slides/python-net/hu/aspose.slides.charts/idoublechartvalue). |
| [`error_bars_custom_values`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/error_bars_custom_values/) | Sorozati hibasávok értékeit reprezentálja Custom értéktípus esetén.<br/>            Csak olvasható [`IErrorBarsCustomValues`](/slides/python-net/hu/aspose.slides.charts/ierrorbarscustomvalues). |
| [`label`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/label/) | A diagram adatpontjának címkéjét reprezentálja.<br/>            Csak olvasható [`IDataLabel`](/slides/python-net/hu/aspose.slides.charts/idatalabel). |
| [`is_bubble_3d`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/is_bubble_3d/) | Megadja, hogy a buborékokra 3-D hatás legyen alkalmazva.<br/>            Olvasás/írás **bool**. |
| [`explosion`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/explosion/) | Megadja, hogy mennyivel kerül a adatpont eltolásra a kördiagram középpontjától.<br/>            Olvasás/írás **int**. |
| [`format`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/format/) | A formázási tulajdonságokat reprezentálja.<br/>            Olvasás/írás [`IFormat`](/slides/python-net/hu/aspose.slides.charts/iformat). |
| [`marker`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/marker/) | Egy adatjelölőt specifikál.<br/>            Csak olvasható [`IMarker`](/slides/python-net/hu/aspose.slides.charts/imarker). |
| [`related_legend_entry`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/related_legend_entry/) | A megfelelő jelmagyarázat bejegyzés tulajdonságait adja vissza a következő diagramtípusok esetén:<br/>            ChartType.BarOfPie,<br/>            ChartType.ExplodedPie,<br/>            ChartType.ExplodedPie3D,<br/>            ChartType.Pie,<br/>            ChartType.Pie3D,<br/>            ChartType.PieOfPie.<br/>            Csak olvasható [`ILegendEntryProperties`](/slides/python-net/hu/aspose.slides.charts/ilegendentryproperties). |
| [`set_as_total`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/set_as_total/) | Az adatpontot összegként állítja be. Csak a Waterfall sorozattípusra alkalmazható. |
| [`invert_if_negative`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/invert_if_negative/) | Megadja, hogy a adatpont negatív érték esetén megfordítja a színeket.<br/>            Olvasás/írás **bool**. |
| [`data_point_levels`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/data_point_levels/) | Visszaadja az adatpont szintjeinek tárolóját. A Treeamp és Sunburst sorozatoknál alkalmazható.<br/>            Az adatpont szintek indexelése nulláral kezdődik. |
| [`index`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/index/) | Meghatározza, hogy a szülő gyerekeinek gyűjteményének melyik részére vonatkozik ez az adatpont.<br/>            Csak **int**. |
| [`actual_x`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/actual_x/) |  |
| [`actual_y`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/actual_y/) |  |
| [`actual_width`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/actual_width/) |  |
| [`actual_height`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/actual_height/) |  |

## Metódusok

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/remove/#) | Eltávolítja az adatpontot a diagram sorozatból. |
| [`get_automatic_data_point_color(self)`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint/get_automatic_data_point_color/#) | Visszaad egy automatikus színt az adatponthoz a sorozat index, adatpont index, a ParentSeriesGroup.IsColorVaried tulajdonság és a diagram stílus alapján.<br/>            Ez a szín az alapértelmezett, ha a FillType értéke NotDefined. |


### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)