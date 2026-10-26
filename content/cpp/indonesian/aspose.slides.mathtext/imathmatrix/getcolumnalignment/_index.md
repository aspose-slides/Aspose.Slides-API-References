---
title: GetColumnAlignment()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan perataan horizontal kolom yang ditentukan
type: docs
weight: 235
url: /id/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) metode

Mendapatkan perataan horizontal kolom yang ditentukan

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | **int32_t** | Zero-based column index |

### Nilai Kembali

Perataan Horizontal kolom yang ditentukan

## Catatan



Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Lihat Juga

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Kelas [IMathMatrix](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)