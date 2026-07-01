---
title: Integral
second_title: Reference API Aspose.Sildes pro .NET
description: Provádí integrál
type: docs
weight: 80
url: /cs/aspose.slides.mathtext/imathelement/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Provádí integrál

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| integralType | MathIntegralTypes | Typ integrálu |
| lowerLimit | IMathElement | Dolní mez integrálu |
| upperLimit | IMathElement | Horní mez integrálu |
| limitLocations | MathLimitLocations | Umístění mezí |

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
* výčet [MathIntegralTypes](../../mathintegraltypes)
* výčet [MathLimitLocations](../../mathlimitlocations)
* rozhraní [IMathElement](../../imathelement)
* jmenný prostor [Aspose.Slides.MathText](../../imathelement)
* sestavení [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Provádí integrál

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
* výčet [MathIntegralTypes](../../mathintegraltypes)
* rozhraní [IMathElement](../../imathelement)
* jmenný prostor [Aspose.Slides.MathText](../../imathelement)
* sestavení [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Provádí integrál bez mezí

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
* výčet [MathIntegralTypes](../../mathintegraltypes)
* rozhraní [IMathElement](../../imathelement)
* jmenný prostor [Aspose.Slides.MathText](../../imathelement)
* sestavení [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Provádí integrál

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| integralType | MathIntegralTypes | Typ integrálu |
| lowerLimit | String | Dolní mez integrálu |
| upperLimit | String | Horní mez integrálu |
| limitLocations | MathLimitLocations | Umístění mezí |

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
* výčet [MathIntegralTypes](../../mathintegraltypes)
* výčet [MathLimitLocations](../../mathlimitlocations)
* rozhraní [IMathElement](../../imathelement)
* jmenný prostor [Aspose.Slides.MathText](../../imathelement)
* sestavení [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Provádí integrál

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
* výčet [MathIntegralTypes](../../mathintegraltypes)
* rozhraní [IMathElement](../../imathelement)
* jmenný prostor [Aspose.Slides.MathText](../../imathelement)
* sestavení [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->