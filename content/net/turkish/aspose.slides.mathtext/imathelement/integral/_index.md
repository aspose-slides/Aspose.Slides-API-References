---
title: Integral
second_title: Aspose.Sildes için .NET API Referansı
description: İntegrali alır
type: docs
weight: 80
url: /tr/aspose.slides.mathtext/imathelement/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

İntegrali alır

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral tipi |
| lowerLimit | IMathElement | İntegralin alt sınırı |
| upperLimit | IMathElement | İntegralin üst sınırı |
| limitLocations | MathLimitLocations | sınırlıkların konumu |

### Dönüş Değeri

Yeni [`IMathNaryOperator`](../../imathnaryoperator) tipinde örnek

### Örnekler

Örnek:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Ayrıca Bakınız

* arayüz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* arayüz [IMathElement](../../imathelement)
* ad alanı [Aspose.Slides.MathText](../../imathelement)
* derleme [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

İntegrali alır

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral tipi |
| lowerLimit | IMathElement | İntegralin alt sınırı |
| upperLimit | IMathElement | İntegralin üst sınırı |

### Dönüş Değeri

Yeni [`IMathNaryOperator`](../../imathnaryoperator) tipinde örnek

### Örnekler

Örnek:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Ayrıca Bakınız

* arayüz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* arayüz [IMathElement](../../imathelement)
* ad alanı [Aspose.Slides.MathText](../../imathelement)
* derleme [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Sınırlık olmadan integrali alır

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral tipi |

### Dönüş Değeri

Yeni [`IMathNaryOperator`](../../imathnaryoperator) tipinde örnek

### Örnekler

Örnek:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Ayrıca Bakınız

* arayüz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* arayüz [IMathElement](../../imathelement)
* ad alanı [Aspose.Slides.MathText](../../imathelement)
* derleme [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

İntegrali alır

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral tipi |
| lowerLimit | String | İntegralin alt sınırı |
| upperLimit | String | İntegralin üst sınırı |
| limitLocations | MathLimitLocations | sınırlıkların konumu |

### Dönüş Değeri

Yeni [`IMathNaryOperator`](../../imathnaryoperator) tipinde örnek

### Örnekler

Örnek:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Ayrıca Bakınız

* arayüz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* arayüz [IMathElement](../../imathelement)
* ad alanı [Aspose.Slides.MathText](../../imathelement)
* derleme [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

İntegrali alır

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral tipi |
| lowerLimit | String | İntegralin alt sınırı |
| upperLimit | String | İntegralin üst sınırı |

### Dönüş Değeri

Yeni [`IMathNaryOperator`](../../imathnaryoperator) tipinde örnek

### Örnekler

Örnek:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Ayrıca Bakınız

* arayüz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* arayüz [IMathElement](../../imathelement)
* ad alanı [Aspose.Slides.MathText](../../imathelement)
* derleme [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->