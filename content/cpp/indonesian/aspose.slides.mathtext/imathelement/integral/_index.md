---
title: Integral()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengambil integral
type: docs
weight: 196
url: /id/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) metode


Mengambil integral

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipe integral |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Batas bawah integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Batas atas integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | lokasi batas |

### Nilai Kembalian

Instansi baru dari tipe [IMathNaryOperator](../../imathnaryoperator/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metode


Mengambil integral

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipe integral |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Batas bawah integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Batas atas integral |

### Nilai Kembalian

Instansi baru dari tipe [IMathNaryOperator](../../imathnaryoperator/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) metode


Mengambil integral tanpa batas

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipe integral |

### Nilai Kembalian

Instansi baru dari tipe [IMathNaryOperator](../../imathnaryoperator/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) metode


Mengambil integral

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipe integral |
| lowerLimit | [System::String](../../../system/string/) | Batas bawah integral |
| upperLimit | [System::String](../../../system/string/) | Batas atas integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | lokasi batas |

### Nilai Kembalian

Instansi baru dari tipe [IMathNaryOperator](../../imathnaryoperator/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) metode


Mengambil integral

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipe integral |
| lowerLimit | [System::String](../../../system/string/) | Batas bawah integral |
| upperLimit | [System::String](../../../system/string/) | Batas atas integral |

### Nilai Kembalian

Instansi baru dari tipe [IMathNaryOperator](../../imathnaryoperator/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## Lihat Juga

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathNaryOperator](../../imathnaryoperator/)
* Kelas [IMathElement](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)