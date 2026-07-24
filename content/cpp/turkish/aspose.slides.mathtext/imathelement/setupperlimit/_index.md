---
title: SetUpperLimit()
second_title: Aspose.Slides for C++ API Referansı
description: Üst sınırı alır
type: docs
weight: 144
url: /tr/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) yöntemi

Üst sınırı alır

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
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
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) yöntemi

Üst sınırı alır

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
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
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathLimit](../../imathlimit/)
* Sınıf [IMathElement](../)
* Sınıf [String](../../../system/string/)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)