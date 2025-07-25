---
title: Join
second_title: Aspose.Sildes for .NET API Reference
description: 连接数学元素并形成数学块
type: docs
weight: 80
url: /zh/aspose.slides.mathtext/mathelementbase/join/
---

## Join(IMathElement) {#join}

连接数学元素并形成数学块

```csharp
public virtual IMathBlock Join(IMathElement mathElement)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElement | IMathElement | 要连接的元素 |

### 返回值

一个新的 IMathBlock，包含该实例和指定的参数

### 示例

示例:

```csharp
[C#]
IMathElement element1 = new MathematicalText("x");
IMathElement element2 = new MathematicalText("y");
IMathBlock block = element1.Join(element2);
```

### 另见

* interface [IMathBlock](../../imathblock)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Join(string) {#join_1}

连接数学文本并形成数学块

```csharp
public virtual IMathBlock Join(string mathText)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathText | String | 要连接的数学文本 |

### 返回值

一个新的 IMathBlock，包含该实例和指定的参数

### 示例

示例:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
IMathBlock block = element.Join("+y");
```

### 另见

* interface [IMathBlock](../../imathblock)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
