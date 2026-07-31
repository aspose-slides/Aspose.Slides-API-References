---
title: get_ColumnGap()
second_title: Referensi API Aspose.Slides untuk C++
description: "Nilai jarak horizontal antara kolom dalam matriks; Jika ColumnGapRule diatur ke 3 (\"Exactly\"), maka satuan diinterpretasikan sebagai twip (1/20 poin) Jika ColumnGapRule diatur ke 4 (\"Multiple\"), maka satuan diinterpretasikan sebagai jumlah kenaikan 0,5 em. Dalam kasus lain diabaikan. Default: 0"
type: docs
weight: 131
url: /id/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() method

Nilai jarak horizontal antar kolom dalam matriks; Jika ColumnGapRule disetel ke 3 ("Exactly"), maka satuan diinterpretasikan sebagai twip (1/20 poin) Jika ColumnGapRule disetel ke 4 ("Multiple"), maka satuan diinterpretasikan sebagai jumlah kenaikan 0,5 em. Pada kasus lain diabaikan. Default: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
```

## Catatan


Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Lihat Juga

* Kelas [IMathMatrix](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)