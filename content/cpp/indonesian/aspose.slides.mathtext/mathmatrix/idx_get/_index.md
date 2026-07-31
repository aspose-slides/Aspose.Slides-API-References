---
title: idx_get()
second_title: Referensi API Aspose.Slides for C++
description: Elemen matriks
type: docs
weight: 209
url: /id/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) metode

Elemen matriks

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| row | **int32_t** | Indeks berbasis nol dari baris untuk mendapatkan item |
| column | **int32_t** | Indeks berbasis nol dari kolom untuk mendapatkan item |

### Nilai Kembali


## Catatan



Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)