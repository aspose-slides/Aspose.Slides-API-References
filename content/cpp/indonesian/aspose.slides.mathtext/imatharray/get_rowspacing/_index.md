---
title: get_RowSpacing()
second_title: Referensi API Aspose.Slides untuk C++
description: "Jarak antar baris dalam array. Hanya digunakan ketika RowSpacingRule diatur ke 3, tepatnya dalam kasus ini satuan ukurannya adalah poin atau Multiple dimana satuan ukurannya adalah setengah baris. Bawaan: 0"
type: docs
weight: 118
url: /id/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() metode

Jarak antar baris dalam array Hanya digunakan ketika RowSpacingRule disetel ke 3 Tepatnya dalam kasus ini satuan ukurannya adalah poin atau Multiple dimana satuan ukurannya adalah setengah baris. Bawaan: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
```

## Catatan

Contoh:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Lihat Juga

* Kelas [IMathArray](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)