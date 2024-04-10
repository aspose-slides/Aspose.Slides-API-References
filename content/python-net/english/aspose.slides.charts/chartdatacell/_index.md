---
title: ChartDataCell class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/
---


## ChartDataCell class

Represents cell for chart data.

The ChartDataCell type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [row](/slides/python-net/aspose.slides.charts/row) | Returns the index of the row of worksheet in which the cell is located.<br/>            Read-only :py:class:`int`. |
| [column](/slides/python-net/aspose.slides.charts/column) | Returns the index of the column of worksheet in which the cell is located.<br/>            Read-only :py:class:`int`. |
| [value](/slides/python-net/aspose.slides.charts/value) | Gets or sets the value of a cell.<br/>            Read/write :py:class:`any`. |
| [formula](/slides/python-net/aspose.slides.charts/formula) | Gets or sets the formula in A1-style. |
| [r1c1_formula](/slides/python-net/aspose.slides.charts/r1c1_formula) | Gets or sets the formula in R1C1-style. |
| [chart_data_worksheet](/slides/python-net/aspose.slides.charts/chart_data_worksheet) | Gets the worksheet.<br/>            Read-only :py:class:`aspose.slides.charts.IChartDataWorksheet`. |
| [is_hidden](/slides/python-net/aspose.slides.charts/is_hidden) | Determines whether the cell is hidden.<br/>            Read-only :py:class:`bool`. |
| [custom_number_format](/slides/python-net/aspose.slides.charts/custom_number_format) | Gets or sets the custom display format of numbers and dates. <br/>            If value is empty will be used PresetNumberFormat value.<br/>            Read/write :py:class:`System.String`. |
| [preset_number_format](/slides/python-net/aspose.slides.charts/preset_number_format) | Gets or sets the built-in display format of numbers and dates. Preset number must be in [0..22] or [37..49].<br/>             Read/write :py:class:`int`. |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.charts/chartdatacell/#bool) | If the cell contains a formula, the value will be updated base on that formula. |

