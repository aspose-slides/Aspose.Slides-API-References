---
title: set_RotationAngle()
second_title: Aspose.Slides for C++ API 参考
description: 指定在边界框内应用于文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果已指定，则独立于形状应用。也就是说，形状可以有旋转，同时文本本身也可以有旋转。该属性与属性 TextVerticalType 中的预定义垂直类型共同决定可视文本旋转的最终值。写入 float.
type: docs
weight: 248
url: /zh/aspose.slides.charts/icharttextblockformat/set_rotationangle/
---
## IChartTextBlockFormat::set_RotationAngle(float) 方法

指定在边界框内应用于文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果已指定，则独立于形状应用。也就是说，形状可以有旋转，同时文本本身也可以有旋转。该属性与属性 TextVerticalType 中的预定义垂直类型共同决定可视文本旋转的最终值。写入 **float**。

```cpp
virtual void Aspose::Slides::Charts::IChartTextBlockFormat::set_RotationAngle(float value)=0
```

## 备注

考虑一种情况：形状被顺时针旋转了 90 度。此外，文本主体本身被逆时针旋转了 -90 度。这样，形状看起来已旋转，但其中的文本看起来好像根本没有被旋转。

## 另请参见

* 类 [IChartTextBlockFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* 库 [Aspose.Slides](../../../)