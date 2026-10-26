---
title: Integral
second_title: Aspose.Sildes voor .NET API-referentie
description: Neemt de integraal
type: docs
weight: 80
url: /nl/aspose.slides.mathtext/imathelement/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Neemt de integraal

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integratietype |
| lowerLimit | IMathElement | Ondergrens van integraal |
| upperLimit | IMathElement | Bovengrens van integraal |
| limitLocations | MathLimitLocations | locatie van grenzen |

### Retourwaarde

Nieuwe instantie van type [`IMathNaryOperator`](../../imathnaryoperator)

### Voorbeeld

Voorbeeld:

```csharp
[C#]
IMMathElement baseElement = new MathematicalText("𝑥");
IMMathElement lowerLimit = new MathematicalText("1");
IMMathElement upperLimit = new MathematicalText("2");
IMMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Zie ook

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Neemt de integraal

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integratietype |
| lowerLimit | IMathElement | Ondergrens van integraal |
| upperLimit | IMathElement | Bovengrens van integraal |

### Retourwaarde

Nieuwe instantie van type [`IMathNaryOperator`](../../imathnaryoperator)

### Voorbeeld

Voorbeeld:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Zie ook

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Neemt de integraal zonder grenzen

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integratietype |

### Retourwaarde

Nieuwe instantie van type [`IMathNaryOperator`](../../imathnaryoperator)

### Voorbeeld

Voorbeeld:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Zie ook

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Neemt de integraal

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integratietype |
| lowerLimit | String | Ondergrens van integraal |
| upperLimit | String | Bovengrens van integraal |
| limitLocations | MathLimitLocations | locatie van grenzen |

### Retourwaarde

Nieuwe instantie van type [`IMathNaryOperator`](../../imathnaryoperator)

### Voorbeeld

Voorbeeld:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Zie ook

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Neemt de integraal

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integratietype |
| lowerLimit | String | Ondergrens van integraal |
| upperLimit | String | Bovengrens van integraal |

### Retourwaarde

Nieuwe instantie van type [`IMathNaryOperator`](../../imathnaryoperator)

### Voorbeeld

Voorbeeld:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Zie ook

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->