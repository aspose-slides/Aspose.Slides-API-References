---
title: get_RowSpacing()
second_title: Referensi API Aspose.Slides untuk C++
description: "Jarak antara baris dalam sebuah array Hanya digunakan ketika RowSpacingRule diatur ke 3 Exactly dalam kasus ini satuan yang digunakan adalah poin atau Multiple dalam kasus ini satuan yang digunakan adalah setengah baris. Default: 0"
type: docs
weight: 118
url: /id/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() method


Jarak antara baris dalam sebuah array. Hanya digunakan ketika RowSpacingRule diatur ke 3 Exactly, dalam kasus ini satuan yang digunakan adalah poin, atau Multiple, dalam kasus ini satuan yang digunakan adalah setengah baris. Default: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## Catatan


Contoh: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Lihat Juga

* Kelas [MathArray](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)