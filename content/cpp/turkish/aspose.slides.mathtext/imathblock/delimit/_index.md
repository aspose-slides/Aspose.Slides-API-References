---
title: Delimit()
second_title: Aspose.Slides for C++ API Referansı
description: Tüm alt öğeleri ayırıcı karakterle (köşeli parantezler olmadan) sınırlar
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) yöntemi

Tüm alt elemanları ayırıcı karakterle (köşeli parantezler olmadan) sınırlar

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separatorCharacter | char16_t | Ayırıcı olarak kullanılan karakter |

### Dönüş Değeri

[IMathDelimiter](../../imathdelimiter/) öğesinin örneği
## Notlar



Örnek: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathDelimiter](../../imathdelimiter/)
* Sınıf [IMathBlock](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)