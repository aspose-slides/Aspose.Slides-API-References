---
title: get_Character()
second_title: Referensi API Aspose.Slides untuk C++
description: "Karakter Aksen Nilai harus berada dalam kisaran (U+0300\\u2013U+036F) atau(U+20D0\\u2013U+20EF) Nilai default: Aksen Kombinasi Sirkumfleks (U+0302)"
type: docs
weight: 14
url: /id/aspose.slides.mathtext/imathaccent/get_character/
---
## IMathAccent::get_Character() metode

Karakter Aksen Nilai harus berada dalam kisaran (U+0300\\u2013U+036F) atau(U+20D0\\u2013U+20EF) Nilai default: Aksen Kombinasi Sirkumfleks (U+0302)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathAccent::get_Character()=0
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