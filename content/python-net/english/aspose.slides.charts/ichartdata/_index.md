---
title: IChartData class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/
---


## IChartData class

Represents data used for a chart plotting.

The IChartData type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [chart_data_workbook](/slides/python-net/aspose.slides.charts/chart_data_workbook) | Gets the cells factory to create cells used for chart series or categories.<br/>            Read-only :py:class:`aspose.slides.charts.IChartDataWorkbook`. |
| [series](/slides/python-net/aspose.slides.charts/series) | Gets the series.<br/>            Read-only :py:class:`aspose.slides.charts.IChartSeriesCollection`. |
| [series_groups](/slides/python-net/aspose.slides.charts/series_groups) | Gets the groups of series.<br/>            Read-only :py:class:`aspose.slides.charts.IChartSeriesGroupCollection`. |
| [categories](/slides/python-net/aspose.slides.charts/categories) | Gets the primary categories (or both primary and secondary categories <br/>            if :py:attr:`aspose.slides.charts.IChartData.use_secondary_categories` property is false).<br/>            Read-only :py:class:`aspose.slides.charts.IChartCategoryCollection`. |
| [use_secondary_categories](/slides/python-net/aspose.slides.charts/use_secondary_categories) | If false then :py:attr:`aspose.slides.charts.IChartData.secondary_categories` property return null and data <br/>            in :py:attr:`aspose.slides.charts.IChartData.categories` property is used both for primary and secondary series.<br/>            If true then data in :py:attr:`aspose.slides.charts.IChartData.secondary_categories` property is used for secondary series and data <br/>            in :py:attr:`aspose.slides.charts.IChartData.categories` property is used for primary series.<br/>            Read/write :py:class:`bool`. |
| [secondary_categories](/slides/python-net/aspose.slides.charts/secondary_categories) | Gets the secondary categories if :py:attr:`aspose.slides.charts.IChartData.use_secondary_categories` property is true.<br/>            Read-only :py:class:`aspose.slides.charts.IChartCategoryCollection`. |
| [data_source_type](/slides/python-net/aspose.slides.charts/data_source_type) | Represents data source of the chart |
| [external_workbook_path](/slides/python-net/aspose.slides.charts/external_workbook_path) | Represents external workbook path if data source is external, null otherwise |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.charts/ichartdata/#string) | Sets external workbook as a data source for the chart. Chart data will be updated from the target workbook. |
| [__init__](/slides/python-net/aspose.slides.charts/ichartdata/#string-bool) | Sets external workbook as a data source for the chart. |
| [__init__](/slides/python-net/aspose.slides.charts/ichartdata/#string) | Set chart data range. Series and categories will be updated based on new data range.<br/>            If amount of series in data range greater than count of series in the chart data then additional series with the same type<br/>            as a last series in the current collection will be added to the end of the collection. |
| [__init__](/slides/python-net/aspose.slides.charts/ichartdata/#) | Gets chart data range. |
| [__init__](/slides/python-net/aspose.slides.charts/ichartdata/#) | Swap the data over the axis.<br/>            Data being charted on the X axis will move to the Y axis and vice versa. |

