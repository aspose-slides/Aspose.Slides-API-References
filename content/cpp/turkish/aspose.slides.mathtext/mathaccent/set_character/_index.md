---
title: set_Character()
second_title: Aspose.Slides için C++ API Referansı
description: "Aksan Karakteri Değer (U+0300\\u2013U+036F) veya(U+20D0\\u2013U+20EF) aralığında olmalıdır. Varsayılan değer: Birleştirici Çatı Aksanı (U+0302)"
type: docs
weight: 27
url: /tr/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) yöntemi


Aksan Karakteri Değer (U+0300\\u2013U+036F) veya(U+20D0\\u2013U+20EF) aralığında olmalıdır. Varsayılan değer: Birleştirici Çatı Aksanı (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
```

## Açıklamalar


Örnek: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Ayrıca Bakınız

* Sınıf [MathAccent](../)
* İsim uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)