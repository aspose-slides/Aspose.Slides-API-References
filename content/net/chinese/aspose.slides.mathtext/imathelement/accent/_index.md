---
title: Accent
second_title: Aspose.Slides for .NET API 参考
description: 设置重音符号此元素顶部的字符
type: docs
weight: 10
url: /zh/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement.Accent method

设置重音符号（此元素顶部的字符）

```csharp
public IMathAccent Accent(char accentCharacter)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| accentCharacter | Char | 重音字符。该值应在 (U+0300–U+036F) 或 (U+20D0–U+20EF) |

### 返回值

类型的新实例[`IMathAccent`](../../imathaccent)

### 例子

示例:

```csharp
[C#]
IMathAccent accent = new MathematicalText("x").Accent('~');
```

### 也可以看看

* interface [IMathAccent](../../imathaccent)
* interface [IMathElement](../../imathelement)
* 命名空间 [Aspose.Slides.MathText](../../imathelement)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
