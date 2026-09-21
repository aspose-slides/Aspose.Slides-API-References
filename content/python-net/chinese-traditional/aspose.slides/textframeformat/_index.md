---
title: TextFrameFormat class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/textframeformat/
---
## TextFrameFormat 類別

Contains the TextFrame's formatTextFrameFormatting properties.

**Inheritance:**[`TextFrameFormat`](/slides/python-net/zh-hant/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/zh-hant/aspose.slides/pviobject)

The TextFrameFormat type exposes the following members:

## 建構函式

| 建構式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides/textframeformat/__init__/#) | 初始化 [`TextFrameFormat`](/slides/python-net/zh-hant/aspose.slides/textframeformat) 類別的新執行個體。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`three_d_format`](/slides/python-net/zh-hant/aspose.slides/textframeformat/three_d_format/) | Returns the ThreeDFormat object that represents 3d effect properties for a text.<br/>            只讀 [`IThreeDFormat`](/slides/python-net/zh-hant/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/zh-hant/aspose.slides/textframeformat/margin_left/) | Returns or sets the left margin (points) in a TextFrame.<br/>            可讀寫 **float**. |
| [`margin_right`](/slides/python-net/zh-hant/aspose.slides/textframeformat/margin_right/) | Returns or sets the right margin (points) in a TextFrame.<br/>            可讀寫 **float**. |
| [`margin_top`](/slides/python-net/zh-hant/aspose.slides/textframeformat/margin_top/) | Returns or sets the top margin (points) in a TextFrame.<br/>            可讀寫 **float**. |
| [`margin_bottom`](/slides/python-net/zh-hant/aspose.slides/textframeformat/margin_bottom/) | Returns or sets the bottom margin (points) in a TextFrame.<br/>            可讀寫 **float**. |
| [`wrap_text`](/slides/python-net/zh-hant/aspose.slides/textframeformat/wrap_text/) | **True**  若文字在 TextFrame 的邊界換行。<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/zh-hant/aspose.slides/textframeformat/anchoring_type/) | Returns or sets vertical anchor text in a TextFrame.<br/>            可讀寫 [`TextAnchorType`](/slides/python-net/zh-hant/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/zh-hant/aspose.slides/textframeformat/center_text/) | If NullableBool.True then text should be centered in box horizontally.<br/>            可讀寫 [`NullableBool`](/slides/python-net/zh-hant/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/zh-hant/aspose.slides/textframeformat/text_vertical_type/) | Determines text orientation.<br/>            The resulted value of visual text rotation summarized from this property and custom angle<br/>            in property RotationAngle.<br/>            可讀寫 [`TextVerticalType`](/slides/python-net/zh-hant/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/zh-hant/aspose.slides/textframeformat/autofit_type/) | Returns or sets text's autofit mode.<br/>            可讀寫 [`TextAutofitType`](/slides/python-net/zh-hant/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/zh-hant/aspose.slides/textframeformat/column_count/) | Returns or sets number of columns in the text area.<br/>            This value must be a positive number. Otherwise, the value will be set to zero. <br/>            Value 0 means undefined value.<br/>            可讀寫 **int**. |
| [`column_spacing`](/slides/python-net/zh-hant/aspose.slides/textframeformat/column_spacing/) | Returns or sets the space between text columns in the text area (in points). This should only apply <br/>            when there is more than 1 column present.<br/>            This value must be a positive number. Otherwise, the value will be set to zero. <br/>            可讀寫 **float**. |
| [`rotation_angle`](/slides/python-net/zh-hant/aspose.slides/textframeformat/rotation_angle/) | Specifies custom the rotation that is being applied to the text within the bounding box. If it not<br/>            specified, the rotation of the accompanying shape is used. If it is specified, then this is<br/>            applied independently from the shape. That is the shape can have a rotation applied in<br/>            addition to the text itself having a rotation applied to it.<br/>            The resulted value of visual text rotation summarized from this property and predefined<br/>            vertical type in property TextVerticalType.<br/>            可讀寫 **float**. |
| [`transform`](/slides/python-net/zh-hant/aspose.slides/textframeformat/transform/) | Gets or sets text wrapping shape.<br/>            可讀寫 [`TextShapeType`](/slides/python-net/zh-hant/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/zh-hant/aspose.slides/textframeformat/keep_text_flat/) | Gets or sets keeping text flat even if a 3-D Rotation effect was applied.<br/>            可讀寫 **bool**. |
| [`slide`](/slides/python-net/zh-hant/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/zh-hant/aspose.slides/textframeformat/text_style/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/zh-hant/aspose.slides/textframeformat/get_effective/#) | Gets effective text frame formatting data with the inheritance applied. |

### 另見
* 類別 [`PVIObject`](/slides/python-net/zh-hant/aspose.slides/pviobject)
* 類別 [`TextFrameFormat`](/slides/python-net/zh-hant/aspose.slides/textframeformat)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)