---
title: InsertClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat salinan baris templat yang ditentukan dan menyisipkannya pada posisi yang ditentukan dalam sebuah tabel.
type: docs
weight: 27
url: /id/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) metode

Membuat salinan baris templat yang ditentukan dan menyisipkannya pada posisi yang ditentukan dalam sebuah tabel.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks baris baru. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) yang digunakan sebagai templat. |
| withAttachedRows | **bool** | True untuk menyalin juga semua baris yang terlampir pada baris templat. |

### Nilai Kembali

Baris yang disisipkan.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IRow](../../irow/)
* Kelas [IRowCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)