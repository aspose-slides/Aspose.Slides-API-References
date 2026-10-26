---
title: ChartData class
second_title: Aspose.Slides dla Pythona poprzez .NET – odwołanie API
description: 
type: docs
url: /pl/aspose.slides.charts/chartdata/
---
## ChartData klasa

Reprezentuje dane używane do tworzenia wykresu.

Typ ChartData udostępnia następujące elementy:

## Właściwości

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/pl/aspose.slides.charts/chartdata/chart_data_workbook/) | Pobiera fabrykę komórek służącą do tworzenia komórek używanych w seriach wykresu lub kategoriach.<br/>            Tylko do odczytu [`IChartDataWorkbook`](/slides/python-net/pl/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/pl/aspose.slides.charts/chartdata/series/) | Pobiera series.<br/>            Tylko do odczytu [`IChartSeriesCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/pl/aspose.slides.charts/chartdata/series_groups/) | Pobiera groups of series.<br/>            Tylko do odczytu [`IChartSeriesGroupCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/categories/) | Pobiera primary categories (or both primary and secondary categories <br/>            if [`ChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories) property is false).<br/>            Tylko do odczytu [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories/) | If false then [`ChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/secondary_categories) property return None and data <br/>            in [`ChartData.categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/categories) property is used both for primary and secondary series.<br/>            If true then data in [`ChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/secondary_categories) property is used for secondary series and data <br/>            in [`ChartData.categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/categories) property is used for primary series.<br/>            Odczyt/zapis **bool**. |
| [`secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/secondary_categories/) | Pobiera secondary categories if [`ChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories) property is true.<br/>            Tylko do odczytu [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/pl/aspose.slides.charts/chartdata/data_source_type/) | Reprezentuje external workbook path if external data source, None otherwise |
| [`external_workbook_path`](/slides/python-net/pl/aspose.slides.charts/chartdata/external_workbook_path/) | Reprezentuje data source of the chart |
| [`embedded_workbook_type`](/slides/python-net/pl/aspose.slides.charts/chartdata/embedded_workbook_type/) | Pobiera type of the embedded workbook.<br/>            Returns [`WorkbookType.NOT_DEFINED`](/slides/python-net/pl/aspose.slides.charts/workbooktype/NOT_DEFINED) if [`ChartData.data_source_type`](/slides/python-net/pl/aspose.slides.charts/chartdata/data_source_type) is <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/pl/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Tylko do odczytu [`WorkbookType`](/slides/python-net/pl/aspose.slides.charts/workbooktype). |

## Metody

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/pl/aspose.slides.charts/chartdata/set_external_workbook/#str) | Sets external workbook as a data source for the chart. Chart data will be updated from the target workbook. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/pl/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Sets external workbook as a data source for the chart. |
| [`read_workbook_stream(self)`](/slides/python-net/pl/aspose.slides.charts/chartdata/read_workbook_stream/#) | Writes the internally contained Excel workbook it into an stream. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/pl/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Initializes the internally contained Excel workbook with user-specified value. |
| [`get_range(self)`](/slides/python-net/pl/aspose.slides.charts/chartdata/get_range/#) | Gets chart data range. |
| [`set_range(self, formula)`](/slides/python-net/pl/aspose.slides.charts/chartdata/set_range/#str) | Set chart data range. Series and categories will be updated based on new data range.<br/>            If amount of series in data range greater than count of series in the chart data then additional series with the same type<br/>            as a last series in the current collection will be added to the end of the collection. |
| [`switch_row_column(self)`](/slides/python-net/pl/aspose.slides.charts/chartdata/switch_row_column/#) | Swap the data over the axis.<br/>            Data being charted on the X axis will move to the Y axis and vice versa. |

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)