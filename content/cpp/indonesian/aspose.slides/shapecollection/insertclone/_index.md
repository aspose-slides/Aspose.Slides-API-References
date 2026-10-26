---
title: InsertClone()
second_title: Aspose.Slides untuk Referensi API C++
description: Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.
type: docs
weight: 560
url: /id/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) metode

Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bentuk yang dikloning. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) yang akan dikloning. |
| x | **float** | Koordinat x dari bingkai bentuk yang dikloning, dalam poin. |
| y | **float** | Koordinat y dari bingkai bentuk yang dikloning, dalam poin. |
| width | **float** | Lebar bingkai bentuk yang dikloning, dalam poin. |
| height | **float** | Tinggi bingkai bentuk yang dikloning, dalam poin. |

### Nilai Kembalian

[IShape](../../ishape/) yang baru dibuat.

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) metode

Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Bentuk baru mempertahankan lebar dan tinggi *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bentuk yang dikloning. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) yang akan dikloning. |
| x | **float** | Koordinat x dari bingkai bentuk yang dikloning, dalam poin. |
| y | **float** | Koordinat y dari bingkai bentuk yang dikloning, dalam poin. |

### Nilai Kembalian

[IShape](../../ishape/) yang baru dibuat.

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) metode

Membuat salinan bentuk yang ditentukan dan menyisipkannya ke dalam koleksi bentuk pada indeks yang ditentukan. Bentuk yang dikloning mempertahankan posisi dan ukuran asli.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan bentuk yang dikloning. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) yang akan dikloning. |

### Nilai Kembalian

[IShape](../../ishape/) yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IShape](../../ishape/)
* Kelas [ShapeCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)