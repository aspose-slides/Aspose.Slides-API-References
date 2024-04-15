---
title: ChartDataCell class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/chartdatacell/
---


## ChartDataCell class

Represents cell for chart data.

The ChartDataCell type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`row`](/slides/python-net/aspose.slides.charts/chartdatacell/row/) | Returns the index of the row of worksheet in which the cell is located.<br/>            Read-only **int**. |
| [`column`](/slides/python-net/aspose.slides.charts/chartdatacell/column/) | Returns the index of the column of worksheet in which the cell is located.<br/>            Read-only **int**. |
| [`value`](/slides/python-net/aspose.slides.charts/chartdatacell/value/) | Gets or sets the value of a cell.<br/>            Read/write **any**. |
| [`formula`](/slides/python-net/aspose.slides.charts/chartdatacell/formula/) | Gets or sets the formula in A1-style. |
| [`r1c1_formula`](/slides/python-net/aspose.slides.charts/chartdatacell/r1c1_formula/) | Gets or sets the formula in R1C1-style. |
| [`chart_data_worksheet`](/slides/python-net/aspose.slides.charts/chartdatacell/chart_data_worksheet/) | Gets the worksheet.<br/>            Read-only [`IChartDataWorksheet`](/slides/python-net/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/aspose.slides.charts/chartdatacell/is_hidden/) | Determines whether the cell is hidden.<br/>            Read-only **bool**. |
| [`custom_number_format`](/slides/python-net/aspose.slides.charts/chartdatacell/custom_number_format/) | Gets or sets the custom display format of numbers and dates. <br/>            If value is empty will be used PresetNumberFormat value.<br/>            Read/write **str**. |
| [`preset_number_format`](/slides/python-net/aspose.slides.charts/chartdatacell/preset_number_format/) | Gets or sets the built-in display format of numbers and dates. Preset number must be in [0..22] or [37..49].<br/>             Read/write **int**. |

## Methods

| Method | Description |
| :- | :- |
| [`calculate`](/slides/python-net/aspose.slides.charts/chartdatacell/calculate/#bool) | If the cell contains a formula, the value will be updated base on that formula. |

### See Also
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)
