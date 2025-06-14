---
title: DelimiterShape
second_title: Aspose.Sildes for .NET API Reference
description: 指定分隔符对象中分隔符的形状。当是 MathDelimiterShape.Centered 时，分隔符围绕数学文本的数学轴居中，并且仍然可以完全适应其内容的高度。当是 MathDelimiterShape.Match 时，它们的高度和形状会被修改以完全匹配其内容。
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/imathdelimiter/delimitershape/
---

## IMathDelimiter.DelimiterShape 属性

指定分隔符对象中分隔符的形状。当是 MathDelimiterShape.Centered 时，分隔符围绕数学文本的数学轴居中，并且仍然可以完全适应其内容的高度。当是 MathDelimiterShape.Match 时，它们的高度和形状会被修改以完全匹配其内容。

```csharp
public MathDelimiterShape DelimiterShape { get; set; }
```

### 示例

示例：

```csharp
[C#]
IMathDelimiter delimiter = new MathematicalText("x").Divide("y").Enclose();
delimiter.DelimiterShape = MathDelimiterShape.Match;
```

### 另请参阅

* enum [MathDelimiterShape](../../mathdelimitershape)
* interface [IMathDelimiter](../../imathdelimiter)
* namespace [Aspose.Slides.MathText](../../imathdelimiter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->