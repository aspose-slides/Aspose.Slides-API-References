---
title: IChartData class
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/ichartdata/
---
## IChartData osztály

A diagram ábrázolásához használt adatokat képviseli.

Az IChartData típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/hu/aspose.slides.charts/ichartdata/chart_data_workbook/) | A cellagyár lekérdezése a diagram sorozatokhoz vagy kategóriákhoz használt cellák létrehozásához.<br/>            Csak olvasható [`IChartDataWorkbook`](/slides/python-net/hu/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/hu/aspose.slides.charts/ichartdata/series/) | A sorozatok lekérdezése.<br/>            Csak olvasható [`IChartSeriesCollection`](/slides/python-net/hu/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/hu/aspose.slides.charts/ichartdata/series_groups/) | A sorozatok csoportjainak lekérdezése.<br/>            Csak olvasható [`IChartSeriesGroupCollection`](/slides/python-net/hu/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/categories/) | Az elsődleges kategóriák lekérdezése (vagy az elsődleges és másodlagos kategóriák is <br/>            ha a [`IChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/use_secondary_categories) tulajdonság hamis).<br/>            Csak olvasható [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/use_secondary_categories/) | Ha hamis, akkor a [`IChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/secondary_categories) tulajdonság None értéket ad vissza, és az [`IChartData.categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/categories) tulajdonság adatait az elsődleges és másodlagos sorozatok egyaránt használják.<br/>            Ha igaz, akkor a [`IChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/secondary_categories) tulajdonság adatait a másodlagos sorozatok, a [`IChartData.categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/categories) tulajdonság adatait pedig az elsődleges sorozatok használják.<br/>            Olvasható/írható **bool**. |
| [`secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/secondary_categories/) | A másodlagos kategóriák lekérdezése, ha a [`IChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/ichartdata/use_secondary_categories) tulajdonság igaz.<br/>            Csak olvasható [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/hu/aspose.slides.charts/ichartdata/data_source_type/) | A diagram adatforrását képviseli |
| [`external_workbook_path`](/slides/python-net/hu/aspose.slides.charts/ichartdata/external_workbook_path/) | Külső munkafüzet útvonalát képviseli, ha az adatforrás külső, egyébként None |
| [`embedded_workbook_type`](/slides/python-net/hu/aspose.slides.charts/ichartdata/embedded_workbook_type/) | A beágyazott munkafüzet típusának lekérdezése.<br/>            [`WorkbookType.NOT_DEFINED`](/slides/python-net/hu/aspose.slides.charts/workbooktype/NOT_DEFINED) értéket ad vissza, ha a [`IChartData.data_source_type`](/slides/python-net/hu/aspose.slides.charts/ichartdata/data_source_type) <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/hu/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Csak olvasható [`WorkbookType`](/slides/python-net/hu/aspose.slides.charts/workbooktype). |

## Metódusok

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/hu/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Beállítja a külső munkafüzetet a diagram adatforrásaként. A diagram adatai a cél munkafüzetről lesznek frissítve. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/hu/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Beállítja a külső munkafüzetet a diagram adatforrásaként. |
| [`read_workbook_stream(self)`](/slides/python-net/hu/aspose.slides.charts/ichartdata/read_workbook_stream/#) | A belső Excel munkafüzetet egy memóriában lévő adatfolyamba írja. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/hu/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | A belső Excel munkafüzetet felhasználó által megadott értékkel inicializálja. |
| [`set_range(self, formula)`](/slides/python-net/hu/aspose.slides.charts/ichartdata/set_range/#str) | Állítsa be a diagram adat tartományát. A sorozatok és kategóriák az új adat tartomány alapján frissülnek.<br/>            Ha az adat tartományban lévő sorozatok száma nagyobb, mint a diagram adatban lévő sorozatok száma, akkor további sorozatok ugyanazzal a típussal,<br/>            mint az aktuális gyűjtemény utolsó sorozata, a gyűjtemény végéhez lesznek hozzáadva. |
| [`get_range(self)`](/slides/python-net/hu/aspose.slides.charts/ichartdata/get_range/#) | A diagram adat tartomány lekérdezése. |
| [`switch_row_column(self)`](/slides/python-net/hu/aspose.slides.charts/ichartdata/switch_row_column/#) | Az adat cseréje a tengelyek között.<br/>            Az X tengelyen ábrázolt adat a Y tengelyre kerül, és fordítva. |

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)