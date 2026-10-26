---
title: get_ColumnGapRule()
second_title: Referensi API Aspose.Slides untuk C++
description: "Jenis spasi horizontal antara kolom sebuah matriks; satuan spasi horizontal dapat berupa ems atau points (disimpan sebagai twips). Default: SingleSpacingGap (0)"
type: docs
weight: 105
url: /id/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() metode


Jenis spasi horizontal antara kolom sebuah matriks; satuan spasi horizontal dapat berupa ems atau points (disimpan sebagai twips). Default: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## Catatan


Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Lihat Juga

* Enum [MathSpacingRules](../../mathspacingrules/)
* Kelas [IMathMatrix](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)