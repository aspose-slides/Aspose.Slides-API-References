---
title: set_Character()
second_title: Referensi API Aspose.Slides untuk C++
description: "Karakter Aksen Nilai harus berada dalam rentang (U+0300\\u2013U+036F) atau(U+20D0\\u2013U+20EF) Nilai default: Aksen Sirkumfleks Kombinasi (U+0302)"
type: docs
weight: 27
url: /id/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) metode

Karakter Aksen Nilai harus berada dalam rentang (U+0300\\u2013U+036F) atau (U+20D0\\u2013U+20EF) Nilai default: Aksen Sirkumfleks Kombinasi (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
```

## Catatan

Contoh:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Lihat Juga

* Kelas [MathAccent](../)
* Namespace [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)