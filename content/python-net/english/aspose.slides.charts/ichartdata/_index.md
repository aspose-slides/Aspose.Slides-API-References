---
title: IChartData class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/ichartdata/
---


## IChartData class

Represents data used for a chart plotting.

The IChartData type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/aspose.slides.charts/ichartdata/chart_data_workbook/) | Gets the cells factory to create cells used for chart series or categories.<br/>            Read-only [`IChartDataWorkbook`](/slides/python-net/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/aspose.slides.charts/ichartdata/series/) | Gets the series.<br/>            Read-only [`IChartSeriesCollection`](/slides/python-net/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/aspose.slides.charts/ichartdata/series_groups/) | Gets the groups of series.<br/>            Read-only [`IChartSeriesGroupCollection`](/slides/python-net/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/aspose.slides.charts/ichartdata/categories/) | Gets the primary categories (or both primary and secondary categories <br/>            if [`IChartData.use_secondary_categories`](/slides/python-net/aspose.slides.charts/ichartdata#use_secondary_categories) property is false).<br/>            Read-only [`IChartCategoryCollection`](/slides/python-net/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/aspose.slides.charts/ichartdata/use_secondary_categories/) | If false then [`IChartData.secondary_categories`](/slides/python-net/aspose.slides.charts/ichartdata#secondary_categories) property return null and data <br/>            in [`IChartData.categories`](/slides/python-net/aspose.slides.charts/ichartdata#categories) property is used both for primary and secondary series.<br/>            If true then data in [`IChartData.secondary_categories`](/slides/python-net/aspose.slides.charts/ichartdata#secondary_categories) property is used for secondary series and data <br/>            in [`IChartData.categories`](/slides/python-net/aspose.slides.charts/ichartdata#categories) property is used for primary series.<br/>            Read/write **bool**. |
| [`secondary_categories`](/slides/python-net/aspose.slides.charts/ichartdata/secondary_categories/) | Gets the secondary categories if [`IChartData.use_secondary_categories`](/slides/python-net/aspose.slides.charts/ichartdata#use_secondary_categories) property is true.<br/>            Read-only [`IChartCategoryCollection`](/slides/python-net/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/aspose.slides.charts/ichartdata/data_source_type/) | Represents data source of the chart |
| [`external_workbook_path`](/slides/python-net/aspose.slides.charts/ichartdata/external_workbook_path/) | Represents external workbook path if data source is external, null otherwise |

## Methods

| Method | Description |
| :- | :- |
| [`set_external_workbook`](/slides/python-net/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Sets external workbook as a data source for the chart. Chart data will be updated from the target workbook. |
| [`set_external_workbook`](/slides/python-net/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Sets external workbook as a data source for the chart. |
| [`set_range`](/slides/python-net/aspose.slides.charts/ichartdata/set_range/#str) | Set chart data range. Series and categories will be updated based on new data range.<br/>            If amount of series in data range greater than count of series in the chart data then additional series with the same type<br/>            as a last series in the current collection will be added to the end of the collection. |
| [`get_range`](/slides/python-net/aspose.slides.charts/ichartdata/get_range/#) | Gets chart data range. |
| [`switch_row_column`](/slides/python-net/aspose.slides.charts/ichartdata/switch_row_column/#) | Swap the data over the axis.<br/>            Data being charted on the X axis will move to the Y axis and vice versa. |

### See Also
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)
