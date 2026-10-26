---
title: InsertColumnBefore()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyisipkan kolom baru sebelum yang ditentukan. Awalnya semua elemen di kolom baru adalah null.
type: docs
weight: 326
url: /id/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) metode

Menyisipkan kolom baru sebelum kolom yang ditentukan. Awalnya semua elemen di kolom baru adalah null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks kolom sebelum mana kolom baru disisipkan |
## Catatan



Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Lihat Juga

* Kelas [MathMatrix](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)