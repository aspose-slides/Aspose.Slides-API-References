---
title: idx_get()
second_title: Referensi API Aspose.Slides untuk C++
description: Elemen matriks
type: docs
weight: 209
url: /id/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) method


Elemen matriks

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| row | **int32_t** | Indeks berbasis nol dari baris untuk mengambil item |
| column | **int32_t** | Indeks berbasis nol dari kolom untuk mengambil item |

### Nilai Kembalian


## Catatan



Contoh: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathElement](../../imathelement/)
* Kelas [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)