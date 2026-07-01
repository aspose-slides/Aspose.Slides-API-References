---
title: Integral
second_title: Aspose.Sildes pro .NET API Reference
description: Vytváří integrál
type: docs
weight: 70
url: /cs/aspose.slides.mathtext/mathelementbase/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Vytváří integrál

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| integralType | MathIntegralTypes | Typ integrálu |
| lowerLimit | IMathElement | Dolní mez integrálu |
| upperLimit | IMathElement | Horní mez integrálu |
| limitLocations | MathLimitLocations | umístění limit |

### Návratová hodnota

Nová instance typu [`IMathNaryOperator`](../../imathnaryoperator)

### Příklady

Příklad:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Viz také

* rozhraní [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* rozhraní [IMathElement](../../imathelement)
* enum [MathLimitLocations](../../mathlimitlocations)
* třída [MathElementBase](../../mathelementbase)
* jmenný prostor [Aspose.Slides.MathText](../../mathelementbase)
* sestavení [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Vytváří integrál

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| integralType | MathIntegralTypes | Typ integrálu |
| lowerLimit | IMathElement | Dolní mez integrálu |
| upperLimit | IMathElement | Horní mez integrálu |

### Návratová hodnota

Nová instance typu [`IMathNaryOperator`](../../imathnaryoperator)

### Příklady

Příklad:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Viz také

* rozhraní [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* rozhraní [IMathElement](../../imathelement)
* třída [MathElementBase](../../mathelementbase)
* jmenný prostor [Aspose.Slides.MathText](../../mathelementbase)
* sestavení [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Vytváří integrál bez limitů

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| integralType | MathIntegralTypes | Typ integrálu |

### Návratová hodnota

Nová instance typu [`IMathNaryOperator`](../../imathnaryoperator)

### Příklady

Příklad:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Viz také

* rozhraní [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* třída [MathElementBase](../../mathelementbase)
* jmenný prostor [Aspose.Slides.MathText](../../mathelementbase)
* sestavení [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Vytváří integrál

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| integralType | MathIntegralTypes | Typ integrálu |
| lowerLimit | String | Dolní mez integrálu |
| upperLimit | String | Horní mez integrálu |
| limitLocations | MathLimitLocations | umístění limit |

### Návratová hodnota

Nová instance typu [`IMathNaryOperator`](../../imathnaryoperator)

### Příklady

Příklad:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Viz také

* rozhraní [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* třída [MathElementBase](../../mathelementbase)
* jmenný prostor [Aspose.Slides.MathText](../../mathelementbase)
* sestavení [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Vytváří integrál

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| integralType | MathIntegralTypes | Typ integrálu |
| lowerLimit | String | Dolní mez integrálu |
| upperLimit | String | Horní mez integrálu |

### Návratová hodnota

Nová instance typu [`IMathNaryOperator`](../../imathnaryoperator)

### Příklady

Příklad:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Viz také

* rozhraní [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* třída [MathElementBase](../../mathelementbase)
* jmenný prostor [Aspose.Slides.MathText](../../mathelementbase)
* sestavení [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->