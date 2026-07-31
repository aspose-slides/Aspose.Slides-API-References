---
title: get_ColumnGap()
second_title: Referensi API Aspose.Slides untuk C++
description: "Nilai jarak horizontal antara kolom-kolom matriks; Jika ColumnGapRule diatur ke 3 (\"Exactly\"), maka satuan diinterpretasikan sebagai twips (1/20 poin) Jika ColumnGapRule diatur ke 4 (\"Multiple\"), maka satuan diinterpretasikan sebagai jumlah kenaikan 0.5 em. Pada kasus lain diabaikan. Default: 0"
type: docs
weight: 131
url: /id/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() metode


Nilai jarak horizontal antara kolom-kolom matriks; Jika ColumnGapRule diatur ke 3 ("Exactly"), maka satuan diinterpretasikan sebagai twips (1/20 poin) Jika ColumnGapRule diatur ke 4 ("Multiple"), maka satuan diinterpretasikan sebagai jumlah kenaikan 0,5 em. Pada kasus lain diabaikan. Default: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
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
* Namespace [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)