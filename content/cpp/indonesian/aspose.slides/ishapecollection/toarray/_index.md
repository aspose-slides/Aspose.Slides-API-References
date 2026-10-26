---
title: ToArray()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat dan mengembalikan sebuah array yang berisi semua shape.
type: docs
weight: 287
url: /id/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() metode

Membuat dan mengembalikan sebuah array yang berisi semua shapes.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```


### Nilai Kembalian

Sebuah array dari objek [IShape](../../ishape/).

## IShapeCollection::ToArray(int32_t, int32_t) metode


Membuat dan mengembalikan sebuah array yang berisi semua shapes dalam rentang yang ditentukan.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | **int32_t** | Indeks shape pertama yang akan dikembalikan. |
| count | **int32_t** | Jumlah shapes yang akan dikembalikan. |

### Nilai Kembalian

Sebuah array dari objek [IShape](../../ishape/).

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)