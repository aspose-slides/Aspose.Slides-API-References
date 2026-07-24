---
title: CreateMathFraction()
second_title: Aspose.Slides için C++ API Referansı
description: Bir matematik kesri oluşturur
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathfractionfactory/createmathfraction/
---
## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) metot


Bir matematik kesri oluşturur

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Numerator |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominator |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Fraction type |

### Dönüş Değeri

Yeni matematik kesri [IMathFraction](../../imathfraction/)

## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metot


Bir matematik kesri oluşturur

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Numerator |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Denominator |

### Dönüş Değeri

Yeni matematik kesri [IMathFraction](../../imathfraction/)

## İlgili

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathFraction](../../imathfraction/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathFractionFactory](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)