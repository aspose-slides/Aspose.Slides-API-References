---
title: get_RotationAngle()
second_title: Aspose.Slides for C++ API 参考
description: 指定应用于边界框内文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果已指定，则该旋转独立于形状应用。也就是说，形状可以有一个旋转，同时文本本身也可以有一个旋转。该属性以及属性 TextVerticalType 中的预定义垂直类型共同汇总得到的视觉文本旋转值。读取 float.
type: docs
weight: 235
url: /zh/aspose.slides.charts/icharttextblockformat/get_rotationangle/
---
## IChartTextBlockFormat::get_RotationAngle() 方法

指定应用于边界框内文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果已指定，则该旋转独立于形状应用。也就是说，形状可以有一个旋转，同时文本本身也可以有一个旋转。该属性以及属性 TextVerticalType 中的预定义垂直类型共同汇总得到的视觉文本旋转值。读取 **float**。

```cpp
virtual float Aspose::Slides::Charts::IChartTextBlockFormat::get_RotationAngle()=0
```

## 备注

考虑一种情况：形状被应用了顺时针 90 度的旋转。此外，文本主体本身被应用了逆时针 -90 度的旋转。这样，最终的形状看起来是旋转的，但其中的文本看起来好像根本没有被旋转。

## 另见

* 类 [IChartTextBlockFormat](../)
* 命名空间 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)