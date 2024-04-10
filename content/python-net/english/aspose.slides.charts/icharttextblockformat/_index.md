---
title: IChartTextBlockFormat class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.charts/
---


## IChartTextBlockFormat class

Represents formatting properties for chart text elements.

The IChartTextBlockFormat type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [anchoring_type](/slides/python-net/aspose.slides.charts/anchoring_type) | Returns or sets vertical anchor text in a TextFrame.<br/>            Read/write :py:enum:`aspose.slides.TextAnchorType`. |
| [center_text](/slides/python-net/aspose.slides.charts/center_text) | If NullableBool.True then text should be centered in box horizontally.<br/>            Read/write :py:enum:`aspose.slides.NullableBool`. |
| [text_vertical_type](/slides/python-net/aspose.slides.charts/text_vertical_type) | Determines text orientation.<br/>            The resulted value of visual text rotation summarized from this property and custom angle<br/>            in property RotationAngle.<br/>            Read/write :py:enum:`aspose.slides.TextVerticalType`. |
| [margin_left](/slides/python-net/aspose.slides.charts/margin_left) | Returns or sets the left margin (points) in a TextFrame.<br/>            Changing of this property can produce a certain influence only for these chart parts: <br/>            DataLabel and DataLabelFormat (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering).<br/>            Read/write :py:class:`float`. |
| [margin_right](/slides/python-net/aspose.slides.charts/margin_right) | Returns or sets the right margin (points) in a TextFrame.<br/>            Changing of this property can produce a certain influence only for these chart parts: <br/>            DataLabel and DataLabelFormat (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering).<br/>            Read/write :py:class:`float`. |
| [margin_top](/slides/python-net/aspose.slides.charts/margin_top) | Returns or sets the top margin (points) in a TextFrame.<br/>            Changing of this property can produce a certain influence only for these chart parts: <br/>            DataLabel and DataLabelFormat (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering).<br/>            Read/write :py:class:`float`. |
| [margin_bottom](/slides/python-net/aspose.slides.charts/margin_bottom) | Returns or sets the bottom margin (points) in a TextFrame.<br/>            Changing of this property can produce a certain influence only for these chart parts: <br/>            DataLabel and DataLabelFormat (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering).<br/>            Read/write :py:class:`float`. |
| [wrap_text](/slides/python-net/aspose.slides.charts/wrap_text) | **True** if text is wrapped at TextFrame's margins.<br/>            Changing of this property can produce a certain influence only for these chart parts: <br/>            DataLabel and DataLabelFormat (full suport in PowerPoint 2007/2013).<br/>            Read/write :py:enum:`aspose.slides.NullableBool`. |
| [autofit_type](/slides/python-net/aspose.slides.charts/autofit_type) | Returns or sets text's autofit mode.<br/>            Changing of this property can produce a certain influence only for these chart parts: <br/>            DataLabel and DataLabelFormat (full suport in PowerPoint 2013; in PowerPoint 2007 there is no effect for rendering).<br/>            Read/write :py:enum:`aspose.slides.TextAutofitType`. |
| [rotation_angle](/slides/python-net/aspose.slides.charts/rotation_angle) | Specifies the custom rotation that is being applied to the text within the bounding box. If it not<br/>            specified, the rotation of the accompanying shape is used. If it is specified, then this is<br/>            applied independently from the shape. That is the shape can have a rotation applied in<br/>            addition to the text itself having a rotation applied to it.<br/>            The resulted value of visual text rotation summarized from this property and predefined<br/>            vertical type in property TextVerticalType.<br/>            Read/write :py:class:`float`. |

