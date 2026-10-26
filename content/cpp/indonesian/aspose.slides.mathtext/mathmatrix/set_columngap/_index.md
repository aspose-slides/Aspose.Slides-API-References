---
title: set_ColumnGap()
second_title: Referensi API Aspose.Slides untuk C++
description: "Nilai jarak horizontal antara kolom-kolom sebuah matriks; Jika ColumnGapRule diatur ke 3 (\"Exactly\"), maka satuannya diinterpretasikan sebagai twips (1/20 poin) Jika ColumnGapRule diatur ke 4 (\"Multiple\"), maka satuannya diinterpretasikan sebagai jumlah kenaikan 0.5 em. Pada kasus lain diabaikan. Default: 0"
type: docs
weight: 144
url: /id/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) metode

Nilai jarak horizontal antara kolom-kolom sebuah matriks; Jika ColumnGapRule diatur ke 3 ("Exactly"), maka satuannya diinterpretasikan sebagai twips (1/20 poin) Jika ColumnGapRule diatur ke 4 ("Multiple"), maka satuannya diinterpretasikan sebagai jumlah kenaikan 0.5 em. Pada kasus lain diabaikan. Default: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
```

## Catatan

Contoh:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Lihat Juga

* Kelas [MathMatrix](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)