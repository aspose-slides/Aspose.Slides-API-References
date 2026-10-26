---
title: GetColumnAlignment()
second_title: Referensi API Aspose.Slides untuk C++
description: Dapatkan perataan horizontal kolom yang ditentukan
type: docs
weight: 248
url: /id/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) metode


Dapatkan perataan horizontal kolom yang ditentukan

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks kolom berbasis nol |

### Nilai Kembalian

Perataan horizontal kolom yang ditentukan
## Catatan



Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Lihat Juga

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Kelas [MathMatrix](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)