---
title: ITextFrameFormat class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/itextframeformat/
---
## ITextFrameFormat 类

包含 TextFrame 的格式属性。

ITextFrameFormat 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`text_style`](/slides/python-net/zh/aspose.slides/itextframeformat/text_style/) | 返回文本的样式。<br/>            只读 [`ITextStyle`](/slides/python-net/zh/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/zh/aspose.slides/itextframeformat/margin_left/) | 返回或设置 TextFrame 中的左边距（points）。<br/>            可读写 **float**. |
| [`margin_right`](/slides/python-net/zh/aspose.slides/itextframeformat/margin_right/) | 返回或设置 TextFrame 中的右边距（points）。<br/>            可读写 **float**. |
| [`margin_top`](/slides/python-net/zh/aspose.slides/itextframeformat/margin_top/) | 返回或设置 TextFrame 中的上边距（points）。<br/>            可读写 **float**. |
| [`margin_bottom`](/slides/python-net/zh/aspose.slides/itextframeformat/margin_bottom/) | 返回或设置 TextFrame 中的下边距（points）。<br/>            可读写 **float**. |
| [`wrap_text`](/slides/python-net/zh/aspose.slides/itextframeformat/wrap_text/) | **True** 如果文本在 TextFrame 的边距处自动换行。<br/>            可读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/zh/aspose.slides/itextframeformat/anchoring_type/) | 返回或设置 TextFrame 中的垂直锚定文本。<br/>            可读写 [`TextAnchorType`](/slides/python-net/zh/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/zh/aspose.slides/itextframeformat/center_text/) | 如果 NullableBool.True，则文本应水平居中于盒子内。<br/>            可读写 [`NullableBool`](/slides/python-net/zh/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/zh/aspose.slides/itextframeformat/text_vertical_type/) | 确定文本方向。<br/>            该属性与属性 RotationAngle 中的自定义角度共同决定可视文本旋转的结果值。<br/>            可读写 [`TextVerticalType`](/slides/python-net/zh/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/zh/aspose.slides/itextframeformat/autofit_type/) | 返回或设置文本的自动适配模式。<br/>            可读写 [`TextAutofitType`](/slides/python-net/zh/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/zh/aspose.slides/itextframeformat/column_count/) | 返回或设置文本区域中的列数。<br/>            该值必须为正数。否则，值将被设为 0。 <br/>            值 0 表示未定义。<br/>            可读写 **int**. |
| [`column_spacing`](/slides/python-net/zh/aspose.slides/itextframeformat/column_spacing/) | 返回或设置文本区域中列之间的间距（points）。仅在存在超过 1 列时适用。<br/>            当有多个列时。<br/>            该值必须为正数。否则，值将被设为 0。 <br/>            可读写 **float**. |
| [`three_d_format`](/slides/python-net/zh/aspose.slides/itextframeformat/three_d_format/) | 返回表示文本 3D 效果属性的 ThreeDFormat 对象。<br/>            只读 [`IThreeDFormat`](/slides/python-net/zh/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/zh/aspose.slides/itextframeformat/keep_text_flat/) | 返回或设置完全将文本保持在 3D 场景之外。<br/>            可读写 **bool**. |
| [`rotation_angle`](/slides/python-net/zh/aspose.slides/itextframeformat/rotation_angle/) | 指定在边界框内应用于文本的自定义旋转。如果未指定，<br/>            将使用伴随形状的旋转。如果已指定，则该旋转独立于形状应用。也就是说，形状可以有旋转，<br/>            同时文本本身也可以有旋转。<br/>            该属性与属性 TextVerticalType 中的预定义垂直类型共同决定可视文本旋转的结果值。<br/>            可读写 **float**. |
| [`transform`](/slides/python-net/zh/aspose.slides/itextframeformat/transform/) | 获取或设置文本换行形状。<br/>            可读写 [`TextShapeType`](/slides/python-net/zh/aspose.slides/textshapetype). |

## 方法

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/zh/aspose.slides/itextframeformat/get_effective/#) | 获取在应用继承后的有效文本框格式数据。 |

### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)