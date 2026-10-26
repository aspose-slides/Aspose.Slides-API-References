---
title: Integral
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mengambil integral
type: docs
weight: 80
url: /id/aspose.slides.mathtext/imathelement/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Mengambil integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipe integral |
| lowerLimit | IMathElement | Batas bawah integral |
| upperLimit | IMathElement | Batas atas integral |
| limitLocations | MathLimitLocations | lokasi batas |

### Return Value

Instansi baru dari tipe [`IMathNaryOperator`](../../imathnaryoperator)

### Examples

Contoh:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Mengambil integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipe integral |
| lowerLimit | IMathElement | Batas bawah integral |
| upperLimit | IMathElement | Batas atas integral |

### Return Value

Instansi baru dari tipe [`IMathNaryOperator`](../../imathnaryoperator)

### Examples

Contoh:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Mengambil integral tanpa batas

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipe integral |

### Return Value

Instansi baru dari tipe [`IMathNaryOperator`](../../imathnaryoperator)

### Examples

Contoh:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Mengambil integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipe integral |
| lowerLimit | String | Batas bawah integral |
| upperLimit | String | Batas atas integral |
| limitLocations | MathLimitLocations | lokasi batas |

### Return Value

Instansi baru dari tipe [`IMathNaryOperator`](../../imathnaryoperator)

### Examples

Contoh:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Mengambil integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipe integral |
| lowerLimit | String | Batas bawah integral |
| upperLimit | String | Batas atas integral |

### Return Value

Instansi baru dari tipe [`IMathNaryOperator`](../../imathnaryoperator)

### Examples

Contoh:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### See Also

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->