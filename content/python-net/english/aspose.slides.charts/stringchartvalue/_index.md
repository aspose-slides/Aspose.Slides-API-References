---
title: StringChartValue
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/stringchartvalue/
---


StringChartValue class

Represent string value which can be stored in pptx presentation document in two ways:
            1) in cell/cells of workbook related to chart;
            2) as literal value.

**Inheritance:**[`StringChartValue`](/slides/python-net/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/aspose.slides.charts/basechartvalue)

The StringChartValue type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [data_source_type](/slides/python-net/aspose.slides.charts/stringchartvalue/data_source_type/) | Specifies whether AsCell, AsCells, AsLiteralString or AsLiteralDouble <br/>            property is actual in descendants. In other words it specifies the type <br/>            of value of the Data property.<br/>            Read/write [`DataSourceType`](/slides/python-net/aspose.slides.charts/datasourcetype). |
| [data](/slides/python-net/aspose.slides.charts/stringchartvalue/data/) | Returns or sets Data object.<br/>            Read/write .NET type System.Object. |
| [as_cells](/slides/python-net/aspose.slides.charts/stringchartvalue/as_cells/) | Null value assigning is not allowed.<br/>            Returning value always is not null.<br/>            Read/write [`IChartCellCollection`](/slides/python-net/aspose.slides.charts/ichartcellcollection). |
| [as_literal_string](/slides/python-net/aspose.slides.charts/stringchartvalue/as_literal_string/) | Returns or sets value as literal string.<br/>            Read/write .NET type System.String. |
| [as_i_multiple_cell_chart_value](/slides/python-net/aspose.slides.charts/stringchartvalue/as_i_multiple_cell_chart_value/) |  |
| [as_i_base_chart_value](/slides/python-net/aspose.slides.charts/stringchartvalue/as_i_base_chart_value/) |  |

## Methods

| Method | Description |
| :- | :- |
| [set_from_one_cell](/slides/python-net/aspose.slides.charts/stringchartvalue/stringchartvalue/#IChartDataCell/) | Sets value from specified cell. |
| [get_cells_address_in_workbook](/slides/python-net/aspose.slides.charts/stringchartvalue/stringchartvalue/#/) | If DataSourceType property is DataSourceType.Worksheet then this method returns address<br/>            of the cells in workbook which represent the string data. Otherwise return<br/>            empty string. |

