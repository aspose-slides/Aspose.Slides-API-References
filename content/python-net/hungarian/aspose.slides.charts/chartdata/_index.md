---
title: ChartData class
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API referencia
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
| [`chart_data_workbook`](/slides/python-net/hu/aspose.slides.charts/chartdata/chart_data_workbook/) | Lekéri a cellagyárat a diagram sorozatokhoz vagy kategóriákhoz használt cellák létrehozásához.<br/>            Csak olvasható [`IChartDataWorkbook`](/slides/python-net/hu/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/hu/aspose.slides.charts/chartdata/series/) | Lekéri a sorozatokat.<br/>            Csak olvasható [`IChartSeriesCollection`](/slides/python-net/hu/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/hu/aspose.slides.charts/chartdata/series_groups/) | Lekéri a sorozatok csoportjait.<br/>            Csak olvasható [`IChartSeriesGroupCollection`](/slides/python-net/hu/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/categories/) | Lekéri az elsődleges kategóriákat (vagy az elsődleges és a másodlagos kategóriákat is, ha a [`ChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/use_secondary_categories) tulajdonság hamis).<br/>            Csak olvasható [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/use_secondary_categories/) | Ha hamis, akkor a [`ChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/secondary_categories) tulajdonság None értéket ad vissza, és a [`ChartData.categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/categories) tulajdonság adatait az elsődleges és a másodlagos sorozatokhoz egyaránt használják.<br/>            Ha igaz, akkor a [`ChartData.secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/secondary_categories) tulajdonság adatait a másodlagos sorozatokhoz, a [`ChartData.categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/categories) tulajdonság adatait pedig az elsődleges sorozatokhoz használják.<br/>            Olvasható/írható **bool**. |
| [`secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/secondary_categories/) | Lekéri a másodlagos kategóriákat, ha a [`ChartData.use_secondary_categories`](/slides/python-net/hu/aspose.slides.charts/chartdata/use_secondary_categories) tulajdonság igaz.<br/>            Csak olvasható [`IChartCategoryCollection`](/slides/python-net/hu/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/hu/aspose.slides.charts/chartdata/data_source_type/) | Külső munkafüzet útvonalát jelöli, ha külső adatforrás, egyébként None |
| [`external_workbook_path`](/slides/python-net/hu/aspose.slides.charts/chartdata/external_workbook_path/) | A diagram adatforrását jelöli |
| [`embedded_workbook_type`](/slides/python-net/hu/aspose.slides.charts/chartdata/embedded_workbook_type/) | Lekéri a beágyazott munkafüzet típusát.<br/>            Visszaadja a [`WorkbookType.NOT_DEFINED`](/slides/python-net/hu/aspose.slides.charts/workbooktype/NOT_DEFINED) értéket, ha a [`ChartData.data_source_type`](/slides/python-net/hu/aspose.slides.charts/chartdata/data_source_type) [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/hu/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Csak olvasható [`WorkbookType`](/slides/python-net/hu/aspose.slides.charts/workbooktype). |

## Metódusok

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/hu/aspose.slides.charts/chartdata/set_external_workbook/#str) | Beállítja a külső munkafüzetet a diagram adatforrásaként. A diagram adatai a cél munkafüzetből lesznek frissítve. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/hu/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Beállítja a külső munkafüzetet a diagram adatforrásaként. |
| [`read_workbook_stream(self)`](/slides/python-net/hu/aspose.slides.charts/chartdata/read_workbook_stream/#) | Az belsőleg tárolt Excel munkafüzetet egy adatfolyamba írja. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/hu/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Inicializálja a belsőleg tárolt Excel munkafüzetet a felhasználó által megadott értékkel. |
| [`get_range(self)`](/slides/python-net/hu/aspose.slides.charts/chartdata/get_range/#) | Lekéri a diagram adat-tartományt. |
| [`set_range(self, formula)`](/slides/python-net/hu/aspose.slides.charts/chartdata/set_range/#str) | Beállítja a diagram adat-tartományt. A sorozatok és a kategóriák az új adat-tartomány alapján lesznek frissítve.<br/>            Ha az adat-tartományban lévő sorozatok száma nagyobb, mint a diagram adataiban lévő sorozatok száma, akkor további sorozatok, az aktuális gyűjtemény utolsó sorozatának típusával megegyező, hozzá lesznek adva a gyűjtemény végéhez. |
| [`refresh_data(self)`](/slides/python-net/hu/aspose.slides.charts/chartdata/refresh_data/#) | Frissíti a diagram adatokat a forrás munkafüzetről való újratöltéssel. |
| [`switch_row_column(self)`](/slides/python-net/hu/aspose.slides.charts/chartdata/switch_row_column/#) | Az adatcserét a tengelyek között hajtja végre.<br/>            Az X tengelyen ábrázolt adatok a Y tengelyre kerülnek, és fordítva. |

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)