---
title: Radical()
second_title: Aspose.Slides için C++ API Referansı
description: Belirli argümandan verilen dereceden matematiksel kökü belirler.
type: docs
weight: 131
url: /tr/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) metot


Verilen dereceden belirtilen argümandan matematiksel kökü belirler.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argument of Radical |

### Dönüş Değeri

Yeni [IMathRadical](../../imathradical/) türünün örneği
## Açıklamalar



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) metot


Verilen dereceden belirtilen argümandan matematiksel kökü belirler.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argument of Radical |

### Dönüş Değeri

Yeni [IMathRadical](../../imathradical/) türünün örneği
## Açıklamalar



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathRadical](../../imathradical/)
* Sınıf [IMathElement](../)
* Sınıf [String](../../../system/string/)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)