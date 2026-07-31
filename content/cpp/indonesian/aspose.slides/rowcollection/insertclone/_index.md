---
title: InsertClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat salinan baris templat yang ditentukan dan menyisipkannya pada posisi yang ditentukan dalam sebuah tabel.
type: docs
weight: 66
url: /id/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) metode

Membuat salinan baris templat yang ditentukan dan menyisipkannya pada posisi yang ditentukan dalam sebuah tabel.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Argumen

| Parameter | Type | Deskripsi |
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
* Kelas [RowCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)