---
title: InsertConnector()
second_title: Aspose.Slides untuk Referensi API C++
description: Membuat bentuk penghubung baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, dengan menerapkan gaya templat default.
type: docs
weight: 391
url: /id/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) method

Membuat bentuk penghubung baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, dengan menerapkan gaya templat default.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bentuk penghubung. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) dari bentuk penghubung yang akan disisipkan. |
| x | **float** | Koordinat x dari bingkai penghubung, dalam poin. |
| y | **float** | Koordinat y dari bingkai penghubung, dalam poin. |
| width | **float** | Lebar bingkai penghubung, dalam poin. |
| height | **float** | Tinggi bingkai penghubung, dalam poin. |

### Nilai Kembali

[IConnector](../../iconnector/) yang baru dibuat.

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) method

Membuat bentuk penghubung baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, dengan opsional menerapkan gaya templat default.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bentuk penghubung. |
| shapeType | [ShapeType](../../shapetype/) | [ShapeType](../../shapetype/) dari bentuk penghubung yang akan disisipkan. |
| x | **float** | Koordinat x dari bingkai penghubung, dalam poin. |
| y | **float** | Koordinat y dari bingkai penghubung, dalam poin. |
| width | **float** | Lebar bingkai penghubung, dalam poin. |
| height | **float** | Tinggi bingkai penghubung, dalam poin. |
| createFromTemplate | **bool** | True untuk menerapkan gaya templat default (nama tidak kosong, gaya sederhana); false untuk membuat penghubung dengan nilai properti default. |

### Nilai Kembali

[IConnector](../../iconnector/) yang baru dibuat.

## Lihat Juga

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)