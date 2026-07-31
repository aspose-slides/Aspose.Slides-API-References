---
title: InsertClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.
type: docs
weight: 508
url: /id/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) method

Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bentuk yang dikloning. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) yang akan dikloning. |
| x | **float** | Koordinat x bingkai bentuk yang dikloning\\u2019s, dalam poin. |
| y | **float** | Koordinat y bingkai bentuk yang dikloning\\u2019s, dalam poin. |
| width | **float** | Lebar bingkai bentuk yang dikloning\\u2019s, dalam poin. |
| height | **float** | Tinggi bingkai bentuk yang dikloning\\u2019s, dalam poin. |

### Nilai Kembali

[IShape](../../ishape/) yang baru dibuat.

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) method

Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Bentuk baru mempertahankan lebar dan tinggi *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bentuk yang dikloning. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) yang akan dikloning. |
| x | **float** | Koordinat x bingkai bentuk yang dikloning\\u2019s, dalam poin. |
| y | **float** | Koordinat y bingkai bentuk yang dikloning\\u2019s, dalam poin. |

### Nilai Kembali

[IShape](../../ishape/) yang baru dibuat.

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) method

Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Bentuk yang dikloning mempertahankan posisi dan ukuran asli\\u2019s.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bentuk yang dikloning. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) yang akan dikloning. |

### Nilai Kembali

[IShape](../../ishape/) yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IShape](../../ishape/)
* Kelas [IShapeCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)