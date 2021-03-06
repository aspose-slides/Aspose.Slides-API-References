---
title: MathBorderBox
second_title: Aspose.Slides for .NET API 参考
description: 创建带有矩形边框的 MathBorderBox 元素
type: docs
weight: 10
url: /zh/net/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox(IMathElement) {#constructor}

创建带有矩形边框的 MathBorderBox 元素

```csharp
public MathBorderBox(IMathElement element)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| element | IMathElement | 应用边框的基本元素。可以为空。 |

### 例子

示例：

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```

### 也可以看看

* interface [IMathElement](../../imathelement)
* class [MathBorderBox](../../mathborderbox)
* 命名空间 [Aspose.Slides.MathText](../../mathborderbox)
* 部件 [Aspose.Slides](../../../)

---

## MathBorderBox(IMathElement, bool, bool, bool, bool, bool, bool, bool, bool) {#constructor_1}

创建 MathBorderBox 元素

```csharp
public MathBorderBox(IMathElement element, bool hideTop, bool hideBottom, bool hideLeft, 
    bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, 
    bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| element | IMathElement | 应用边框的基本元素 |
| hideTop | Boolean | 隐藏顶部边缘 |
| hideBottom | Boolean | 隐藏底边 |
| hideLeft | Boolean | 隐藏左边缘 |
| hideRight | Boolean | 隐藏右边缘 |
| strikethroughHorizontal | Boolean | 水平删除线 |
| strikethroughVertical | Boolean | 删除线垂直 |
| strikethroughBottomLeftToTopRight | Boolean | 删除线从左下到右上角 |
| strikethroughTopLeftToBottomRight | Boolean | 删除线从左上到右下 |

### 例子

示例：

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
```

### 也可以看看

* interface [IMathElement](../../imathelement)
* class [MathBorderBox](../../mathborderbox)
* 命名空间 [Aspose.Slides.MathText](../../mathborderbox)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
