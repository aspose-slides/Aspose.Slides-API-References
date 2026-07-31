---
title: Reorder()
second_title: Referensi API Aspose.Slides untuk C++
description: Memindahkan shape yang ditentukan ke posisi baru dalam koleksi shape.
type: docs
weight: 339
url: /id/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) metode

Memindahkan shape yang ditentukan ke posisi baru dalam koleksi shape.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks target berbasis nol tempat shape akan ditempatkan. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [IShape](../../ishape/) untuk dipindahkan dalam koleksi. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) metode

Memindahkan shapes yang ditentukan dalam koleksi shape, menempatkannya mulai dari indeks yang diberikan.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks target berbasis nol tempat shape pertama yang ditentukan akan ditempatkan; shape berikutnya mengikuti urutan yang diberikan. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | Satu atau lebih instance [IShape](../../ishape/) untuk dipindahkan dalam koleksi. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [IShape](../../ishape/)
* Kelas [ShapeCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)