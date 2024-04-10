---
title: ChartData
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/chartdata/
---


ChartData class

Represents data used for a chart plotting.

The ChartData type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [chart_data_workbook](/slides/python-net/aspose.slides.charts/chartdata/chart_data_workbook/) | Gets the cells factory to create cells used for chart series or categories.<br/>            Read-only :py:class:`aspose.slides.charts.IChartDataWorkbook`. |
| [series](/slides/python-net/aspose.slides.charts/chartdata/series/) | Gets the series.<br/>            Read-only :py:class:`aspose.slides.charts.IChartSeriesCollection`. |
| [series_groups](/slides/python-net/aspose.slides.charts/chartdata/series_groups/) | Gets the groups of series.<br/>            Read-only :py:class:`aspose.slides.charts.IChartSeriesGroupCollection`. |
| [categories](/slides/python-net/aspose.slides.charts/chartdata/categories/) | Gets the primary categories (or both primary and secondary categories <br/>            if :py:attr:`aspose.slides.charts.ChartData.use_secondary_categories` property is false).<br/>            Read-only :py:class:`aspose.slides.charts.IChartCategoryCollection`. |
| [use_secondary_categories](/slides/python-net/aspose.slides.charts/chartdata/use_secondary_categories/) | If false then :py:attr:`aspose.slides.charts.ChartData.secondary_categories` property return null and data <br/>            in :py:attr:`aspose.slides.charts.ChartData.categories` property is used both for primary and secondary series.<br/>            If true then data in :py:attr:`aspose.slides.charts.ChartData.secondary_categories` property is used for secondary series and data <br/>            in :py:attr:`aspose.slides.charts.ChartData.categories` property is used for primary series.<br/>            Read/write :py:class:`bool`. |
| [secondary_categories](/slides/python-net/aspose.slides.charts/chartdata/secondary_categories/) | Gets the secondary categories if :py:attr:`aspose.slides.charts.ChartData.use_secondary_categories` property is true.<br/>            Read-only :py:class:`aspose.slides.charts.IChartCategoryCollection`. |
| [data_source_type](/slides/python-net/aspose.slides.charts/chartdata/data_source_type/) | Represents external workbook path if external data source, null otherwise |
| [external_workbook_path](/slides/python-net/aspose.slides.charts/chartdata/external_workbook_path/) | Represents data source of the chart |

## Methods

| Method | Description |
| :- | :- |
| [set_external_workbook](/slides/python-net/aspose.slides.charts/chartdata/chartdata/#string/) | Sets external workbook as a data source for the chart. Chart data will be updated from the target workbook. |
| [set_external_workbook](/slides/python-net/aspose.slides.charts/chartdata/chartdata/#string-bool/) | Sets external workbook as a data source for the chart. |
| [get_range](/slides/python-net/aspose.slides.charts/chartdata/chartdata/#/) | Gets chart data range. |
| [set_range](/slides/python-net/aspose.slides.charts/chartdata/chartdata/#string/) | Set chart data range. Series and categories will be updated based on new data range.<br/>            If amount of series in data range greater than count of series in the chart data then additional series with the same type<br/>            as a last series in the current collection will be added to the end of the collection. |
| [switch_row_column](/slides/python-net/aspose.slides.charts/chartdata/chartdata/#/) | Swap the data over the axis.<br/>            Data being charted on the X axis will move to the Y axis and vice versa. |

