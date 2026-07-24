---
title: SetLowerLimit()
second_title: Aspose.Slides for C++ API Referansı
description: Alt sınırı alır
type: docs
weight: 157
url: /tr/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) metod


Alt sınırı alır

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### Dönüş Değeri

Yeni [IMathLimit](../../imathlimit/) örneği
## Açıklamalar



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) metod


Alt sınırı alır

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Dönüş Değeri

Yeni [IMathLimit](../../imathlimit/) örneği
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathLimit](../../imathlimit/)
* Sınıf [IMathElement](../)
* Sınıf [String](../../../system/string/)
* İsim Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)