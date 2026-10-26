---
title: AddAutoShape()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat auto shape baru dengan format default dan menambahkannya ke akhir koleksi shape.
type: docs
weight: 352
url: /id/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) metode

Membuat auto shape baru dengan format default dan menambahkannya ke akhir koleksi shape.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) dari auto shape yang akan ditambahkan. |
| x | **float** | Koordinat x bingkai shape, dalam poin. |
| y | **float** | Koordinat y bingkai shape, dalam poin. |
| width | **float** | Lebar bingkai shape, dalam poin. |
| height | **float** | Tinggi bingkai shape, dalam poin. |

### Nilai Kembali

[IAutoShape](../../iautoshape/) yang baru dibuat.

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) metode

Membuat auto shape baru dan menambahkannya ke akhir koleksi shape, dengan opsional menginisialisasinya menggunakan format templat default.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) dari auto shape yang akan ditambahkan. |
| x | **float** | Koordinat x bingkai shape, dalam poin. |
| y | **float** | Koordinat y bingkai shape, dalam poin. |
| width | **float** | Lebar bingkai shape, dalam poin. |
| height | **float** | Tinggi bingkai shape, dalam poin. |
| createFromTemplate | **bool** | True untuk menerapkan gaya templat default (gaya sederhana, teks terpusat, dan nama tidak kosong) pada shape baru; false untuk membuat shape dengan semua properti disetel ke nilai default mereka. |

### Nilai Kembali

[IAutoShape](../../iautoshape/) yang baru dibuat.

## Lihat Juga

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)