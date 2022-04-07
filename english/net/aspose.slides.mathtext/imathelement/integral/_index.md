---
title: Integral
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 160
url: /net/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement.Integral method (1 of 5)

Takes the integral without limits

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| parameter | description |
| --- | --- |
| integralType | Integral type |

## Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

## Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## IMathElement.Integral method (2 of 5)

Takes the integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| parameter | description |
| --- | --- |
| integralType | Integral type |
| lowerLimit | Lower limit of integral |
| upperLimit | Upper limit of integral |

## Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

## Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## IMathElement.Integral method (3 of 5)

Takes the integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| parameter | description |
| --- | --- |
| integralType | Integral type |
| lowerLimit | Lower limit of integral |
| upperLimit | Upper limit of integral |

## Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

## Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## IMathElement.Integral method (4 of 5)

Takes the integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| parameter | description |
| --- | --- |
| integralType | Integral type |
| lowerLimit | Lower limit of integral |
| upperLimit | Upper limit of integral |
| limitLocations | location of limits |

## Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

## Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## IMathElement.Integral method (5 of 5)

Takes the integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| parameter | description |
| --- | --- |
| integralType | Integral type |
| lowerLimit | Lower limit of integral |
| upperLimit | Upper limit of integral |
| limitLocations | location of limits |

## Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

## Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
