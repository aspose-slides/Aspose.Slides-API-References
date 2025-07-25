---
title: IChartTextBlockFormat
second_title: Aspose.Sildes for .NET API Reference
description: 代表图表文本元素的格式属性。
type: docs
weight: 1900
url: /zh/aspose.slides.charts/icharttextblockformat/
---

## IChartTextBlockFormat 接口

代表图表文本元素的格式属性。

```csharp
public interface IChartTextBlockFormat
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AnchoringType](../../aspose.slides.charts/icharttextblockformat/anchoringtype) { get; set; } | 返回或设置文本框中的垂直锚文本。可读写 [`TextAnchorType`](../../aspose.slides/textanchortype)。 |
| [AutofitType](../../aspose.slides.charts/icharttextblockformat/autofittype) { get; set; } | 返回或设置文本的自动适应模式。更改此属性仅对这些图表部分产生某种影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中没有渲染效果）。可读写 [`TextAutofitType`](../../aspose.slides/textautofittype)。 |
| [CenterText](../../aspose.slides.charts/icharttextblockformat/centertext) { get; set; } | 如果 NullableBool.True，则文本在框中应水平居中。可读写 [`NullableBool`](../../aspose.slides/nullablebool)。 |
| [MarginBottom](../../aspose.slides.charts/icharttextblockformat/marginbottom) { get; set; } | 返回或设置文本框的底部边距（点）。更改此属性仅对这些图表部分产生某种影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中没有渲染效果）。可读写 Double。 |
| [MarginLeft](../../aspose.slides.charts/icharttextblockformat/marginleft) { get; set; } | 返回或设置文本框的左侧边距（点）。更改此属性仅对这些图表部分产生某种影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中没有渲染效果）。可读写 Double。 |
| [MarginRight](../../aspose.slides.charts/icharttextblockformat/marginright) { get; set; } | 返回或设置文本框的右侧边距（点）。更改此属性仅对这些图表部分产生某种影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中没有渲染效果）。可读写 Double。 |
| [MarginTop](../../aspose.slides.charts/icharttextblockformat/margintop) { get; set; } | 返回或设置文本框的顶部边距（点）。更改此属性仅对这些图表部分产生某种影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2013 中完全支持；在 PowerPoint 2007 中没有渲染效果）。可读写 Double。 |
| [RotationAngle](../../aspose.slides.charts/icharttextblockformat/rotationangle) { get; set; } | 指定应用于边界框内文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果指定，则将独立于形状单独应用。这意味着形状可以应用旋转，而文本本身也可以有单独的旋转。由此属性和属性 TextVerticalType 中预定义的垂直类型综合得出的可视文本旋转值。可读写 Single。 |
| [TextVerticalType](../../aspose.slides.charts/icharttextblockformat/textverticaltype) { get; set; } | 决定文本方向。由此属性和属性 RotationAngle 中的自定义角度综合得出的可视文本旋转值。可读写 [`TextVerticalType`](../../aspose.slides/textverticaltype)。 |
| [WrapText](../../aspose.slides.charts/icharttextblockformat/wraptext) { get; set; } | **True** 如果文本在文本框的边距处换行。更改此属性仅对这些图表部分产生某种影响：DataLabel 和 DataLabelFormat（在 PowerPoint 2007/2013 中完全支持）。可读写 [`NullableBool`](../../aspose.slides/nullablebool)。 |

### 另请参见

* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->