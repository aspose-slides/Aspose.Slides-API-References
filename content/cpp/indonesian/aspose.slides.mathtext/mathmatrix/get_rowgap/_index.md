---
title: get_RowGap()
second_title: Aspose.Slides untuk Referensi API C++
description: "Nilai jarak vertikal antara baris-baris matriks; Jika RowGapRule diatur ke 3 (\"Exactly\"), maka satuannya diinterpretasikan sebagai twips (1/20 poin) Jika RowGapRule diatur ke 4 (\"Multiple\"), maka satuannya diinterpretasikan sebagai setengah baris. Default: 0"
type: docs
weight: 183
url: /id/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() method


Nilai jarak vertikal antara baris-baris matriks; Jika RowGapRule diatur ke 3 ("Exactly"), maka satuannya diinterpretasikan sebagai twips (1/20 poin) Jika RowGapRule diatur ke 4 ("Multiple"), maka satuannya diinterpretasikan sebagai setengah baris. Default: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
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
* Ruang nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)