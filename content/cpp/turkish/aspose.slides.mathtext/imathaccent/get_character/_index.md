---
title: get_Character()
second_title: Aspose.Slides for C++ API Referansı
description: "Aksan Karakteri Değer (U+0300\\u2013U+036F) veya (U+20D0\\u2013U+20EF) aralığında olmalıdır Varsayılan değer: Birleştirici Çatı Aksanı (U+0302)"
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/imathaccent/get_character/
---
## IMathAccent::get_Character() metodu


Aksan Karakteri Değer (U+0300\\u2013U+036F) veya(U+20D0\\u2013U+20EF) aralığında olmalıdır Varsayılan değer: Birleştirici Çatı Aksanı (U+0302)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathAccent::get_Character()=0
```

## Açıklamalar


Örnek: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Ayrıca Bakınız

* Sınıf [IMathAccent](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)