---
title: ToArray()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat dan mengembalikan array yang berisi semua bentuk.
type: docs
weight: 326
url: /id/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() metode

Membuat dan mengembalikan array yang berisi semua bentuk.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```

### Nilai Kembali

Array berisi objek [IShape](../../ishape/).

## ShapeCollection::ToArray(int32_t, int32_t) metode

Membuat dan mengembalikan array yang berisi semua bentuk dalam rentang yang ditentukan.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | **int32_t** | Indeks bentuk pertama yang akan dikembalikan. |
| count | **int32_t** | Jumlah bentuk yang akan dikembalikan. |

### Nilai Kembali

Array berisi objek [IShape](../../ishape/).

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IShape](../../ishape/)
* Kelas [ShapeCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)