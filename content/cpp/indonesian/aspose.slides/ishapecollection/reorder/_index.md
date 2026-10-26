---
title: Reorder()
second_title: Referensi API Aspose.Slides untuk C++
description: Memindahkan shape yang ditentukan ke posisi baru dalam koleksi shape.
type: docs
weight: 300
url: /id/aspose.slides/ishapecollection/reorder/
---
## IShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) metode


Memindahkan shape yang ditentukan ke posisi baru dalam koleksi shape.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks target berbasis nol tempat shape akan ditempatkan. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) untuk dipindahkan dalam koleksi. |

## IShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) metode


Memindahkan shape yang ditentukan dalam koleksi shape, menempatkannya mulai dari indeks yang diberikan.

```cpp
virtual void Aspose::Slides::IShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks target berbasis nol tempat shape pertama yang ditentukan akan ditempatkan; shape berikutnya mengikuti urutan yang diberikan. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Satu atau lebih instansi [IShape](../../ishape/) untuk dipindahkan dalam koleksi. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)