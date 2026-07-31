---
title: AddClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat salinan baris templat yang ditentukan dan menyisipkannya di bagian bawah tabel.
type: docs
weight: 14
url: /id/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) metode

Membuat salinan baris templat yang ditentukan dan menyisipkannya di bagian bawah tabel.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) yang digunakan sebagai templat. |
| withAttachedColumns | **bool** | True untuk menyalin juga semua kolom yang terlampir pada baris templat. |

### Nilai Kembalian

Kolom yang ditambahkan.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IColumn](../../icolumn/)
* Kelas [IColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)