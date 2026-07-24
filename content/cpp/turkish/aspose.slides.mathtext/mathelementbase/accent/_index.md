---
title: Accent()
second_title: Aspose.Slides için C++ API Referansı
description: Bu öğenin üst kısmına bir aksan işareti (bir karakter) ayarlar
type: docs
weight: 196
url: /tr/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) metodu

Bu öğenin üst kısmına bir aksan işareti (bir karakter) ayarlar

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| accentCharacter | char16_t | Aksan karakteri. Değer (U+0300\\u2013U+036F) veya (U+20D0\\u2013U+20EF) aralığında olmalıdır. |

### Dönüş Değeri

Yeni [IMathAccent](../../imathaccent/) türünde bir örnek

## Açıklamalar

Örnek: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathAccent](../../imathaccent/)
* Sınıf [MathElementBase](../)
* AdAlanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)