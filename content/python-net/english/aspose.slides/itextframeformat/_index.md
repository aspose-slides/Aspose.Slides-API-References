---
title: ITextFrameFormat
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/itextframeformat/
---


ITextFrameFormat class

Contains the TextFrame's formatting properties.

The ITextFrameFormat type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [text_style](/slides/python-net/aspose.slides/itextframeformat/text_style/) | Returns text's style.<br/>            Read-only <br/>[`ITextStyle`](/slides/python-net/aspose.slides/itextstyle)<br/>. |
| [margin_left](/slides/python-net/aspose.slides/itextframeformat/margin_left/) | Returns or sets the left margin (points) in a TextFrame.<br/>            Read/write <br/>.NET type System.Double<br/>. |
| [margin_right](/slides/python-net/aspose.slides/itextframeformat/margin_right/) | Returns or sets the right margin (points) in a TextFrame.<br/>            Read/write <br/>.NET type System.Double<br/>. |
| [margin_top](/slides/python-net/aspose.slides/itextframeformat/margin_top/) | Returns or sets the top margin (points) in a TextFrame.<br/>            Read/write <br/>.NET type System.Double<br/>. |
| [margin_bottom](/slides/python-net/aspose.slides/itextframeformat/margin_bottom/) | Returns or sets the bottom margin (points) in a TextFrame.<br/>            Read/write <br/>.NET type System.Double<br/>. |
| [wrap_text](/slides/python-net/aspose.slides/itextframeformat/wrap_text/) | **<br/>True<br/>** <br/> if text is wrapped at TextFrame's margins.<br/>            Read/write <br/>[`NullableBool`](/slides/python-net/aspose.slides/nullablebool)<br/>. |
| [anchoring_type](/slides/python-net/aspose.slides/itextframeformat/anchoring_type/) | Returns or sets vertical anchor text in a TextFrame.<br/>            Read/write <br/>[`TextAnchorType`](/slides/python-net/aspose.slides/textanchortype)<br/>. |
| [center_text](/slides/python-net/aspose.slides/itextframeformat/center_text/) | If NullableBool.True then text should be centered in box horizontally.<br/>            Read/write <br/>[`NullableBool`](/slides/python-net/aspose.slides/nullablebool)<br/>. |
| [text_vertical_type](/slides/python-net/aspose.slides/itextframeformat/text_vertical_type/) | Determines text orientation.<br/>            The resulted value of visual text rotation summarized from this property and custom angle<br/>            in property RotationAngle.<br/>            Read/write <br/>[`TextVerticalType`](/slides/python-net/aspose.slides/textverticaltype)<br/>. |
| [autofit_type](/slides/python-net/aspose.slides/itextframeformat/autofit_type/) | Returns or sets text's autofit mode.<br/>            Read/write <br/>[`TextAutofitType`](/slides/python-net/aspose.slides/textautofittype)<br/>. |
| [column_count](/slides/python-net/aspose.slides/itextframeformat/column_count/) | Returns or sets number of columns in the text area.<br/>            This value must be a positive number. Otherwise, the value will be set to zero. <br/>            Value 0 means undefined value.<br/>            Read/write <br/>.NET type System.Int32<br/>. |
| [column_spacing](/slides/python-net/aspose.slides/itextframeformat/column_spacing/) | Returns or sets the space between text columns in the text area (in points). This should only apply <br/>            when there is more than 1 column present.<br/>            This value must be a positive number. Otherwise, the value will be set to zero. <br/>            Read/write <br/>.NET type System.Double<br/>. |
| [three_d_format](/slides/python-net/aspose.slides/itextframeformat/three_d_format/) | Returns the ThreeDFormat object that represents 3d effect properties for a text.<br/>            Read-only <br/>[`IThreeDFormat`](/slides/python-net/aspose.slides/ithreedformat)<br/>. |
| [keep_text_flat](/slides/python-net/aspose.slides/itextframeformat/keep_text_flat/) | Returns or set keeping text out of 3D scene entirely.<br/>            Read/write <br/>.NET type System.Boolean<br/>. |
| [rotation_angle](/slides/python-net/aspose.slides/itextframeformat/rotation_angle/) | Specifies the custom rotation that is being applied to the text within the bounding box. If it not<br/>            specified, the rotation of the accompanying shape is used. If it is specified, then this is<br/>            applied independently from the shape. That is the shape can have a rotation applied in<br/>            addition to the text itself having a rotation applied to it.<br/>            The resulted value of visual text rotation summarized from this property and predefined<br/>            vertical type in property TextVerticalType.<br/>            Read/write <br/>.NET type System.Single<br/>. |
| [transform](/slides/python-net/aspose.slides/itextframeformat/transform/) | Gets or sets text wrapping shape.<br/>            Read/write <br/>[`TextShapeType`](/slides/python-net/aspose.slides/textshapetype)<br/>. |

## Methods

| Method | Description |
| :- | :- |
| [get_effective](/slides/python-net/aspose.slides/itextframeformat/itextframeformat/#/) | Gets effective text frame formatting data with the inheritance applied. |

