---
title: set_RotationAngle()
second_title: Aspose.Slides C++ API 参考
description: 指定应用于边界框内文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果已指定，则该旋转独立于形状应用。也就是说，形状可以有旋转，同时文本本身也可以有旋转。该属性与属性 TextVerticalType 中的预定义垂直类型共同汇总得出可视文本旋转的最终值。写入 float.
type: docs
weight: 352
url: /zh/aspose.slides/itextframeformat/set_rotationangle/
---
## ITextFrameFormat::set_RotationAngle(float) 方法


指定应用于边界框内文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果已指定，则该旋转独立于形状应用。也就是说，形状可以有旋转，同时文本本身也可以有旋转。该属性与属性 TextVerticalType 中的预定义垂直类型共同汇总得出可视文本旋转的最终值。写入 **float**。

```cpp
virtual void Aspose::Slides::ITextFrameFormat::set_RotationAngle(float value)=0
```

## 备注


考虑一种情况：形状被应用了顺时针 90 度的旋转。除此之外，文本本身被应用了逆时针 -90 度的旋转。于是，最终的形状看起来已旋转，但其中的文本看起来好像根本没有旋转。

## 另请参见

* 类 [ITextFrameFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)