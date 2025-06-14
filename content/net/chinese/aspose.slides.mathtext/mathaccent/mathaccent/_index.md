---
title: MathAccent
second_title: Aspose.Sildes for .NET API Reference
description: 创建一个数学重音，应用于指定的数学元素，使用默认的重音字符值
type: docs
weight: 10
url: /zh/aspose.slides.mathtext/mathaccent/mathaccent/
---

## MathAccent(IMathElement) {#constructor}

创建一个数学重音，应用于指定的数学元素，使用默认的重音字符值

```csharp
public MathAccent(IMathElement element)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | IMathElement | 要应用重音的数学元素 |

### 示例

示例:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("x");
MathAccent accent = new MathAccent(baseElement);
```

### 另见

* 接口 [IMathElement](../../imathelement)
* 类 [MathAccent](../../mathaccent)
* 命名空间 [Aspose.Slides.MathText](../../mathaccent)
* 程序集 [Aspose.Slides](../../../)

---

## MathAccent(IMathElement, char) {#constructor_1}

创建一个数学重音，应用于指定的数学元素

```csharp
public MathAccent(IMathElement element, char accentCharacter)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | IMathElement | 要应用重音的数学元素 |
| accentCharacter | Char | 重音字符 |

### 示例

示例:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("x");
MathAccent accent = new MathAccent(baseElement, '~');
```

### 另见

* 接口 [IMathElement](../../imathelement)
* 类 [MathAccent](../../mathaccent)
* 命名空间 [Aspose.Slides.MathText](../../mathaccent)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
