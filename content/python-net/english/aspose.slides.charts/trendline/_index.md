﻿---
title: Trendline class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/trendline/
---


## Trendline class

Class represents trend line of chart series

The Trendline type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`trendline_name`](/slides/python-net/aspose.slides.charts/trendline/trendline_name/) | Gets or sets  name of the trendline.<br/>            Read/write **str**. |
| [`trendline_type`](/slides/python-net/aspose.slides.charts/trendline/trendline_type/) | Gets or sets type of trend line.<br/>            Read/write [`TrendlineType`](/slides/python-net/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/aspose.slides.charts/trendline/format/) | Represents the format of the trend line.<br/>            Read/write [`IFormat`](/slides/python-net/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/aspose.slides.charts/trendline/backward/) | Specifies the number of categories (or units on a scatter chart) that the trend line extends before<br/>            the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative<br/>            value.<br/>            Read/write **float**. |
| [`forward`](/slides/python-net/aspose.slides.charts/trendline/forward/) | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the<br/>            data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative<br/>            value.<br/>            Read/write **float**. |
| [`intercept`](/slides/python-net/aspose.slides.charts/trendline/intercept/) | Specifies the value where the trendline shall cross the y axis. This property shall be supported only<br/>            when the trendline type is exp, linear, or poly.<br/>            Read/write **float**. |
| [`display_equation`](/slides/python-net/aspose.slides.charts/trendline/display_equation/) | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue).<br/>            Read/write **bool**. |
| [`order`](/slides/python-net/aspose.slides.charts/trendline/order/) | Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6.<br/>            Read/write **int**. |
| [`period`](/slides/python-net/aspose.slides.charts/trendline/period/) | Specifies the period of the trend line for a moving average trend line. It is ignored for other trend<br/>            line variants. Value must be between 2 and 255.<br/>            Read/write **int**. |
| [`display_r_squared_value`](/slides/python-net/aspose.slides.charts/trendline/display_r_squared_value/) | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation).<br/>            Read/write **bool**. |
| [`related_legend_entry`](/slides/python-net/aspose.slides.charts/trendline/related_legend_entry/) | Represents legend entry related with this trendline<br/>            Read-only [`ILegendEntryProperties`](/slides/python-net/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/aspose.slides.charts/trendline/text_frame_for_overriding/) | Can contain a rich formatted text. If this property is not None then this <br/>            formatted text value overrides auto-generated text of data label.<br/>            Auto-generated text of data label means text that is managed by ShowSeriesName, <br/>            ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property.<br/>            Read-only [`ITextFrame`](/slides/python-net/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/aspose.slides.charts/trendline/text_format/) | Returns text format.<br/>            Read-only [`IChartTextFormat`](/slides/python-net/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/aspose.slides.charts/trendline/chart/) | Returns the parent chart.<br/>            Read-only [`IChart`](/slides/python-net/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/aspose.slides.charts/trendline/presentation/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`add_text_frame_for_overriding`](/slides/python-net/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | Initialize TextFrameForOverriding with the text in paramener "text".<br/>            If TextFrameForOverriding is already initialized then simply changes its text. |


### See Also
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)

