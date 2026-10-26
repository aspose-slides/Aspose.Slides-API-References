---
title: AddAutoShape()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat auto shape baru dengan format default dan menambahkannya ke akhir koleksi shape.
type: docs
weight: 313
url: /id/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) metode

Membuat auto shape baru dengan format default dan menambahkannya ke akhir koleksi shape.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) auto shape yang akan ditambahkan. |
| x | **float** | Koordinat x dari bingkai shape, dalam poin. |
| y | **float** | Koordinat y dari bingkai shape, dalam poin. |
| width | **float** | Lebar bingkai shape, dalam poin. |
| height | **float** | Tinggi bingkai shape, dalam poin. |

### Nilai Kembalian

[IAutoShape](../../iautoshape/) yang baru dibuat.

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) metode

Membuat auto shape baru dan menambahkannya ke akhir koleksi shape, secara opsional menginisialisasinya dengan format template default.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) auto shape yang akan ditambahkan. |
| x | **float** | Koordinat x dari bingkai shape, dalam poin. |
| y | **float** | Koordinat y dari bingkai shape, dalam poin. |
| width | **float** | Lebar bingkai shape, dalam poin. |
| height | **float** | Tinggi bingkai shape, dalam poin. |
| createFromTemplate | **bool** | true untuk menerapkan gaya template default (gaya sederhana, teks terpusat, dan nama tidak kosong) pada shape baru; false untuk membuat shape dengan semua properti diset ke nilai defaultnya. |

### Nilai Kembalian

[IAutoShape](../../iautoshape/) yang baru dibuat.

## Lihat Juga

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAutoShape](../../iautoshape/)
* Kelas [IShapeCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)