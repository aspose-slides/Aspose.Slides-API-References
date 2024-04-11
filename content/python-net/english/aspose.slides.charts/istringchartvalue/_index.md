---
title: IStringChartValue
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/istringchartvalue/
---


IStringChartValue class

Represent string value which can be stored in pptx presentation document in two ways:
            1) in cell/cells of workbook related to chart;
            2) as literal value.

The IStringChartValue type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [as_literal_string](/slides/python-net/aspose.slides.charts/istringchartvalue/as_literal_string/) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals.<br/>            Read/write .NET type System.String. |
| [as_i_multiple_cell_chart_value](/slides/python-net/aspose.slides.charts/istringchartvalue/as_i_multiple_cell_chart_value/) | Allows to get base IMultipleCellChartValue interface.<br/>            Read-only [`IMultipleCellChartValue`](/slides/python-net/aspose.slides.charts/imultiplecellchartvalue). |
| [as_cells](/slides/python-net/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [as_i_base_chart_value](/slides/python-net/aspose.slides.charts/istringchartvalue/as_i_base_chart_value/) |  |
| [data_source_type](/slides/python-net/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [data](/slides/python-net/aspose.slides.charts/istringchartvalue/data/) |  |

## Methods

| Method | Description |
| :- | :- |
| [to_string](/slides/python-net/aspose.slides.charts/istringchartvalue/to_string/#) | Returns string representation. |
| [set_from_one_cell](/slides/python-net/aspose.slides.charts/istringchartvalue/set_from_one_cell/#IChartDataCell) | Sets value from specified cell. |
| [get_cells_address_in_workbook](/slides/python-net/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | If DataSourceType property is DataSourceType.Worksheet then this method returns address<br/>            of the cells in workbook which represent the string data. Otherwise return<br/>            empty string. |

