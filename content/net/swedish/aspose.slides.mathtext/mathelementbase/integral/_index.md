---
title: Integral
second_title: Aspose.Sildes för .NET API-referens
description: Tar integral
type: docs
weight: 70
url: /sv/aspose.slides.mathtext/mathelementbase/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Tar integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integraltyp |
| lowerLimit | IMathElement | Nedre gräns för integral |
| upperLimit | IMathElement | Övre gräns för integral |
| limitLocations | MathLimitLocations | Placering av gränser |

### Returvärde

Ny instans av typ [`IMathNaryOperator`](../../imathnaryoperator)

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
* enum [MathLimitLocations](../../mathlimitlocations)
* klass [MathElementBase](../../mathelementbase)
* namnrymd [Aspose.Slides.MathText](../../mathelementbase)
* samling [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Tar integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integraltyp |
| lowerLimit | IMathElement | Nedre gräns för integral |
| upperLimit | IMathElement | Övre gräns för integral |

### Returvärde

Ny instans av typ [`IMathNaryOperator`](../../imathnaryoperator)

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
* klass [MathElementBase](../../mathelementbase)
* namnrymd [Aspose.Slides.MathText](../../mathelementbase)
* samling [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Tar integral utan gränser

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integraltyp |

### Returvärde

Ny instans av typ [`IMathNaryOperator`](../../imathnaryoperator)

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
* klass [MathElementBase](../../mathelementbase)
* namnrymd [Aspose.Slides.MathText](../../mathelementbase)
* samling [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Tar integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integraltyp |
| lowerLimit | String | Nedre gräns för integral |
| upperLimit | String | Övre gräns för integral |
| limitLocations | MathLimitLocations | Placering av gränser |

### Returvärde

Ny instans av typ [`IMathNaryOperator`](../../imathnaryoperator)

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
* klass [MathElementBase](../../mathelementbase)
* namnrymd [Aspose.Slides.MathText](../../mathelementbase)
* samling [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Tar integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integraltyp |
| lowerLimit | String | Nedre gräns för integral |
| upperLimit | String | Övre gräns för integral |

### Returvärde

Ny instans av typ [`IMathNaryOperator`](../../imathnaryoperator)

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
* klass [MathElementBase](../../mathelementbase)
* namnrymd [Aspose.Slides.MathText](../../mathelementbase)
* samling [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->