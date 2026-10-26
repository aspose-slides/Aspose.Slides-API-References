---
title: set_RotationAngle()
second_title: Aspose.Slides for C++ API 参考
description: 指定正在应用于边界框内文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果已指定，则此旋转独立于形状应用。也就是说，形状可以有一个旋转，同时文本本身也可以有一个旋转。该属性与属性 TextVerticalType 中预定义的垂直类型共同决定了视觉文本旋转的最终值。写入 float.
type: docs
weight: 313
url: /zh/aspose.slides/textframeformat/set_rotationangle/
---
## TextFrameFormat::set_RotationAngle(float) 方法


指定正在应用于边界框内文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果已指定，则此旋转独立于形状应用。也就是说，形状可以有一个旋转，同时文本本身也可以有一个旋转。此属性以及属性 TextVerticalType 中预定义的垂直类型共同决定了视觉文本旋转的最终值。写入 **float**。

```cpp
void Aspose::Slides::TextFrameFormat::set_RotationAngle(float value) override
```

## 备注


考虑一种情况：形状被应用了顺时针 90 度的旋转。除此之外，文本主体本身被应用了逆时针 -90 度的旋转。这样，最终的形状看起来是旋转的，但其中的文本看起来好像根本没有被旋转。

## 另请参见

* 类 [TextFrameFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)