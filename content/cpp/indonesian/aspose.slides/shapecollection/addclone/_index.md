---
title: AddClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat salinan dari shape yang ditentukan dan menambahkannya ke akhir koleksi shape.
type: docs
weight: 547
url: /id/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) metode


Membuat salinan dari shape yang ditentukan dan menambahkannya ke akhir koleksi shape.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Shape yang akan diklon. |
| x | **float** | Koordinat x dari bingkai shape baru\\u2019s, dalam poin. |
| y | **float** | Koordinat y dari bingkai shape baru\\u2019s, dalam poin. |
| width | **float** | Lebar bingkai shape baru\\u2019s, dalam poin. |
| height | **float** | Tinggi bingkai shape baru\\u2019s, dalam poin. |

### Nilai Kembalian

[IShape](../../ishape/) yang baru dibuat.

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) metode


Membuat salinan dari shape yang ditentukan dan menambahkannya ke akhir koleksi shape. Shape baru mempertahankan lebar dan tinggi *sourceShape*.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Shape yang akan diklon. |
| x | **float** | Koordinat x dari bingkai shape baru\\u2019s, dalam poin. |
| y | **float** | Koordinat y dari bingkai shape baru\\u2019s, dalam poin. |

### Nilai Kembalian

[IShape](../../ishape/) yang baru dibuat.

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) metode


Membuat salinan dari shape yang ditentukan dan menambahkannya ke akhir koleksi shape. Shape yang diklon mempertahankan posisi dan ukuran aslinya.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) yang akan diklon. |

### Nilai Kembalian

[IShape](../../ishape/) yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IShape](../../ishape/)
* Kelas [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)