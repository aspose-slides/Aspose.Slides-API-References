---
title: Integral
second_title: Aspose.Slides for .NET API 参考
description: 取整数
type: docs
weight: 70
url: /zh/aspose.slides.mathtext/mathelementbase/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

取整数

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 积分类型 |
| lowerLimit | IMathElement | 积分下限 |
| upperLimit | IMathElement | 积分上限 |
| limitLocations | MathLimitLocations | 限制位置 |

### 返回值

类型的新实例[`IMathNaryOperator`](../../imathnaryoperator)

### 例子

示例:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### 也可以看看

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* enum [MathLimitLocations](../../mathlimitlocations)
* class [MathElementBase](../../mathelementbase)
* 命名空间 [Aspose.Slides.MathText](../../mathelementbase)
* 部件 [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

取整数

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 积分类型 |
| lowerLimit | IMathElement | 积分下限 |
| upperLimit | IMathElement | 积分上限 |

### 返回值

类型的新实例[`IMathNaryOperator`](../../imathnaryoperator)

### 例子

示例::::47::

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### 也可以看看

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* 命名空间 [Aspose.Slides.MathText](../../mathelementbase)
* 部件 [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

无限制地取积分

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 积分类型 |

### 返回值

类型的新实例[`IMathNaryOperator`](../../imathnaryoperator)

### 例子

示例:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### 也可以看看

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* class [MathElementBase](../../mathelementbase)
* 命名空间 [Aspose.Slides.MathText](../../mathelementbase)
* 部件 [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

取整数

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 积分类型 |
| lowerLimit | String | 积分下限 |
| upperLimit | String | 积分上限 |
| limitLocations | MathLimitLocations | 限制位置 |

### 返回值

类型的新实例[`IMathNaryOperator`](../../imathnaryoperator)

### 例子

示例:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### 也可以看看

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* class [MathElementBase](../../mathelementbase)
* 命名空间 [Aspose.Slides.MathText](../../mathelementbase)
* 部件 [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

取整数

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| integralType | MathIntegralTypes | 积分类型 |
| lowerLimit | String | 积分下限 |
| upperLimit | String | 积分上限 |

### 返回值

类型的新实例[`IMathNaryOperator`](../../imathnaryoperator)

### 例子

示例::::47::

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### 也可以看看

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* class [MathElementBase](../../mathelementbase)
* 命名空间 [Aspose.Slides.MathText](../../mathelementbase)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
