---
title: IMathRadical
second_title: Aspose.Slides for .NET API 参考
description: 指定根函数由一个基数和一个可选的度数组成 激进宾语的例子是
type: docs
weight: 7710
url: /zh/net/aspose.slides.mathtext/imathradical/
---
## IMathRadical interface

指定根函数，由一个基数和一个可选的度数组成。 激进宾语的例子是√𝑥。

```csharp
public interface IMathRadical : IMathElement
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathradical/asimathelement) { get; } | 允许获取基础 IMathElement 接口 [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathradical/base) { get; } | 基本参数 |
| [Degree](../../aspose.slides.mathtext/imathradical/degree) { get; } | 度数参数 |
| [HideDegree](../../aspose.slides.mathtext/imathradical/hidedegree) { get; set; } | 隐藏度数 当为真时，度数不显示，如 √𝑥 |

### 例子

示例:

```csharp
[C#]
IMathRadical radical = new MathematicalText("x").Radical("3"); // 立方根
```

### 也可以看看

* interface [IMathElement](../imathelement)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->