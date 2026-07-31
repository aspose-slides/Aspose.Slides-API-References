---
title: InsertColumnBefore()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyisipkan kolom baru sebelum yang ditentukan. Awalnya semua elemen di kolom baru adalah null.
type: docs
weight: 313
url: /id/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) metode

Menyisipkan kolom baru sebelum kolom yang ditentukan. Awalnya semua elemen di kolom baru adalah null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | **int32_t** | Indeks kolom sebelum mana menyisipkan kolom baru |
## Catatan



Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Lihat Juga

* Kelas [IMathMatrix](../)
* Ruang Nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)