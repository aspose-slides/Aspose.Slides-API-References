---
title: Delimit()
second_title: Aspose.Slides for C++ API Referansı
description: Alt öğeleri ayırıcı karakter ile sınırlar (köşeli parantezler olmadan)
type: docs
weight: 209
url: /tr/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) yöntemi

Ayrıcı karakter ile alt öğeleri sınırlıyor (köşeli parantezler olmadan)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| separatorCharacter | char16_t | Ayrıcı karakter |

### Dönüş Değeri

[IMathDelimiter](../../imathdelimiter/)

## Açıklamalar


Örnek:
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)