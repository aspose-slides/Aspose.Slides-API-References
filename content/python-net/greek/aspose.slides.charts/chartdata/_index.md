---
title: ChartData class
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides.charts/chartdata/
---
## ChartData κλάση

Αναπαριστά δεδομένα που χρησιμοποιούνται για σχεδιασμό διαγράμματος.

Ο τύπος ChartData εκθέτει τα ακόλουθα μέλη:

## Ιδιότητες

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/el/aspose.slides.charts/chartdata/chart_data_workbook/) | Gets the cells factory to create cells used for chart series or categories.<br/>            Μόνο για ανάγνωση [`IChartDataWorkbook`](/slides/python-net/el/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/el/aspose.slides.charts/chartdata/series/) | Gets the series.<br/>            Μόνο για ανάγνωση [`IChartSeriesCollection`](/slides/python-net/el/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/el/aspose.slides.charts/chartdata/series_groups/) | Gets the groups of series.<br/>            Μόνο για ανάγνωση [`IChartSeriesGroupCollection`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/el/aspose.slides.charts/chartdata/categories/) | Gets the primary categories (or both primary and secondary categories <br/>            if [`ChartData.use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/use_secondary_categories) property is false).<br/>            Μόνο για ανάγνωση [`IChartCategoryCollection`](/slides/python-net/el/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/use_secondary_categories/) | If false then [`ChartData.secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/secondary_categories) property return None and data <br/>            in [`ChartData.categories`](/slides/python-net/el/aspose.slides.charts/chartdata/categories) property is used both for primary and secondary series.<br/>            If true then data in [`ChartData.secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/secondary_categories) property is used for secondary series and data <br/>            in [`ChartData.categories`](/slides/python-net/el/aspose.slides.charts/chartdata/categories) property is used for primary series.<br/>            Ανάγνωση/εγγραφή **bool**. |
| [`secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/secondary_categories/) | Gets the secondary categories if [`ChartData.use_secondary_categories`](/slides/python-net/el/aspose.slides.charts/chartdata/use_secondary_categories) property is true.<br/>            Μόνο για ανάγνωση [`IChartCategoryCollection`](/slides/python-net/el/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/el/aspose.slides.charts/chartdata/data_source_type/) | Represents external workbook path if external data source, None otherwise |
| [`external_workbook_path`](/slides/python-net/el/aspose.slides.charts/chartdata/external_workbook_path/) | Represents data source of the chart |
| [`embedded_workbook_type`](/slides/python-net/el/aspose.slides.charts/chartdata/embedded_workbook_type/) | Gets the type of the embedded workbook.<br/>            Returns [`WorkbookType.NOT_DEFINED`](/slides/python-net/el/aspose.slides.charts/workbooktype/NOT_DEFINED) if [`ChartData.data_source_type`](/slides/python-net/el/aspose.slides.charts/chartdata/data_source_type) is <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/el/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Μόνο για ανάγνωση [`WorkbookType`](/slides/python-net/el/aspose.slides.charts/workbooktype). |

## Μέθοδοι

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/el/aspose.slides.charts/chartdata/set_external_workbook/#str) | Sets external workbook as a data source for the chart. Chart data will be updated from the target workbook. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/el/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Sets external workbook as a data source for the chart. |
| [`read_workbook_stream(self)`](/slides/python-net/el/aspose.slides.charts/chartdata/read_workbook_stream/#) | Writes the internally contained Excel workbook it into an stream. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/el/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Initializes the internally contained Excel workbook with user-specified value. |
| [`get_range(self)`](/slides/python-net/el/aspose.slides.charts/chartdata/get_range/#) | Gets chart data range. |
| [`set_range(self, formula)`](/slides/python-net/el/aspose.slides.charts/chartdata/set_range/#str) | Set chart data range. Series and categories will be updated based on new data range.<br/>            If amount of series in data range greater than count of series in the chart data then additional series with the same type<br/>            as a last series in the current collection will be added to the end of the collection. |
| [`switch_row_column(self)`](/slides/python-net/el/aspose.slides.charts/chartdata/switch_row_column/#) | Swap the data over the axis.<br/>            Data being charted on the X axis will move to the Y axis and vice versa. |

### Δείτε επίσης
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)