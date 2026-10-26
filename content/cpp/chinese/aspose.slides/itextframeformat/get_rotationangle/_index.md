---
title: get_RotationAngle()
second_title: Aspose.Slides for C++ API 参考
description: 指定应用于边界框内文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果已指定，则该旋转独立于形状应用。也就是说，形状可以有一个旋转，同时文本本身也可以有一个旋转。该属性与属性 TextVerticalType 中的预定义垂直类型共同汇总得到的可视文本旋转值。读取 float.
type: docs
weight: 339
url: /zh/aspose.slides/itextframeformat/get_rotationangle/
---
## ITextFrameFormat::get_RotationAngle() 方法


指定应用于边界框内文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果已指定，则该旋转独立于形状应用。也就是说，形状可以有一个旋转，同时文本本身也可以有一个旋转。该属性与属性 TextVerticalType 中的预定义垂直类型共同汇总得到的可视文本旋转值。读取 **float**.

```cpp
virtual float Aspose::Slides::ITextFrameFormat::get_RotationAngle()=0
```

## 备注


考虑一种情况：形状已经应用了顺时针 90 度的旋转。除此之外，文本主体本身又应用了逆时针 -90 度的旋转。这样，最终的形状看起来已旋转，但其中的文本看起来好像根本没有被旋转。

## 另请参见

* 类 [ITextFrameFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)