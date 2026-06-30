---
title: Integral
second_title: Aspose.Sildes för .NET API-referens
description: Tar integralen
type: docs
weight: 80
url: /sv/aspose.slides.mathtext/imathelement/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Tar integralen

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | IMathElement | Lower limit of integral |
| upperLimit | IMathElement | Upper limit of integral |
| limitLocations | MathLimitLocations | plats för gränser |

### Returvärde

Ny instans av typen [`IMathNaryOperator`](../../imathnaryoperator)

### Exempel

Exempel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Se även

* gränssnitt [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* gränssnitt [IMathElement](../../imathelement)
* namnrymd [Aspose.Slides.MathText](../../imathelement)
* samling [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Tar integralen

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | IMathElement | Lower limit of integral |
| upperLimit | IMathElement | Upper limit of integral |

### Returvärde

Ny instans av typen [`IMathNaryOperator`](../../imathnaryoperator)

### Exempel

Exempel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Se även

* gränssnitt [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* gränssnitt [IMathElement](../../imathelement)
* namnrymd [Aspose.Slides.MathText](../../imathelement)
* samling [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Tar integralen utan gränser

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |

### Returvärde

Ny instans av typen [`IMathNaryOperator`](../../imathnaryoperator)

### Exempel

Exempel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Se även

* gränssnitt [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* gränssnitt [IMathElement](../../imathelement)
* namnrymd [Aspose.Slides.MathText](../../imathelement)
* samling [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Tar integralen

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | String | Lower limit of integral |
| upperLimit | String | Upper limit of integral |
| limitLocations | MathLimitLocations | plats för gränser |

### Returvärde

Ny instans av typen [`IMathNaryOperator`](../../imathnaryoperator)

### Exempel

Exempel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Se även

* gränssnitt [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* gränssnitt [IMathElement](../../imathelement)
* namnrymd [Aspose.Slides.MathText](../../imathelement)
* samling [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Tar integralen

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | String | Lower limit of integral |
| upperLimit | String | Upper limit of integral |

### Returvärde

Ny instans av typen [`IMathNaryOperator`](../../imathnaryoperator)

### Exempel

Exempel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Se även

* gränssnitt [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* gränssnitt [IMathElement](../../imathelement)
* namnrymd [Aspose.Slides.MathText](../../imathelement)
* samling [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->