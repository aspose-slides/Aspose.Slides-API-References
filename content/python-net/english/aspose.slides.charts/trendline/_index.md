---
title: Trendline
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/trendline/
---


Trendline class

Class represents trend line of chart series

The Trendline type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [trendline_name](/slides/python-net/aspose.slides.charts/trendline/trendline_name/) | Gets or sets  name of the trendline.<br/>            Read/write :py:class:`System.String`. |
| [trendline_type](/slides/python-net/aspose.slides.charts/trendline/trendline_type/) | Gets or sets type of trend line.<br/>            Read/write :py:enum:`aspose.slides.charts.TrendlineType`. |
| [format](/slides/python-net/aspose.slides.charts/trendline/format/) | Represents the format of the trend line.<br/>            Read/write :py:class:`aspose.slides.charts.IFormat`. |
| [backward](/slides/python-net/aspose.slides.charts/trendline/backward/) | Specifies the number of categories (or units on a scatter chart) that the trend line extends before<br/>            the data for the series that is being trended. On scatter and non-scatter charts, the value shall be any nonnegative<br/>            value.<br/>            Read/write :py:class:`float`. |
| [forward](/slides/python-net/aspose.slides.charts/trendline/forward/) | Specifies the number of categories (or units on a scatter chart) that the trendline extends after the<br/>            data for the series that is being trended. On scatter and non-scatter charts, the value shall be any non-negative<br/>            value.<br/>            Read/write :py:class:`float`. |
| [intercept](/slides/python-net/aspose.slides.charts/trendline/intercept/) | Specifies the value where the trendline shall cross the y axis. This property shall be supported only<br/>            when the trendline type is exp, linear, or poly.<br/>            Read/write :py:class:`float`. |
| [display_equation](/slides/python-net/aspose.slides.charts/trendline/display_equation/) | Specifies that the equation for the trendline is displayed on the chart (in the same label as the Rsquaredvalue).<br/>            Read/write :py:class:`bool`. |
| [order](/slides/python-net/aspose.slides.charts/trendline/order/) | Specifies the order of the polynomial trend line. It is ignored for other trend line types. Value must be between 2 and 6.<br/>            Read/write :py:class:`int`. |
| [period](/slides/python-net/aspose.slides.charts/trendline/period/) | Specifies the period of the trend line for a moving average trend line. It is ignored for other trend<br/>            line variants. Value must be between 2 and 255.<br/>            Read/write :py:class:`int`. |
| [display_r_squared_value](/slides/python-net/aspose.slides.charts/trendline/display_r_squared_value/) | Specifies that the R-squared value of the trendline is displayed on the chart (in the same label as the equation).<br/>            Read/write :py:class:`bool`. |
| [related_legend_entry](/slides/python-net/aspose.slides.charts/trendline/related_legend_entry/) | Represents legend entry related with this trendline<br/>            Read-only :py:class:`aspose.slides.charts.ILegendEntryProperties`. |
| [text_frame_for_overriding](/slides/python-net/aspose.slides.charts/trendline/text_frame_for_overriding/) | Can contain a rich formatted text. If this property is not null then this <br/>            formatted text value overrides auto-generated text of data label.<br/>            Auto-generated text of data label means text that is managed by ShowSeriesName, <br/>            ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property.<br/>            Read-only :py:class:`aspose.slides.ITextFrame`. |
| [text_format](/slides/python-net/aspose.slides.charts/trendline/text_format/) | Returns text format.<br/>            Read-only :py:class:`aspose.slides.charts.IChartTextFormat`. |
| [chart](/slides/python-net/aspose.slides.charts/trendline/chart/) | Returns the parent chart.<br/>            Read-only :py:class:`aspose.slides.charts.IChart`. |
| [as_i_overridable_text](/slides/python-net/aspose.slides.charts/trendline/as_i_overridable_text/) |  |
| [as_i_formatted_text_container](/slides/python-net/aspose.slides.charts/trendline/as_i_formatted_text_container/) |  |
| [as_i_chart_component](/slides/python-net/aspose.slides.charts/trendline/as_i_chart_component/) |  |
| [as_i_slide_component](/slides/python-net/aspose.slides.charts/trendline/as_i_slide_component/) |  |
| [slide](/slides/python-net/aspose.slides.charts/trendline/slide/) |  |
| [as_i_presentation_component](/slides/python-net/aspose.slides.charts/trendline/as_i_presentation_component/) |  |
| [presentation](/slides/python-net/aspose.slides.charts/trendline/presentation/) |  |

## Methods

| Method | Description |
| :- | :- |
| [add_text_frame_for_overriding](/slides/python-net/aspose.slides.charts/trendline/trendline/#string/) | Initialize TextFrameForOverriding with the text in paramener "text".<br/>            If TextFrameForOverriding is already initialized then simply changes its text. |

