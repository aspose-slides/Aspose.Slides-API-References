---
title: get_Character()
second_title: Referensi API Aspose.Slides untuk C++
description: "Karakter Aksen Nilai harus berada dalam rentang (U+0300\\u2013U+036F) atau (U+20D0\\u2013U+20EF) Nilai default: Combining Circumflex Accent (U+0302)"
type: docs
weight: 14
url: /id/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() metode

Karakter Aksen Nilai harus berada dalam rentang (U+0300\\u2013U+036F) atau (U+20D0\\u2013U+20EF) Nilai default: Combining Circumflex Accent (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## Catatan

Contoh:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Lihat Juga

* Class [MathAccent](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)