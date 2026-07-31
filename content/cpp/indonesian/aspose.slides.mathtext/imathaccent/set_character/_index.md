---
title: set_Character()
second_title: Referensi API Aspose.Slides untuk C++
description: "Karakter Aksen Nilai harus berada dalam rentang (U+0300\\u2013U+036F) atau(U+20D0\\u2013U+20EF) Nilai default: Kombinasi Aksen Sirkumfleks (U+0302)"
type: docs
weight: 27
url: /id/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) metode

Karakter Aksen Nilai harus berada dalam rentang (U+0300\\u2013U+036F) atau (U+20D0\\u2013U+20EF) Nilai default: Kombinasi Aksen Sirkumfleks (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## Catatan

Contoh: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Lihat Juga

* Kelas [IMathAccent](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)