---
title: Integral
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mengambil integral
type: docs
weight: 70
url: /id/aspose.slides.mathtext/mathelementbase/integral/
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

### Nilai Kembali

Instansi baru dari tipe [`IMathNaryOperator`](../../imathnaryoperator)

### Contoh

Contoh:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Lihat Juga

* antarmuka [IMathNaryOperator](../../imathnaryoperator)
* enumerasi [MathIntegralTypes](../../mathintegraltypes)
* antarmuka [IMathElement](../../imathelement)
* enumerasi [MathLimitLocations](../../mathlimitlocations)
* kelas [MathElementBase](../../mathelementbase)
* ruang nama [Aspose.Slides.MathText](../../mathelementbase)
* rakitan [Aspose.Slides](../../../)

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

### Nilai Kembali

Instansi baru dari tipe [`IMathNaryOperator`](../../imathnaryoperator)

### Contoh

Contoh:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Lihat Juga

* antarmuka [IMathNaryOperator](../../imathnaryoperator)
* enumerasi [MathIntegralTypes](../../mathintegraltypes)
* antarmuka [IMathElement](../../imathelement)
* kelas [MathElementBase](../../mathelementbase)
* ruang nama [Aspose.Slides.MathText](../../mathelementbase)
* rakitan [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Mengambil integral tanpa batas

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipe integral |

### Nilai Kembali

Instansi baru dari tipe [`IMathNaryOperator`](../../imathnaryoperator)

### Contoh

Contoh:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Lihat Juga

* antarmuka [IMathNaryOperator](../../imathnaryoperator)
* enumerasi [MathIntegralTypes](../../mathintegraltypes)
* kelas [MathElementBase](../../mathelementbase)
* ruang nama [Aspose.Slides.MathText](../../mathelementbase)
* rakitan [Aspose.Slides](../../../)

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

### Nilai Kembali

Instansi baru dari tipe [`IMathNaryOperator`](../../imathnaryoperator)

### Contoh

Contoh:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Lihat Juga

* antarmuka [IMathNaryOperator](../../imathnaryoperator)
* enumerasi [MathIntegralTypes](../../mathintegraltypes)
* enumerasi [MathLimitLocations](../../mathlimitlocations)
* kelas [MathElementBase](../../mathelementbase)
* ruang nama [Aspose.Slides.MathText](../../mathelementbase)
* rakitan [Aspose.Slides](../../../)

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

### Nilai Kembali

Instansi baru dari tipe [`IMathNaryOperator`](../../imathnaryoperator)

### Contoh

Contoh:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Lihat Juga

* antarmuka [IMathNaryOperator](../../imathnaryoperator)
* enumerasi [MathIntegralTypes](../../mathintegraltypes)
* kelas [MathElementBase](../../mathelementbase)
* ruang nama [Aspose.Slides.MathText](../../mathelementbase)
* rakitan [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->