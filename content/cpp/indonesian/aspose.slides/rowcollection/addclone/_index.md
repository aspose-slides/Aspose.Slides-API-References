---
title: AddClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat salinan baris templat yang ditentukan dan menyisipkannya di bagian bawah tabel.
type: docs
weight: 53
url: /id/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) metode

Membuat salinan baris templat yang ditentukan dan menyisipkannya di bagian bawah tabel.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) yang digunakan sebagai templat. |
| withAttachedRows | **bool** | True untuk menyalin juga semua baris yang terlampir pada baris templat. |

### Nilai Kembalian

Baris yang ditambahkan.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IRow](../../irow/)
* Kelas [RowCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)