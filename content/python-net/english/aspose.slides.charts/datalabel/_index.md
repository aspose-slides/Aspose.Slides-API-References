---
title: DataLabel class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/datalabel/
---


## DataLabel class

Represents a series labels.

The DataLabel type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Creates a new instance of DataLabel class. |

## Properties

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/aspose.slides.charts/datalabel/chart/) | Returns the parent chart.<br/>            Read-only [`IChart`](/slides/python-net/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/aspose.slides.charts/datalabel/is_visible/) | False means that data label is not visible (and so all Show*-flags (ShowValue, ...) are false).<br/>            Read-only **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Can contain a rich formatted text. If this property is not null then this <br/>            formatted text value overrides auto-generated text of data label.<br/>            Auto-generated text of data label means text that is managed by ShowSeriesName, <br/>            ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property.<br/>            Read-only [`ITextFrame`](/slides/python-net/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/aspose.slides.charts/datalabel/text_format/) | Returns text format.<br/>            Read-only [`IChartTextFormat`](/slides/python-net/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/aspose.slides.charts/datalabel/x/) | Returns or sets the x coordinate of a title as a fraction of the width of the chart.<br/>            Read/write **float**. |
| [`y`](/slides/python-net/aspose.slides.charts/datalabel/y/) | Returns or sets the y coordinate of a title as a fraction of the height of the chart.<br/>            Read/write **float**. |
| [`width`](/slides/python-net/aspose.slides.charts/datalabel/width/) | Returns or sets the width of a title as a fraction of the width of the chart.<br/>            Read/write **float**. |
| [`height`](/slides/python-net/aspose.slides.charts/datalabel/height/) | Returns or sets the height of a title as a fraction of the height of the chart.<br/>            Read/write **float**. |
| [`right`](/slides/python-net/aspose.slides.charts/datalabel/right/) | Right.<br/>            Read-only **float**. |
| [`bottom`](/slides/python-net/aspose.slides.charts/datalabel/bottom/) | Bottom.<br/>            Read-only **float**. |
| [`data_label_format`](/slides/python-net/aspose.slides.charts/datalabel/data_label_format/) | Returns data label format.<br/>            Read-only [`IDataLabelFormat`](/slides/python-net/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/aspose.slides.charts/datalabel/value_from_cell/) | Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true. |
| [`actual_x`](/slides/python-net/aspose.slides.charts/datalabel/actual_x/) | Specifies actual x location (left) of the chart element relative to the left top corner of the chart.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Read **float**. |
| [`actual_y`](/slides/python-net/aspose.slides.charts/datalabel/actual_y/) | Specifies actual top of the chart element relative to the left top corner of the chart.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Read **float**. |
| [`actual_width`](/slides/python-net/aspose.slides.charts/datalabel/actual_width/) | Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Read **float**. |
| [`actual_height`](/slides/python-net/aspose.slides.charts/datalabel/actual_height/) | Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Read **float**. |
| [`as_i_layoutable`](/slides/python-net/aspose.slides.charts/datalabel/as_i_layoutable/) |  |
| [`as_i_overridable_text`](/slides/python-net/aspose.slides.charts/datalabel/as_i_overridable_text/) |  |
| [`as_i_actual_layout`](/slides/python-net/aspose.slides.charts/datalabel/as_i_actual_layout/) |  |
| [`as_i_slide_component`](/slides/python-net/aspose.slides.charts/datalabel/as_i_slide_component/) |  |
| [`slide`](/slides/python-net/aspose.slides.charts/datalabel/slide/) |  |
| [`as_i_presentation_component`](/slides/python-net/aspose.slides.charts/datalabel/as_i_presentation_component/) |  |
| [`presentation`](/slides/python-net/aspose.slides.charts/datalabel/presentation/) |  |
| [`as_i_formatted_text_container`](/slides/python-net/aspose.slides.charts/datalabel/as_i_formatted_text_container/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`hide`](/slides/python-net/aspose.slides.charts/datalabel/hide/#) | Make data label hidden by setting all Show*-flags (ShowValue, ...) to false state.<br/>            IsVisible will be false after this. |
| [`get_actual_label_text`](/slides/python-net/aspose.slides.charts/datalabel/get_actual_label_text/#) | Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value. |
| [`add_text_frame_for_overriding`](/slides/python-net/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#string) | Initialize TextFrameForOverriding with the text in paramener "text".<br/>            If TextFrameForOverriding is already initialized then simply changes its text. |

### See Also
* module [`aspose.slides.charts`](/slides/python-net/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)
