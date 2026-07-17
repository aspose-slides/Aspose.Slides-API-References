---
title: get_RotationAngle()
second_title: Aspose.Slides for C++ API 参考
description: 指定自定义的旋转，该旋转应用于边界框内的文本。如果未指定，则使用伴随形状的旋转。如果指定，则该旋转独立于形状应用。也就是说，形状可以有旋转，同时文本本身也可以有旋转。此属性以及属性 TextVerticalType 中预定义的垂直类型汇总得到的视觉文本旋转值。读取 float.
type: docs
weight: 300
url: /zh/aspose.slides/textframeformat/get_rotationangle/
---
## TextFrameFormat::get_RotationAngle() 方法

指定自定义的旋转，该旋转应用于边界框内的文本。如果未指定，则使用伴随形状的旋转。如果指定，则该旋转独立于形状应用。也就是说，形状可以有旋转，同时文本本身也可以有旋转。该属性以及属性 TextVerticalType 中预定义的垂直类型汇总得到的视觉文本旋转值。读取 **float**。

```cpp
float Aspose::Slides::TextFrameFormat::get_RotationAngle() override
```

## 备注

考虑一种情况：形状已应用顺时针 90 度的旋转。此外，文本本身又应用了逆时针 -90 度的旋转。于是，结果形状看起来已旋转，但其中的文本看起来好像根本没有旋转。

## 另请参阅

* 类 [TextFrameFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)