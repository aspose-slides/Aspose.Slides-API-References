---
title: InsertAutoShape()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat auto shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, dengan menerapkan format templat default.
type: docs
weight: 378
url: /id/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) metode

Membuat auto shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, dengan menerapkan format templat default.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan auto shape baru. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) dari auto shape yang akan disisipkan. |
| x | **float** | Koordinat x dari bingkai shape, dalam poin. |
| y | **float** | Koordinat y dari bingkai shape, dalam poin. |
| width | **float** | Lebar bingkai shape, dalam poin. |
| height | **float** | Tinggi bingkai shape, dalam poin. |

### Nilai Kembali

[IAutoShape](../../iautoshape/) yang baru dibuat.

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) metode

Membuat auto shape baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan, dengan opsi menginisialisasinya menggunakan gaya templat default.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan auto shape. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) dari auto shape yang akan disisipkan. |
| x | **float** | Koordinat x dari bingkai shape, dalam poin. |
| y | **float** | Koordinat y dari bingkai shape, dalam poin. |
| width | **float** | Lebar bingkai shape, dalam poin. |
| height | **float** | Tinggi bingkai shape, dalam poin. |
| createFromTemplate | **bool** | True untuk menerapkan gaya templat default (termasuk nama tidak kosong, gaya sederhana, dan teks berpusat); false untuk membuat shape dengan semua properti diatur ke nilai default. |

### Nilai Kembali

[IAutoShape](../../iautoshape/) yang baru dibuat.

## Lihat Juga

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAutoShape](../../iautoshape/)
* Kelas [ShapeCollection](../)
* Ruang nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)