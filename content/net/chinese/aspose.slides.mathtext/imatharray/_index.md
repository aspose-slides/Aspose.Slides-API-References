---
title: IMathArray
second_title: Aspose.Sildes for .NET API Reference
description: 指定一组方程或任何数学对象的垂直数组
type: docs
weight: 7850
url: /zh/aspose.slides.mathtext/imatharray/
---

## IMathArray 接口

指定一组方程或任何数学对象的垂直数组

```csharp
public interface IMathArray : IMathElement
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/imatharray/arguments) { get; } | 数组的项目集合 |
| [AsIMathElement](../../aspose.slides.mathtext/imatharray/asimathelement) { get; } | 允许获取基接口 IMathElement [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imatharray/basejustification) { get; set; } | 指定数组相对于周围文本的对齐方式 数组外的文本可以与数组对象的底部、顶部或中心对齐。 默认值：Center |
| [MaximumDistribution](../../aspose.slides.mathtext/imatharray/maximumdistribution) { get; set; } | 最大分布 为 true 时，数组的间隔扩展到包含元素（页面、列、单元格等）的最大宽度。 |
| [ObjectDistribution](../../aspose.slides.mathtext/imatharray/objectdistribution) { get; set; } | 对象分布 为 true 时，数组的内容间隔扩展到数组对象的最大宽度。 |
| [RowSpacing](../../aspose.slides.mathtext/imatharray/rowspacing) { get; set; } | 数组行之间的间距 仅在 RowSpacingRule 设置为 3 时使用，确切情况下计量单位为点，或设置为倍数时计量单位为半行。 默认值：0 |
| [RowSpacingRule](../../aspose.slides.mathtext/imatharray/rowspacingrule) { get; set; } | 数组元素之间的垂直间距类型 |

### 示例

示例：

```csharp
[C#]
IMathArray mathArray = new MathArray(new MathematicalText("item1"));
```

### 另请参阅

* 接口 [IMathElement](../imathelement)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->