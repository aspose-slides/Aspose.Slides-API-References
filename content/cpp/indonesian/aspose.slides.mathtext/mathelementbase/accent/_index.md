---
title: Accent()
second_title: Referensi API Aspose.Slides untuk C++
description: Menetapkan tanda aksen (karakter di atas elemen ini)
type: docs
weight: 196
url: /id/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) metode

Menetapkan tanda aksen (karakter di atas elemen ini)

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| accentCharacter | char16_t | Karakter aksen. Nilainya harus berada dalam rentang (U+0300\\u2013U+036F) atau (U+20D0\\u2013U+20EF) |

### Nilai Kembali

Instansi baru dari tipe [IMathAccent](../../imathaccent/)
## Keterangan



Contoh: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathAccent](../../imathaccent/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)