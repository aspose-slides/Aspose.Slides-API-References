---
title: Integral
second_title: مرجع API الخاص بـ Aspose.Sildes لـ .NET
description: يأخذ التكامل
type: docs
weight: 80
url: /ar/aspose.slides.mathtext/imathelement/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

يأخذ التكامل

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | نوع التكامل |
| lowerLimit | IMathElement | الحد الأدنى للتكامل |
| upperLimit | IMathElement | الحد الأعلى للتكامل |
| limitLocations | MathLimitLocations | موقع الحدود |

### Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

يأخذ التكامل

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | نوع التكامل |
| lowerLimit | IMathElement | الحد الأدنى للتكامل |
| upperLimit | IMathElement | الحد الأعلى للتكامل |

### Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

يأخذ التكامل بدون حدود

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | نوع التكامل |

### Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

يأخذ التكامل

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | نوع التكامل |
| lowerLimit | String | الحد الأدنى للتكامل |
| upperLimit | String | الحد الأعلى للتكامل |
| limitLocations | MathLimitLocations | موقع الحدود |

### Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

يأخذ التكامل

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | نوع التكامل |
| lowerLimit | String | الحد الأدنى للتكامل |
| upperLimit | String | الحد الأعلى للتكامل |

### Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->