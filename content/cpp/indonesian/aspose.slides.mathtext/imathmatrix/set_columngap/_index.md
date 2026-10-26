---
title: set_ColumnGap()
second_title: Referensi API Aspose.Slides untuk C++
description: "Nilai jarak horizontal antara kolom matriks; Jika ColumnGapRule diatur ke 3 (\"Exactly\"), maka satuan diinterpretasikan sebagai twips (1/20 poin) Jika ColumnGapRule diatur ke 4 (\"Multiple\"), maka satuan diinterpretasikan sebagai jumlah kenaikan 0.5 em. Dalam kasus lain diabaikan. Default: 0"
type: docs
weight: 144
url: /id/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) metode


Nilai dari jarak horizontal antar kolom matriks; Jika ColumnGapRule disetel ke 3 ("Exactly"), maka satuan diinterpretasikan sebagai twips (1/20 poin) Jika ColumnGapRule disetel ke 4 ("Multiple"), maka satuan diinterpretasikan sebagai jumlah kenaikan 0.5 em. Pada kasus lain diabaikan. Default: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
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
* RuangNama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)