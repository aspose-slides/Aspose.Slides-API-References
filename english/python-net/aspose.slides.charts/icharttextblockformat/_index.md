---
title: IChartTextBlockFormat
second_title: Aspose.Sildes for Python via .NET API Reference
description: 
type: docs
weight: 690
url: /python-net/aspose.slides.charts/icharttextblockformat/
---

## IChartTextBlockFormat class

Represents formatting properties for chart text elements.

The IChartTextBlockFormat type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|anchoring_type|Returns or sets vertical anchor text in a TextFrame.<br/>            Read/write [TextAnchorType](/slides/python-net/aspose.slides/textanchortype/).|
|center_text|If NullableBool.True then text should be centered in box horizontally.<br/>            Read/write [NullableBool](/slides/python-net/aspose.slides/nullablebool/).|
|text_vertical_type|Determines text orientation.<br/>            The resulted value of visual text rotation summarized from this property and custom angle<br/>            in property RotationAngle.<br/>            Read/write [TextVerticalType](/slides/python-net/aspose.slides/textverticaltype/).|
|margin_left|Returns or sets the left margin (points) in a TextFrame.<br/>            Changing of this property can produce a certain influence only for these chart parts: <br/>            DataLabel and DataLabelFormat (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering).<br/>            Read/write float.|
|margin_right|Returns or sets the right margin (points) in a TextFrame.<br/>            Changing of this property can produce a certain influence only for these chart parts: <br/>            DataLabel and DataLabelFormat (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering).<br/>            Read/write float.|
|margin_top|Returns or sets the top margin (points) in a TextFrame.<br/>            Changing of this property can produce a certain influence only for these chart parts: <br/>            DataLabel and DataLabelFormat (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering).<br/>            Read/write float.|
|margin_bottom|Returns or sets the bottom margin (points) in a TextFrame.<br/>            Changing of this property can produce a certain influence only for these chart parts: <br/>            DataLabel and DataLabelFormat (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering).<br/>            Read/write float.|
|wrap_text|True if text is wrapped at TextFrame's margins.<br/>            Changing of this property can produce a certain influence only for these chart parts: <br/>            DataLabel and DataLabelFormat (full suport in PowerPoint 2007/2013).<br/>            Read/write [NullableBool](/slides/python-net/aspose.slides/nullablebool/).|
|autofit_type|Returns or sets text's autofit mode.<br/>            Changing of this property can produce a certain influence only for these chart parts: <br/>            DataLabel and DataLabelFormat (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering).<br/>            Read/write [TextAutofitType](/slides/python-net/aspose.slides/textautofittype/).|
|rotation_angle|Specifies the custom rotation that is being applied to the text within the bounding box. If it not<br/>            specified, the rotation of the accompanying shape is used. If it is specified, then this is<br/>            applied independently from the shape. That is the shape can have a rotation applied in<br/>            addition to the text itself having a rotation applied to it.<br/>            The resulted value of visual text rotation summarized from this property and predefined<br/>            vertical type in property TextVerticalType.<br/>            Read/write|

### See Also

* namespace [aspose.slides.charts](/slides/python-net/aspose.slides.charts/)
* assembly [Aspose.Slides](/slides/python-net/)

