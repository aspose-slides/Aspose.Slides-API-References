---
title: Function
second_title: Aspose.Sildes for .NET API Reference
description: 使用此实例作为函数名称来接受一个参数的函数
type: docs
weight: 50
url: /zh/aspose.slides.mathtext/mathelementbase/function/
---

## Function(IMathElement) {#function}

使用此实例作为函数名称来接受一个参数的函数

```csharp
public IMathFunction Function(IMathElement functionArgument)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionArgument | IMathElement | 函数的一个参数 |

### 返回值

新数学元素，类型为 [`IMathFunction`](../../imathfunction)

### 示例

示例：

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathElement functionArg = new MathematicalText("x");
IMathFunction func = functionName.Function(functionArg);
```

### 参见

* 接口 [IMathFunction](../../imathfunction)
* 接口 [IMathElement](../../imathelement)
* 类 [MathElementBase](../../mathelementbase)
* 命名空间 [Aspose.Slides.MathText](../../mathelementbase)
* 程序集 [Aspose.Slides](../../../)

---

## Function(string) {#function_1}

使用此实例作为函数名称来接受一个参数的函数

```csharp
public IMathFunction Function(string functionArgument)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| functionArgument | String | 函数的一个参数 |

### 返回值

新数学元素，类型为 [`IMathFunction`](../../imathfunction)

### 示例

示例：

```csharp
[C#]
IMathElement functionName = new MathematicalText("sin");
IMathFunction func = functionName.Function("x");
```

### 参见

* 接口 [IMathFunction](../../imathfunction)
* 类 [MathElementBase](../../mathelementbase)
* 命名空间 [Aspose.Slides.MathText](../../mathelementbase)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->