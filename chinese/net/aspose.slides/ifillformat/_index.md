---
title: IFillFormat
second_title: Aspose.Slides for .NET API 参考
description: 表示填充格式选项
type: docs
weight: 5270
url: /zh/net/aspose.slides/ifillformat/
---
## IFillFormat interface

表示填充格式选项。

```csharp
public interface IFillFormat : IFillParamSource
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ifillformat/asifillparamsource) { get; } | 允许获取基本的 IFillParamSource 接口。 只读[`IFillParamSource`](../ifillparamsource)。 |
| [FillType](../../aspose.slides/ifillformat/filltype) { get; set; } | 返回或设置填充类型。 读/写[`FillType`](../filltype)。 |
| [GradientFormat](../../aspose.slides/ifillformat/gradientformat) { get; } | 返回渐变填充格式。 只读[`IGradientFormat`](../igradientformat)。 |
| [PatternFormat](../../aspose.slides/ifillformat/patternformat) { get; } | 返回图案填充格式。 只读[`IPatternFormat`](../ipatternformat)。 |
| [PictureFillFormat](../../aspose.slides/ifillformat/picturefillformat) { get; } | 返回图片填充格式。 只读[`IPictureFillFormat`](../ipicturefillformat)。 |
| [RotateWithShape](../../aspose.slides/ifillformat/rotatewithshape) { get; set; } | 确定填充是否应随形状旋转。 读/写[`NullableBool`](../nullablebool)。 |
| [SolidFillColor](../../aspose.slides/ifillformat/solidfillcolor) { get; } | 返回填充颜色。 只读[`IColorFormat`](../icolorformat)。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetEffective](../../aspose.slides/ifillformat/geteffective)() | 获取应用继承的有效填充格式数据。 |

### 也可以看看

* interface [IFillParamSource](../ifillparamsource)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->