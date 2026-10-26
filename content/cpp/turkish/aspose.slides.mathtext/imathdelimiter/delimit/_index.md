---
title: Delimit()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen ayırıcı karakteri kullanarak bağımsız değişkenleri sınırlar
type: docs
weight: 144
url: /tr/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) yöntemi


Belirtilen ayırıcı karakteri kullanarak bağımsız değişkenleri sınırlar

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char16_t | ayırıcı karakter |

### Dönüş Değeri

Bu nesne, ayırıcı karakter uygulandıktan sonra
## Açıklamalar



Örnek: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathDelimiter](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)