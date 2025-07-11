---
title: EndingCharacter
second_title: Aspose.Sildes for .NET API Reference
description: 分隔符结束字符指定结束或关闭的分隔符字符。数学分隔符是诸如括号、方括号和花括号等封闭字符。默认值为''。
type: docs
weight: 50
url: /zh/aspose.slides.mathtext/imathdelimiter/endingcharacter/
---

## IMathDelimiter.EndingCharacter 属性

分隔符结束字符指定结束或关闭的分隔符字符。数学分隔符是诸如括号、方括号和花括号等封闭字符。默认值为')'。

```csharp
public char EndingCharacter { get; set; }
```

### 示例

示例：

```csharp
[C#]
IMathDelimiter delimiter = new MathematicalText("x").Join("y").Enclose();
delimiter.EndingCharacter = ']';
```

### 另请参阅

* 接口 [IMathDelimiter](../../imathdelimiter)
* 命名空间 [Aspose.Slides.MathText](../../imathdelimiter)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->