---
title: get_RowGapRule()
second_title: Referensi API Aspose.Slides untuk C++
description: "Jenis jarak vertikal antara baris-baris dalam sebuah matriks; satuan jarak vertikal dapat berupa baris atau poin (disimpan sebagai twips). Default: SingleSpacingGap (0)"
type: docs
weight: 157
url: /id/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() metode

Jenis jarak vertikal antara baris-baris dalam sebuah matriks; satuan jarak vertikal dapat berupa baris atau poin (disimpan sebagai twips). Default: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## Catatan

Contoh:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Lihat Juga

* Enum [MathSpacingRules](../../mathspacingrules/)
* Kelas [IMathMatrix](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)