---
title: DataLabel
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/datalabel/
---

## DataLabel class

Represents a series labels.

The DataLabel type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|DataLabel(parent_immediate)|Initializes a new instance of the DataLabel class|
## Properties
| Name | Description |
| :- | :- |
|chart|Returns the parent chart.<br/>            Read-only [IChart](/slides/python-net/aspose.slides.charts/ichart/).|
|is_visible|False means that data label is not visible (and so all Show*-flags (ShowValue, ...) are false).<br/>            Read-only bool.|
|text_frame_for_overriding|Can contain a rich formatted text. If this property is not null then this <br/>            formatted text value overrides auto-generated text of data label.<br/>            Auto-generated text of data label means text that is managed by ShowSeriesName, <br/>            ShowValue, ... properties and is formatted with the TextFormatManager.TextFormat property.<br/>            Read-only [ITextFrame](/slides/python-net/aspose.slides/itextframe/).|
|text_format|Returns text format.<br/>            Read-only [IChartTextFormat](/slides/python-net/aspose.slides.charts/icharttextformat/).|
|x|Returns or sets the x coordinate of a title as a fraction of the width of the chart.<br/>            Read/write|
|y|Returns or sets the y coordinate of a title as a fraction of the height of the chart.<br/>            Read/write|
|width|Returns or sets the width of a title as a fraction of the width of the chart.<br/>            Read/write|
|height|Returns or sets the height of a title as a fraction of the height of the chart.<br/>            Read/write|
|right|Right.<br/>            Read-only|
|bottom|Bottom.<br/>            Read-only|
|data_label_format|Returns data label format.<br/>            Read-only [IDataLabelFormat](/slides/python-net/aspose.slides.charts/idatalabelformat/).|
|value_from_cell|Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true.|
|actual_x|Specifies actual x location (left) of the chart element relative to the left top corner of the chart.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Read|
|actual_y|Specifies actual top of the chart element relative to the left top corner of the chart.<br/>            Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Read|
|actual_width|Specifies actual width of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Read|
|actual_height|Specifies actual height of the chart element. Call method IChart.ValidateChartLayout() before to get actual values. <br/>            Read|
|as_i_layoutable|Returns ILayoutable interface.<br/>            Read-only [ILayoutable](/slides/python-net/aspose.slides.charts/ilayoutable/).|
|as_i_overridable_text|Returns IOverridableText interface.<br/>            Read-only [IOverridableText](/slides/python-net/aspose.slides.charts/ioverridabletext/).|
|as_i_actual_layout|Returns IActualLayout interface.|
|as_i_slide_component|Allows to get base ISlideComponent interface.<br/>            Read-only [ISlideComponent](/slides/python-net/aspose.slides/islidecomponent/).|
|slide|Returns the base slide.<br/>            Read-only [IBaseSlide](/slides/python-net/aspose.slides/ibaseslide/).|
|as_i_presentation_component|Allows to get base IPresentationComponent interface.<br/>            Read-only [IPresentationComponent](/slides/python-net/aspose.slides/ipresentationcomponent/).|
|presentation|Returns the presentation. <br/>            Read-only [IPresentation](/slides/python-net/aspose.slides/ipresentation/).|
|as_i_formatted_text_container|Allows to get base IFormattedTextContainer interface.<br/>            Read-only [IFormattedTextContainer](/slides/python-net/aspose.slides.charts/iformattedtextcontainer/).|
## Methods
| Name | Description |
| :- | :- |
|hide()|Make data label hidden by setting all Show*-flags (ShowValue, ...) to false state.<br/>            IsVisible will be false after this.|
|get_actual_label_text()|Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value.|
|add_text_frame_for_overriding(text)|Initialize TextFrameForOverriding with the text in paramener "text".<br/>            If TextFrameForOverriding is already initialized then simply changes its text.|

### See Also

* namespace [aspose.slides.charts](/slides/python-net/aspose.slides.charts/)
* assembly [Aspose.Slides](/slides/python-net/)

