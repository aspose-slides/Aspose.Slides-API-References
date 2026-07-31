---
title: InsertColumnAfter()
second_title: Referensi API Aspose.Slides untuk C++
description: Masukkan kolom baru setelah yang ditentukan. Awalnya semua elemen di kolom baru adalah null.
type: docs
weight: 326
url: /id/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) metode


Masukkan kolom baru setelah kolom yang ditentukan. Awalnya semua elemen di kolom baru adalah null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks kolom setelah mana kolom baru akan disisipkan |
## Catatan

Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Lihat Juga

* Kelas [IMathMatrix](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)