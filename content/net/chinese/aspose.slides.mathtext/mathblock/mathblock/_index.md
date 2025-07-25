---
title: MathBlock
second_title: Aspose.Sildes for .NET API Reference
description: 初始化 MathBlock 类的新实例。
type: docs
weight: 10
url: /zh/aspose.slides.mathtext/mathblock/mathblock/
---

## MathBlock() {#constructor}

初始化 MathBlock 类的新实例。

```csharp
public MathBlock()
```

### 示例

示例：

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### 参见

* 类 [MathBlock](../../mathblock)
* 命名空间 [Aspose.Slides.MathText](../../mathblock)
* 程序集 [Aspose.Slides](../../../)

---

## MathBlock(IMathElement) {#constructor_1}

创建一个新的数学块并将指定的元素放入其中

```csharp
public MathBlock(IMathElement mathElement)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElement | IMathElement | 要放入块中的数学元素 |

### 示例

示例：

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
```

### 参见

* 接口 [IMathElement](../../imathelement)
* 类 [MathBlock](../../mathblock)
* 命名空间 [Aspose.Slides.MathText](../../mathblock)
* 程序集 [Aspose.Slides](../../../)

---

## MathBlock(IEnumerable&lt;IMathElement&gt;) {#constructor_2}

创建一个新的数学块并将指定的元素放入其中

```csharp
public MathBlock(IEnumerable<IMathElement> mathElements)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathElements | IEnumerable`1 | 要放入块中的数学元素 |

### 示例

示例：

```csharp
[C#]
var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
MathBlock mathBlock = new MathBlock(elems);
```

### 参见

* 接口 [IMathElement](../../imathelement)
* 类 [MathBlock](../../mathblock)
* 命名空间 [Aspose.Slides.MathText](../../mathblock)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->