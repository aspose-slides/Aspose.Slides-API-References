---
title: InsertAutoShape()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah bentuk otomatis baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, dengan menerapkan pemformatan templat default.
type: docs
weight: 339
url: /id/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) metode

Membuat sebuah bentuk otomatis baru dan menyisipkannya ke dalam kumpulan bentuk pada indeks yang ditentukan, dengan menerapkan pemformatan templat default.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bentuk otomatis baru. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) dari bentuk otomatis yang akan disisipkan. |
| x | **float** | Koordinat x bingkai bentuk, dalam poin. |
| y | **float** | Koordinat y bingkai bentuk, dalam poin. |
| width | **float** | Lebar bingkai bentuk, dalam poin. |
| height | **float** | Tinggi bingkai bentuk, dalam poin. |

### Nilai Kembalian

[IAutoShape](../../iautoshape/) yang baru dibuat.

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) metode

Membuat sebuah bentuk otomatis baru dan menyisipkannya ke dalam kumpulan bentuk pada indeks yang ditentukan, secara opsional menginisialisasinya dengan gaya templat default.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bentuk otomatis. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) dari bentuk otomatis yang akan disisipkan. |
| x | **float** | Koordinat x bingkai bentuk, dalam poin. |
| y | **float** | Koordinat y bingkai bentuk, dalam poin. |
| width | **float** | Lebar bingkai bentuk, dalam poin. |
| height | **float** | Tinggi bingkai bentuk, dalam poin. |
| createFromTemplate | **bool** | True untuk menerapkan gaya templat default (termasuk nama yang tidak kosong, gaya sederhana, dan teks terpusat); false untuk membuat bentuk dengan semua properti diatur ke nilai defaultnya. |

### Nilai Kembalian

[IAutoShape](../../iautoshape/) yang baru dibuat.

## Lihat Juga

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAutoShape](../../iautoshape/)
* Kelas [IShapeCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)