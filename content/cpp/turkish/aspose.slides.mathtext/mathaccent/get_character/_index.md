---
title: get_Character()
second_title: Aspose.Slides için C++ API Referansı
description: "Vurgu Karakteri Değer (U+0300\\u2013U+036F) veya (U+20D0\\u2013U+20EF) aralığında olmalıdır. Varsayılan değer: Birleştirici Çatı Vurgu (U+0302)"
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() method


Vurgu Karakteri Değer (U+0300\u2013U+036F) veya (U+20D0\u2013U+20EF) aralığında olmalıdır. Varsayılan değer: Birleştirici Çatı Vurgu (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## Açıklamalar


Örnek: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Diğer Bilgiler

* Sınıf [MathAccent](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)