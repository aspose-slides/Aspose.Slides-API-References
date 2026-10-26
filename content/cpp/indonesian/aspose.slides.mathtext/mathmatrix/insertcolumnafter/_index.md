---
title: InsertColumnAfter()
second_title: Aspose.Slides untuk C++ Referensi API
description: Masukkan kolom baru setelah kolom yang ditentukan. Awalnya semua elemen pada kolom baru bernilai null.
type: docs
weight: 339
url: /id/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) metode


Masukkan kolom baru setelah kolom yang ditentukan. Awalnya semua elemen pada kolom baru bernilai null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks kolom setelahnya kolom baru akan disisipkan |
## Catatan



Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Lihat Juga

* Kelas [MathMatrix](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)