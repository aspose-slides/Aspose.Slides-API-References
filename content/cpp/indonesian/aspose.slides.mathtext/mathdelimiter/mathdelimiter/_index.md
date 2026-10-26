---
title: MathDelimiter()
second_title: Aspose.Slides untuk C++ Referensi API
description: Menginisialisasi MathDelimiter dengan elemen yang ditentukan sebagai argumen basis tunggal
type: docs
weight: 144
url: /id/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) konstruktor

Menginisialisasi [MathDelimiter](../) dengan elemen yang ditentukan sebagai argumen basis tunggal

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemen dasar tempat delimiter diterapkan. Dapat bernilai null. |

## Catatan

Contoh:
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)