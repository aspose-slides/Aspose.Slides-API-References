---
title: Character
second_title: Aspose.Slides for .NET API 参考
description: 重音字符 该值应在 U0300U036F 或 U20D0U20EF 范围内 默认值结合 Circumflex 重音 U0302
type: docs
weight: 30
url: /zh/net/aspose.slides.mathtext/mathaccent/character/
---
## MathAccent.Character property

重音字符 该值应在 (U+0300–U+036F) 或 (U+20D0–U+20EF) 范围内) 默认值:结合 Circumflex 重音 (U+0302)

```csharp
public char Character { get; set; }
```

### 例子

示例::::47::

```csharp
[C#]
IMathAccent accent = new MathematicalText("x").Accent('~');
char ch = accent.Character;
```

### 也可以看看

* class [MathAccent](../../mathaccent)
* 命名空间 [Aspose.Slides.MathText](../../mathaccent)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->