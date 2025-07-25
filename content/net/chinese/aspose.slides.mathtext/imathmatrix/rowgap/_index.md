---
title: RowGap
second_title: Aspose.Slides for .NET API Reference
description: 矩阵行间垂直间距的值。如果 RowGapRule 设置为 3（“确切”），则单位被解释为 twips（1/20 点）。如果 RowGapRule 设置为 4（“倍数”），则单位被解释为半行。默认值：0
type: docs
weight: 100
url: /zh/aspose.slides.mathtext/imathmatrix/rowgap/
---

## IMathMatrix.RowGap 属性

矩阵行之间垂直间距的值；如果 RowGapRule 设置为 3（“确切”），则单位被解释为 twips（1/20 点）。如果 RowGapRule 设置为 4（“倍数”），则单位被解释为半行。默认值：0

```csharp
public uint RowGap { get; set; }
```

### 示例

示例：

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.RowGapRule = MathSpacingRules.Exactly;
matrix.RowGap = 20;
```

### 另请参见

* 接口 [IMathMatrix](../../imathmatrix)
* 命名空间 [Aspose.Slides.MathText](../../imathmatrix)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->