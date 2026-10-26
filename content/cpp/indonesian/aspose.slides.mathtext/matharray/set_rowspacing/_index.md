---
title: set_RowSpacing()
second_title: Referensi API Aspose.Slides untuk C++
description: "Jarak antar baris dalam sebuah array hanya digunakan ketika RowSpacingRule diatur ke 3. Tepatnya, dalam kasus tersebut satuan ukurannya adalah poin atau Multiple, dalam kasus tersebut satuan ukurannya adalah setengah baris. Default: 0"
type: docs
weight: 131
url: /id/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) metode

Jarak antar baris array hanya digunakan ketika RowSpacingRule diatur ke 3. Tepatnya, dalam kasus tersebut satuan ukurannya adalah poin atau Multiple, dalam kasus tersebut satuan ukurannya adalah setengah baris. Bawaan: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
```

## Keterangan

Contoh:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Lihat Juga

* Kelas [MathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)