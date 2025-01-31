---
title: IMathAccent
second_title: Aspose.Slides for .NET API 参考
description: 指定重音函数由基数和组合变音符号组成 示例́
type: docs
weight: 7370
url: /zh/aspose.slides.mathtext/imathaccent/
---
## IMathAccent interface

指定重音函数，由基数和组合变音符号组成 示例:𝑎́

```csharp
public interface IMathAccent : IMathElement
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathaccent/asimathelement) { get; } | 允许获取基础 IMathElement 接口 [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathaccent/base) { get; } | 应用重音的参数 |
| [Character](../../aspose.slides.mathtext/imathaccent/character) { get; set; } | 重音字符 该值应在 (U+0300–U+036F) 或 (U+20D0–U+20EF) 范围内) 默认值:结合 Circumflex 重音 (U+0302) |

### 例子

示例:

```csharp
[C#]
IMathAccent accent = new MathematicalText("x").Accent('~');
```

### 也可以看看

* interface [IMathElement](../imathelement)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
