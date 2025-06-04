---
title: Integral
second_title: Aspose.Sildes for .NET API Reference
description: 计算积分
type: docs
weight: 70
url: /zh/aspose.slides.mathtext/mathelementbase/integral/
---

## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

计算积分

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 积分类型 |
| lowerLimit | IMathElement | 积分下限 |
| upperLimit | IMathElement | 积分上限 |
| limitLocations | MathLimitLocations | 限制位置 |

### 返回值

新实例类型 [`IMathNaryOperator`](../../imathnaryoperator)

### 示例

示例：

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### 参见

* 接口 [IMathNaryOperator](../../imathnaryoperator)
* 枚举 [MathIntegralTypes](../../mathintegraltypes)
* 接口 [IMathElement](../../imathelement)
* 枚举 [MathLimitLocations](../../mathlimitlocations)
* 类 [MathElementBase](../../mathelementbase)
* 命名空间 [Aspose.Slides.MathText](../../mathelementbase)
* 程序集 [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

计算积分

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 积分类型 |
| lowerLimit | IMathElement | 积分下限 |
| upperLimit | IMathElement | 积分上限 |

### 返回值

新实例类型 [`IMathNaryOperator`](../../imathnaryoperator)

### 示例

示例：

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### 参见

* 接口 [IMathNaryOperator](../../imathnaryoperator)
* 枚举 [MathIntegralTypes](../../mathintegraltypes)
* 接口 [IMathElement](../../imathelement)
* 类 [MathElementBase](../../mathelementbase)
* 命名空间 [Aspose.Slides.MathText](../../mathelementbase)
* 程序集 [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

计算无界积分

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 积分类型 |

### 返回值

新实例类型 [`IMathNaryOperator`](../../imathnaryoperator)

### 示例

示例：

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### 参见

* 接口 [IMathNaryOperator](../../imathnaryoperator)
* 枚举 [MathIntegralTypes](../../mathintegraltypes)
* 类 [MathElementBase](../../mathelementbase)
* 命名空间 [Aspose.Slides.MathText](../../mathelementbase)
* 程序集 [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

计算积分

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 积分类型 |
| lowerLimit | String | 积分下限 |
| upperLimit | String | 积分上限 |
| limitLocations | MathLimitLocations | 限制位置 |

### 返回值

新实例类型 [`IMathNaryOperator`](../../imathnaryoperator)

### 示例

示例：

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### 参见

* 接口 [IMathNaryOperator](../../imathnaryoperator)
* 枚举 [MathIntegralTypes](../../mathintegraltypes)
* 枚举 [MathLimitLocations](../../mathlimitlocations)
* 类 [MathElementBase](../../mathelementbase)
* 命名空间 [Aspose.Slides.MathText](../../mathelementbase)
* 程序集 [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

计算积分

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 积分类型 |
| lowerLimit | String | 积分下限 |
| upperLimit | String | 积分上限 |

### 返回值

新实例类型 [`IMathNaryOperator`](../../imathnaryoperator)

### 示例

示例：

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### 参见

* 接口 [IMathNaryOperator](../../imathnaryoperator)
* 枚举 [MathIntegralTypes](../../mathintegraltypes)
* 类 [MathElementBase](../../mathelementbase)
* 命名空间 [Aspose.Slides.MathText](../../mathelementbase)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->