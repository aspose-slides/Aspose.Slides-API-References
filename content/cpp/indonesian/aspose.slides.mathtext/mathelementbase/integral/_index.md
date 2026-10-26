---
title: Integral()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengambil integral
type: docs
weight: 183
url: /id/aspose.slides.mathtext/mathelementbase/integral/
---
## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) metode


Mengambil integral

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipe integral |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Batas bawah integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Batas atas integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | lokasi batas |

### Nilai Kembali

Instansi baru dari tipe [IMathNaryOperator](../../imathnaryoperator/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metode


Mengambil integral

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipe integral |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Batas bawah integral |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Batas atas integral |

### Nilai Kembali

Instansi baru dari tipe [IMathNaryOperator](../../imathnaryoperator/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"?\?");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes) metode


Mengambil integral tanpa batas

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipe integral |

### Nilai Kembali

Instansi baru dari tipe [IMathNaryOperator](../../imathnaryoperator/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) metode


Mengambil integral

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipe integral |
| lowerLimit | [System::String](../../../system/string/) | Batas bawah integral |
| upperLimit | [System::String](../../../system/string/) | Batas atas integral |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | lokasi batas |

### Nilai Kembali

Instansi baru dari tipe [IMathNaryOperator](../../imathnaryoperator/)
## Catatan



Contoh: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## MathElementBase::Integral(MathIntegralTypes, System::String, System::String) metode


Mengambil integral

```cpp
System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::MathElementBase::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Tipe integral |
| lowerLimit | [System::String](../../../system/string/) | Batas bawah integral |
| upperLimit | [System::String](../../../system/string/) | Batas atas integral |

### Nilai Kembali

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
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)