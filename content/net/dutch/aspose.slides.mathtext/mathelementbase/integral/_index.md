---
title: Integral
second_title: Aspose.Slides voor .NET API-referentie
description: Neemt de integraal
type: docs
weight: 70
url: /nl/aspose.slides.mathtext/mathelementbase/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Neemt de integraal

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integratietype |
| lowerLimit | IMathElement | Ondergrens van integraal |
| upperLimit | IMathElement | Bovengrens van integraal |
| limitLocations | MathLimitLocations | locatie van limieten |

### Return Value

Nieuwe instantie van type [`IMathNaryOperator`](../../imathnaryoperator)

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
* enum [MathLimitLocations](../../mathlimitlocations)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Neemt de integraal

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integratietype |
| lowerLimit | IMathElement | Ondergrens van integraal |
| upperLimit | IMathElement | Bovengrens van integraal |

### Return Value

Nieuwe instantie van type [`IMathNaryOperator`](../../imathnaryoperator)

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
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Neemt de integraal zonder limieten

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integratietype |

### Return Value

Nieuwe instantie van type [`IMathNaryOperator`](../../imathnaryoperator)

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
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Neemt de integraal

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integratietype |
| lowerLimit | String | Ondergrens van integraal |
| upperLimit | String | Bovengrens van integraal |
| limitLocations | MathLimitLocations | locatie van limieten |

### Return Value

Nieuwe instantie van type [`IMathNaryOperator`](../../imathnaryoperator)

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
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Neemt de integraal

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integratietype |
| lowerLimit | String | Ondergrens van integraal |
| upperLimit | String | Bovengrens van integraal |

### Return Value

Nieuwe instantie van type [`IMathNaryOperator`](../../imathnaryoperator)

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
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->