---
title: Radical()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen dereceden verilen argümandan matematiksel kökü belirtir.
type: docs
weight: 118
url: /tr/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) metod


Belirtilen dereceden verilen argümandan matematiksel kökü belirtir.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Radical argümanı |

### Dönüş Değeri

Yeni [IMathRadical](../../imathradical/) tipinde bir örnek
## Açıklamalar



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) metod


Belirtilen dereceden verilen argümandan matematiksel kökü belirtir.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Radical argümanı |

### Dönüş Değeri

Yeni [IMathRadical](../../imathradical/) tipinde bir örnek
## Açıklamalar



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathRadical](../../imathradical/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathElementBase](../)
* Sınıf [String](../../../system/string/)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)