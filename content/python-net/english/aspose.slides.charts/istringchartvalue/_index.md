---
title: IStringChartValue class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/
---


## IStringChartValue class

Represent string value which can be stored in pptx presentation document in two ways:
            1) in cell/cells of workbook related to chart;
            2) as literal value.

The IStringChartValue type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [as_literal_string](/slides/python-net/aspose.slides.charts/as_literal_string) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals.<br/>            Read/write :py:class:`System.String`. |
| [as_i_multiple_cell_chart_value](/slides/python-net/aspose.slides.charts/as_i_multiple_cell_chart_value) | Allows to get base IMultipleCellChartValue interface.<br/>            Read-only :py:class:`aspose.slides.charts.IMultipleCellChartValue`. |
| [as_cells](/slides/python-net/aspose.slides.charts/as_cells) |  |
| [as_i_base_chart_value](/slides/python-net/aspose.slides.charts/as_i_base_chart_value) |  |
| [data_source_type](/slides/python-net/aspose.slides.charts/data_source_type) |  |
| [data](/slides/python-net/aspose.slides.charts/data) |  |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.charts/istringchartvalue/#) | Returns string representation. |
| [__init__](/slides/python-net/aspose.slides.charts/istringchartvalue/#IChartDataCell) | Sets value from specified cell. |
| [__init__](/slides/python-net/aspose.slides.charts/istringchartvalue/#) | If DataSourceType property is DataSourceType.Worksheet then this method returns address<br/>            of the cells in workbook which represent the string data. Otherwise return<br/>            empty string. |

