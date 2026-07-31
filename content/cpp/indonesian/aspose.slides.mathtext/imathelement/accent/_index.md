---
title: Accent()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur tanda aksen (sebuah karakter di bagian atas elemen ini)
type: docs
weight: 209
url: /id/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) metode

Mengatur tanda aksen (sebuah karakter di bagian atas elemen ini)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| accentCharacter | char16_t | Karakter aksen. Nilainya harus berada dalam rentang (U+0300\\u2013U+036F) atau (U+20D0\\u2013U+20EF) |

### Nilai Kembalian

Instansi baru dari tipe [IMathAccent](../../imathaccent/)
## Catatan



Contoh: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathAccent](../../imathaccent/)
* Kelas [IMathElement](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)