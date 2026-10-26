---
title: InsertRowAfter()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyisipkan baris baru setelah yang ditentukan. Secara awal semua elemen di baris baru adalah null.
type: docs
weight: 300
url: /id/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) metode


Menyisipkan baris baru setelah yang ditentukan. Secara awal semua elemen di baris baru adalah null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rowIndex | **int32_t** | Indeks baris setelah mana menyisipkan baris baru |
## Catatan



Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Lihat Juga

* Kelas [MathMatrix](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Pustaka [Aspose.Slides](../../../)