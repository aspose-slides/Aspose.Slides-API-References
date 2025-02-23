---
title: Enclose
second_title: Aspose.Slides for .NET API 参考
description: 将此块的子元素括在指定的字符中例如括号或其他字符作为框架
type: docs
weight: 100
url: /zh/aspose.slides.mathtext/mathblock/enclose/
---
## Enclose(char, char) {#enclose_1}

将此块的子元素括在指定的字符中，例如括号或其他字符作为框架

```csharp
public override IMathDelimiter Enclose(char beginningCharacter, char endingCharacter)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| beginningCharacter | Char | 开始字符（通常是左括号） |
| endingCharacter | Char | 结束字符（通常是右括号） |

### 返回值

[`IMathDelimiter`](../../imathdelimiter)类型的数学元素，其中包括指定字符作为框架

### 例子

示例

```csharp
[C#]
IMathBlock block = new MathematicalText("x").Join("+y");
IMathDelimiter delimiter = block.Enclose('[', ']');
```

### 也可以看看

* interface [IMathDelimiter](../../imathdelimiter)
* class [MathBlock](../../mathblock)
* 命名空间 [Aspose.Slides.MathText](../../mathblock)
* 部件 [Aspose.Slides](../../../)

---

## Enclose(char, char, char) {#enclose_2}

将此块的子元素括在指定字符中，例如括号或其他作为框架 并用分隔符分隔

```csharp
public IMathDelimiter Enclose(char beginningCharacter, char endingCharacter, 
    char separatorCharacter)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| 开始字符 | Char | 开始字符（通常是左括号） |
| 结束字符 | Char | 结束字符（通常是右括号） |
| 分隔符字符 | Char | 分隔符 |

### 返回值

[`IMathDelimiter`](../../imathdelimiter)类型的数学元素，其中包括指定字符作为框架和分隔符

### 例子

示例:

```csharp
[C#]
IMathBlock mathBlock = new MathematicalText("x").Join("y");
IMathDelimiter delimiterElement = mathBlock.Enclose('{', '}', '%');
```

### 也可以看看

* interface [IMathDelimiter](../../imathdelimiter)
* class [MathBlock](../../mathblock)
* 命名空间 [Aspose.Slides.MathText](../../mathblock)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
