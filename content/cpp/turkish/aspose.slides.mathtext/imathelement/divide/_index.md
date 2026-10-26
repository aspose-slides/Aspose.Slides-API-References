---
title: Divide()
second_title: Aspose.Slides for C++ API Referansı
description: Bu pay ve belirtilen payda ile bir kesir oluşturur
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) metodu


Creates a fraction with this numerator and specified denominator

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Payda |

### Dönüş Değeri

yeni kesir
## Açıklamalar



Örnek: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) metodu


Creates a fraction with this numerator and specified denominator

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Payda |

### Dönüş Değeri

yeni kesir
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) metodu


Creates a fraction of the specified type with this numerator and specified denominator

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Payda |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Fraction type: Bar, NoBar, Skewed, Linear |

### Dönüş Değeri

yeni kesir
## Açıklamalar



Örnek: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) metodu


Creates a fraction of the specified type with this numerator and specified denominator

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Payda |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Fraction type: Bar, NoBar, Skewed, Linear |

### Dönüş Değeri

yeni kesir
## Açıklamalar



Örnek: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Bakınız

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathFraction](../../imathfraction/)
* Sınıf [IMathElement](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)