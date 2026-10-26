---
title: ChartData class
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/chartdata/
---
## ChartData osztály

Represents data used for a chart plotting.

The ChartData type exposes the following members:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/hu/aspose.slides.charts/chartdata/chart_data_workbook/) | Visszaadja a cellák gyárát a diagram sorozatokhoz vagy kategóriákhoz használt cellák létrehozásához.<br/>            Csak olvasható [`IChartDataWorkbook`](/slides/python-net/hu/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/hu/aspose.slides.charts/chartdata/series/) | Visszaadja a sorozatokat.<br/>            Csak olvasható [`IChartSeriesCollection`](/slides/python-net/hu/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/hu/aspose.slides.charts/chartdata/series_groups/) | Visszaadja a sorozatok csoportjait.<br/>            Csak olvasható [`IChartSeriesGroupCollection`](/slides/python-net/hu/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/categories/) | Visszaadja az elsődleges kategóriákat (vagy az elsődleges és másodlagos kategóriákat <br/>            ha a [`ChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/use_secondary_categories) tulajdonság hamis).<br/>            Csak olvasható [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/use_secondary_categories/) | Ha hamis, akkor a [`ChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/secondary_categories) tulajdonság None-t ad vissza, és a [`ChartData.categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/categories) tulajdonságban szereplő adat mind az elsődleges, mind a másodlagos sorozatokhoz használható.<br/>            Ha igaz, akkor a [`ChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/secondary_categories) tulajdonságban szereplő adat a másodlagos sorozatokhoz, a [`ChartData.categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/categories) tulajdonságban szereplő adat pedig az elsődleges sorozatokhoz használható.<br/>            Olvasás/írás **bool**. |
| [`secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/secondary_categories/) | Visszaadja a másodlagos kategóriákat, ha a [`ChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/use_secondary_categories) tulajdonság igaz.<br/>            Csak olvasható [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/hu/aspose.slides.charts/chartdata/data_source_type/) | Külső munkafüzet útvonalát jelöli, ha külső adatforrás, egyébként None. |
| [`external_workbook_path`](/slides/python-net/hu/aspose.slides.charts/chartdata/external_workbook_path/) | A diagram adatforrását jelöli. |
| [`embedded_workbook_type`](/slides/python-net/hu/aspose.slides.charts/chartdata/embedded_workbook_type/) | Visszaadja a beágyazott munkafüzet típusát.<br/>            [`WorkbookType.NOT_DEFINED`](/slides/python-net/hu/aspose.slides.charts/workbooktype/NOT_DEFINED)-t ad vissza, ha a [`ChartData.data_source_type`](/slides/python-net/hu/aspose.slides.charts/chartdata/data_source_type) <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/hu/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Csak olvasható [`WorkbookType`](/slides/python-net/hu/aspose.slides.charts/workbooktype). |

## Módszerek

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/hu/aspose.slides.charts/chartdata/set_external_workbook/#str) | Beállítja a külső munkafüzetet a diagram adatforrásaként. A diagram adatai a célmunkafüzetből frissülnek. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/hu/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Beállítja a külső munkafüzetet a diagram adatforrásaként. |
| [`read_workbook_stream(self)`](/slides/python-net/hu/aspose.slides.charts/chartdata/read_workbook_stream/#) | Az belsőleg tartalmazott Excel munkafüzetet egy adatfolyamba írja. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/hu/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Inicializálja a belsőleg tartalmazott Excel munkafüzetet a felhasználó által megadott értékkel. |
| [`get_range(self)`](/slides/python-net/hu/aspose.slides.charts/chartdata/get_range/#) | Visszaadja a diagram adatbérletét. |
| [`set_range(self, formula)`](/slides/python-net/hu/aspose.slides.charts/chartdata/set_range/#str) | Beállítja a diagram adatbérletét. A sorozatok és kategóriák az új adatbérlet alapján frissülnek.<br/>            Ha az adatbérletben lévő sorozatok száma nagyobb, mint a diagram adatainak sorozatszáma, akkor további sorozatok, a jelenlegi gyűjtemény utolsó sorozatának típusával megegyező típusú, hozzá lesznek adva a gyűjtemény végéhez. |
| [`switch_row_column(self)`](/slides/python-net/hu/aspose.slides.charts/chartdata/switch_row_column/#) | Az adatokat felcseréli a tengelyek között.<br/>            Az X tengelyen ábrázolt adatok az Y tengelyre, és fordítva kerülnek. |

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)