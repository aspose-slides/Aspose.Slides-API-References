---
title: set_RowGap()
second_title: Referensi API Aspose.Slides untuk C++
description: "Nilai jarak vertikal antara baris pada matriks; Jika RowGapRule diatur ke 3 (\"Exactly\"), maka satuannya diartikan sebagai twips (1/20 poin) Jika RowGapRule diatur ke 4 (\"Multiple\"), maka satuannya diartikan sebagai setengah baris. Default: 0"
type: docs
weight: 196
url: /id/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) metode

Nilai jarak vertikal antara baris pada matriks; Jika RowGapRule diatur ke 3 (\"Exactly\"), maka satuannya diartikan sebagai twips (1/20 poin) Jika RowGapRule diatur ke 4 (\"Multiple\"), maka satuannya diartikan sebagai setengah baris. Default: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
```

## Catatan


Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Lihat Juga

* Kelas [MathMatrix](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)