---
title: GrowToMatchOperandHeight
second_title: Aspose.Slides for .NET API 参考
description: 指定BeginningCharacterSeparatorCharacterEndingCharacter的增长 当为true时分隔符垂直增长以匹配其操作数高度 默认值为true
type: docs
weight: 60
url: /zh/net/aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight/
---
## MathDelimiter.GrowToMatchOperandHeight property

指定BeginningCharacter、SeparatorCharacter、EndingCharacter的增长 当为true时，分隔符垂直增长以匹配其操作数高度。 默认值为true

```csharp
public bool GrowToMatchOperandHeight { get; set; }
```

### 例子

示例：

```csharp
[C#]
IMathDelimiter delimiter = new MathematicalText("x").Divide("y").Enclose();
delimiter.GrowToMatchOperandHeight = false;
```

### 也可以看看

* class [MathDelimiter](../../mathdelimiter)
* 命名空间 [Aspose.Slides.MathText](../../mathdelimiter)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
