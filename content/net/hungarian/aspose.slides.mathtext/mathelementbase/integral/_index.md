---
title: Integral
second_title: Aspose.Sildes .NET API Referencia
description: Létrehozza az integrált
type: docs
weight: 70
url: /hu/aspose.slides.mathtext/mathelementbase/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Létrehozza az integrált

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | IMathElement | Lower limit of integral |
| upperLimit | IMathElement | Upper limit of integral |
| limitLocations | MathLimitLocations | location of limits |

### Visszatérési érték

Új példány a(z) [`IMathNaryOperator`](../../imathnaryoperator) típusból

### Példák

Példa:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Lásd még

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* enum [MathLimitLocations](../../mathlimitlocations)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Létrehozza az integrált

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | IMathElement | Lower limit of integral |
| upperLimit | IMathElement | Upper limit of integral |

### Visszatérési érték

Új példány a(z) [`IMathNaryOperator`](../../imathnaryoperator) típusból

### Példák

Példa:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Lásd még

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Létrehozza az integrált korlátok nélkül

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |

### Visszatérési érték

Új példány a(z) [`IMathNaryOperator`](../../imathnaryoperator) típusból

### Példák

Példa:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Lásd még

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Létrehozza az integrált

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | String | Lower limit of integral |
| upperLimit | String | Upper limit of integral |
| limitLocations | MathLimitLocations | location of limits |

### Visszatérési érték

Új példány a(z) [`IMathNaryOperator`](../../imathnaryoperator) típusból

### Példák

Példa:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Lásd még

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Létrehozza az integrált

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | String | Lower limit of integral |
| upperLimit | String | Upper limit of integral |

### Visszatérési érték

Új példány a(z) [`IMathNaryOperator`](../../imathnaryoperator) típusból

### Példák

Példa:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Lásd még

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->