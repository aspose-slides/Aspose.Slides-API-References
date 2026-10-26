---
title: InsertConnector()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat bentuk penghubung baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, dengan menerapkan gaya templat default.
type: docs
weight: 430
url: /id/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) metode

Membuat bentuk penghubung baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, menerapkan gaya templat default.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
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

### Nilai Kembalian

[IConnector](../../iconnector/) yang baru dibuat.

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) metode

Membuat bentuk penghubung baru dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan, dengan opsi menerapkan gaya templat default.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
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

### Nilai Kembalian

[IConnector](../../iconnector/) yang baru dibuat.

## Lihat Juga

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)