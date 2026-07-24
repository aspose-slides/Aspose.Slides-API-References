---
title: Divide()
second_title: Aspose.Slides for C++ API Referansı
description: Bu pay sayısı ve belirtilen payda ile bir kesir oluşturur
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) metot


Bu pay sayısı ve belirtilen payda ile bir kesir oluşturur

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Payda |

### Dönüş Değeri

yeni kesir
## Açıklamalar



Örnek: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) metot


Bu pay sayısı ve belirtilen payda ile bir kesir oluşturur

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Payda |

### Dönüş Değeri

yeni kesir
## Açıklamalar



Örnek: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) metot


Bu pay sayısı ve belirtilen payda ile belirtilen tipte bir kesir oluşturur

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Payda |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Kesir türü: Bar, NoBar, Skewed, Linear |

### Dönüş Değeri

yeni kesir
## Açıklamalar



Örnek: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) metot


Bu pay sayısı ve belirtilen payda ile belirtilen tipte bir kesir oluşturur

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Payda |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Kesir türü: Bar, NoBar, Skewed, Linear |

### Dönüş Değeri

yeni kesir
## Açıklamalar



Örnek: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## Ayrıca Bakınız

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)