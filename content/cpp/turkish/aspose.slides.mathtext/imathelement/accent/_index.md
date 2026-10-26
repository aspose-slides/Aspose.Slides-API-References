---
title: Accent()
second_title: Aspose.Slides için C++ API Referansı
description: Bu öğenin üst kısmına bir aksan işareti (bir karakter) ayarlar
type: docs
weight: 209
url: /tr/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) yöntemi

Bu öğenin üst kısmına bir aksan işareti (bir karakter) ayarlar

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| accentCharacter | char16_t | Accent karakteri. Değer (U+0300\\u2013U+036F) veya (U+20D0\\u2013U+20EF) aralığında olmalıdır. |

### Dönüş Değeri

Yeni [IMathAccent](../../imathaccent/) türünden örnek
## Açıklamalar



Örnek: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathAccent](../../imathaccent/)
* Sınıf [IMathElement](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)