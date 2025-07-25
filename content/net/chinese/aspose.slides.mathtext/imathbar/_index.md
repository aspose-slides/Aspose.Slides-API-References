---
title: IMathBar
second_title: Aspose.Sildes for .NET API Reference
description: 指定由基础参数和上划线或下划线组成的条形函数
type: docs
weight: 7870
url: /zh/aspose.slides.mathtext/imathbar/
---

## IMathBar 接口

指定条形函数，由基础参数和上划线或下划线组成

```csharp
public interface IMathBar : IMathElement
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathbar/asimathelement) { get; } | 允许获取基础 IMathElement 接口 [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathbar/base) { get; } | 基础参数 |
| [Position](../../aspose.slides.mathtext/imathbar/position) { get; set; } | 条形线的位置。默认值：顶部 |

### 示例

示例：

```csharp
[C#]
IMathBar mathBar = new MathBar(new MathematicalText("x"));
```

### 另见

* 接口 [IMathElement](../imathelement)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->