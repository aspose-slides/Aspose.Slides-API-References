---
title: Integral
second_title: Aspose.Sildes .NET API hivatkozás
description: Integrálást végez
type: docs
weight: 80
url: /hu/aspose.slides.mathtext/imathelement/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Integrálást végez

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integrál típus |
| lowerLimit | IMathElement | Integrál alsó határa |
| upperLimit | IMathElement | Integrál felső határa |
| limitLocations | MathLimitLocations | a korlátok helye |

### Visszatérési érték

Új példány a(z) [`IMathNaryOperator`](../../imathnaryoperator) típusú

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

* interfész [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interfész [IMathElement](../../imathelement)
* névtér [Aspose.Slides.MathText](../../imathelement)
* összeállítás [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Integrálást végez

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integrál típus |
| lowerLimit | IMathElement | Integrál alsó határa |
| upperLimit | IMathElement | Integrál felső határa |

### Visszatérési érték

Új példány a(z) [`IMathNaryOperator`](../../imathnaryoperator) típusú

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

* interfész [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interfész [IMathElement](../../imathelement)
* névtér [Aspose.Slides.MathText](../../imathelement)
* összeállítás [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Integrálást végez korlátok nélkül

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integrál típus |

### Visszatérési érték

Új példány a(z) [`IMathNaryOperator`](../../imathnaryoperator) típusú

### Példák

Példa:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Lásd még

* interfész [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interfész [IMathElement](../../imathelement)
* névtér [Aspose.Slides.MathText](../../imathelement)
* összeállítás [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Integrálást végez

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integrál típus |
| lowerLimit | String | Integrál alsó határa |
| upperLimit | String | Integrál felső határa |
| limitLocations | MathLimitLocations | a korlátok helye |

### Visszatérési érték

Új példány a(z) [`IMathNaryOperator`](../../imathnaryoperator) típusú

### Példák

Példa:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Lásd még

* interfész [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interfész [IMathElement](../../imathelement)
* névtér [Aspose.Slides.MathText](../../imathelement)
* összeállítás [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Integrálást végez

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integrál típus |
| lowerLimit | String | Integrál alsó határa |
| upperLimit | String | Integrál felső határa |

### Visszatérési érték

Új példány a(z) [`IMathNaryOperator`](../../imathnaryoperator) típusú

### Példák

Példa:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Lásd még

* interfész [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interfész [IMathElement](../../imathelement)
* névtér [Aspose.Slides.MathText](../../imathelement)
* összeállítás [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->