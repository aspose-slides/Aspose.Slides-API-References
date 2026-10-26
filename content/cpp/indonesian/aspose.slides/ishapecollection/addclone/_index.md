---
title: AddClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk.
type: docs
weight: 495
url: /id/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) metode

Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Bentuk yang akan digandakan. |
| x | **float** | Koordinat x bingkai bentuk yang digandakan, dalam poin. |
| y | **float** | Koordinat y bingkai bentuk yang digandakan, dalam poin. |
| width | **float** | Lebar bingkai bentuk yang digandakan, dalam poin. |
| height | **float** | Tinggi bingkai bentuk yang digandakan, dalam poin. |

### Nilai Kembalian

[IShape](../../ishape/) yang baru dibuat.

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) metode

Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk. Bentuk baru mempertahankan lebar dan tinggi *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) yang akan digandakan. |
| x | **float** | Koordinat x bingkai bentuk yang digandakan, dalam poin. |
| y | **float** | Koordinat y bingkai bentuk yang digandakan, dalam poin. |

### Nilai Kembalian

[IShape](../../ishape/) yang baru dibuat.

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) metode

Membuat salinan bentuk yang ditentukan dan menambahkannya ke akhir koleksi bentuk. Bentuk yang digandakan mempertahankan posisi dan ukuran asli\\u2019s.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) yang akan digandakan. |

### Nilai Kembalian

[IShape](../../ishape/) yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IShape](../../ishape/)
* Kelas [IShapeCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)