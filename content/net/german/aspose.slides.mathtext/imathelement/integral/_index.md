---
title: Integral
second_title: Aspose.Slides für .NET API Referenz
description: Nimmt das Integral
type: docs
weight: 80
url: /de/aspose.slides.mathtext/imathelement/integral/
---

## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Nimmt das Integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integrartyp |
| lowerLimit | IMathElement | Untere Grenze des Integrals |
| upperLimit | IMathElement | Obere Grenze des Integrals |
| limitLocations | MathLimitLocations | Lage der Grenzen |

### Rückgabewert

Neue Instanz vom Typ [`IMathNaryOperator`](../../imathnaryoperator)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Siehe Auch

* Schnittstelle [IMathNaryOperator](../../imathnaryoperator)
* Enum [MathIntegralTypes](../../mathintegraltypes)
* Enum [MathLimitLocations](../../mathlimitlocations)
* Schnittstelle [IMathElement](../../imathelement)
* Namespace [Aspose.Slides.MathText](../../imathelement)
* Assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Nimmt das Integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integrartyp |
| lowerLimit | IMathElement | Untere Grenze des Integrals |
| upperLimit | IMathElement | Obere Grenze des Integrals |

### Rückgabewert

Neue Instanz vom Typ [`IMathNaryOperator`](../../imathnaryoperator)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Siehe Auch

* Schnittstelle [IMathNaryOperator](../../imathnaryoperator)
* Enum [MathIntegralTypes](../../mathintegraltypes)
* Schnittstelle [IMathElement](../../imathelement)
* Namespace [Aspose.Slides.MathText](../../imathelement)
* Assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Nimmt das Integral ohne Grenzen

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integrartyp |

### Rückgabewert

Neue Instanz vom Typ [`IMathNaryOperator`](../../imathnaryoperator)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Siehe Auch

* Schnittstelle [IMathNaryOperator](../../imathnaryoperator)
* Enum [MathIntegralTypes](../../mathintegraltypes)
* Schnittstelle [IMathElement](../../imathelement)
* Namespace [Aspose.Slides.MathText](../../imathelement)
* Assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Nimmt das Integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integrartyp |
| lowerLimit | String | Untere Grenze des Integrals |
| upperLimit | String | Obere Grenze des Integrals |
| limitLocations | MathLimitLocations | Lage der Grenzen |

### Rückgabewert

Neue Instanz vom Typ [`IMathNaryOperator`](../../imathnaryoperator)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Siehe Auch

* Schnittstelle [IMathNaryOperator](../../imathnaryoperator)
* Enum [MathIntegralTypes](../../mathintegraltypes)
* Enum [MathLimitLocations](../../mathlimitlocations)
* Schnittstelle [IMathElement](../../imathelement)
* Namespace [Aspose.Slides.MathText](../../imathelement)
* Assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Nimmt das Integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integrartyp |
| lowerLimit | String | Untere Grenze des Integrals |
| upperLimit | String | Obere Grenze des Integrals |

### Rückgabewert

Neue Instanz vom Typ [`IMathNaryOperator`](../../imathnaryoperator)

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Siehe Auch

* Schnittstelle [IMathNaryOperator](../../imathnaryoperator)
* Enum [MathIntegralTypes](../../mathintegraltypes)
* Schnittstelle [IMathElement](../../imathelement)
* Namespace [Aspose.Slides.MathText](../../imathelement)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->