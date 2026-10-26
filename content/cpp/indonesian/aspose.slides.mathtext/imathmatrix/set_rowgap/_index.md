---
title: set_RowGap()
second_title: Referensi API Aspose.Slides untuk C++
description: "Nilai jarak vertikal antara baris-baris matriks; Jika RowGapRule disetel ke 3 (\"Exactly\"), maka satuannya ditafsirkan sebagai twips (1/20 poin) Jika RowGapRule disetel ke 4 (\"Multiple\"), maka satuannya ditafsirkan sebagai setengah baris. Default: 0"
type: docs
weight: 196
url: /id/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) metode


Nilai jarak vertikal antara baris-baris matriks; Jika RowGapRule disetel ke 3 ("Exactly"), maka satuannya ditafsirkan sebagai twips (1/20 bagian poin) Jika RowGapRule disetel ke 4 ("Multiple"), maka satuannya ditafsirkan sebagai setengah baris. Default: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
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
* Ruang nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)