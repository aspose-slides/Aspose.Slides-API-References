---
title: RowSpacing
second_title: Aspose.Slides for .NET API 参考
description: 数组行之间的间距 仅当 RowSpacingRule 设置为 3 时才使用在这种情况下度量单位是点 或倍数在这种情况下度量单位是半线 默认值0
type: docs
weight: 60
url: /zh/aspose.slides.mathtext/matharray/rowspacing/
---
## MathArray.RowSpacing property

数组行之间的间距 仅当 RowSpacingRule 设置为 3 时才使用，在这种情况下，度量单位是点 或倍数，在这种情况下，度量单位是半线。 默认值:0

```csharp
public uint RowSpacing { get; set; }
```

### 例子

示例:

```csharp
[C#]
IMathArray mathArray = new MathArray(new MathematicalText("item1"));
mathArray.RowSpacingRule = MathRowSpacingRule.Exactly;
mathArray.RowSpacing = 10;
```

### 也可以看看

* class [MathArray](../../matharray)
* 命名空间 [Aspose.Slides.MathText](../../matharray)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
