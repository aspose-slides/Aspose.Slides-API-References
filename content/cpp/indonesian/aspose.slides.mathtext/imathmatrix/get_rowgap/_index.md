---
title: get_RowGap()
second_title: Referensi API Aspose.Slides untuk C++
description: "Nilai spasi vertikal antara baris-baris matriks; Jika RowGapRule diatur ke 3 (\"Exactly\"), maka satuan diinterpretasikan sebagai twip (1/20 poin) Jika RowGapRule diatur ke 4 (\"Multiple\"), maka satuan diinterpretasikan sebagai setengah baris. Bawaan: 0"
type: docs
weight: 183
url: /id/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() metode

Nilai spasi vertikal antara baris-baris matriks; Jika RowGapRule diatur ke 3 (\"Exactly\"), maka satuan diinterpretasikan sebagai twip (1/20 poin) Jika RowGapRule diatur ke 4 (\"Multiple\"), maka satuan diinterpretasikan sebagai setengah baris. Bawaan: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
```

## Catatan

Contoh:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Lihat Juga

* Kelas [IMathMatrix](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)