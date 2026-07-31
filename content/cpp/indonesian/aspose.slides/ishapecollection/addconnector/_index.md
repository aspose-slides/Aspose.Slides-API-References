---
title: AddConnector()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat bentuk konektor baru dengan gaya templat default dan menambahkannya ke akhir koleksi bentuk.
type: docs
weight: 378
url: /id/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) metode

Membuat bentuk konektor baru dengan gaya templat default dan menambahkannya ke akhir koleksi bentuk.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) dari bentuk konektor yang akan ditambahkan. |
| x | **float** | Koordinat x dari bingkai konektor\\u2019s, dalam poin. |
| y | **float** | Koordinat y dari bingkai konektor\\u2019s, dalam poin. |
| width | **float** | Lebar bingkai konektor\\u2019s, dalam poin. |
| height | **float** | Tinggi bingkai konektor\\u2019s, dalam poin. |

### Nilai Kembalian

[IConnector](../../iconnector/) yang baru dibuat.

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) metode

Membuat bentuk konektor baru dan menambahkannya ke akhir koleksi bentuk, dengan opsional menerapkan gaya templat default.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) dari bentuk konektor yang akan dibuat. |
| x | **float** | Koordinat x dari bingkai konektor\\u2019s, dalam poin. |
| y | **float** | Koordinat y dari bingkai konektor\\u2019s, dalam poin. |
| width | **float** | Lebar bingkai konektor\\u2019s, dalam poin. |
| height | **float** | Tinggi bingkai konektor\\u2019s, dalam poin. |
| createFromTemplate | **bool** | true untuk menerapkan gaya templat default (nama tidak kosong, gaya sederhana); false untuk membuat konektor dengan nilai properti default. |

### Nilai Kembalian

[IConnector](../../iconnector/) yang baru dibuat.

## Lihat Juga

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IConnector](../../iconnector/)
* Kelas [IShapeCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)