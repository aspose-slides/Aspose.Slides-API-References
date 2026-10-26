---
title: set_RowSpacing()
second_title: Referensi API Aspose.Slides untuk C++
description: "Jarak antara baris dalam sebuah array Hanya digunakan ketika RowSpacingRule diatur ke 3 Exactly, dalam kasus tersebut satuan ukurannya adalah poin atau Multiple, dalam kasus tersebut satuan ukurannya adalah setengah baris. Default: 0"
type: docs
weight: 131
url: /id/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) metode

Jarak antar baris dalam sebuah array Digunakan hanya ketika RowSpacingRule diatur ke 3 Tepatnya, jika diatur ke Exactly, satuan ukurannya adalah poin; jika diatur ke Multiple, satuan ukurannya adalah setengah baris. Default: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
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
* Namespace [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)