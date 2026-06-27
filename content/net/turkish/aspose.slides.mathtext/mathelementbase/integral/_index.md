---
title: Integral
second_title: Aspose.Sildes .NET için API Referansı
description: Integral alır
type: docs
weight: 70
url: /tr/aspose.slides.mathtext/mathelementbase/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

İntegreyi alır

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | MathIntegralTypes | İntegral tipi |
| lowerLimit | IMathElement | İntegralin alt limiti |
| upperLimit | IMathElement | İntegralin üst limiti |
| limitLocations | MathLimitLocations | limitlerin konumu |

### Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

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

* arayüz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* arayüz [IMathElement](../../imathelement)
* enum [MathLimitLocations](../../mathlimitlocations)
* sınıf [MathElementBase](../../mathelementbase)
* ad alanı [Aspose.Slides.MathText](../../mathelementbase)
* derleme [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

İntegreyi alır

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | MathIntegralTypes | İntegral tipi |
| lowerLimit | IMathElement | İntegralin alt limiti |
| upperLimit | IMathElement | İntegralin üst limiti |

### Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

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

* arayüz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* arayüz [IMathElement](../../imathelement)
* sınıf [MathElementBase](../../mathelementbase)
* ad alanı [Aspose.Slides.MathText](../../mathelementbase)
* derleme [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Limit olmadan integral alır

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | MathIntegralTypes | İntegral tipi |

### Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### See Also

* arayüz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* sınıf [MathElementBase](../../mathelementbase)
* ad alanı [Aspose.Slides.MathText](../../mathelementbase)
* derleme [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

İntegreyi alır

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | MathIntegralTypes | İntegral tipi |
| lowerLimit | String | İntegralin alt limiti |
| upperLimit | String | İntegralin üst limiti |
| limitLocations | MathLimitLocations | limitlerin konumu |

### Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### See Also

* arayüz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* sınıf [MathElementBase](../../mathelementbase)
* ad alanı [Aspose.Slides.MathText](../../mathelementbase)
* derleme [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

İntegreyi alır

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | MathIntegralTypes | İntegral tipi |
| lowerLimit | String | İntegralin alt limiti |
| upperLimit | String | İntegralin üst limiti |

### Return Value

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### See Also

* arayüz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* sınıf [MathElementBase](../../mathelementbase)
* ad alanı [Aspose.Slides.MathText](../../mathelementbase)
* derleme [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->