---
title: set_Character()
second_title: Aspose.Slides için C++ API Referansı
description: "Vurgu Karakteri Değer (U+0300\\u2013U+036F) veya(U+20D0\\u2013U+20EF) aralığında olmalıdır. Varsayılan değer: Birleştirilmiş Çatı Vurgu (U+0302)"
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) metodu


Vurgu Karakteri Değer (U+0300\\u2013U+036F) veya(U+20D0\\u2013U+20EF) aralığında olmalıdır. Varsayılan değer: Birleştirilmiş Çatı Vurgu (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## Açıklamalar


Örnek: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Diğer Bağlantılar

* Sınıf [IMathAccent](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)