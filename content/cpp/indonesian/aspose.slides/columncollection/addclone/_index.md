---
title: AddClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat salinan baris templat yang ditentukan dan menyisipkannya di bagian bawah tabel.
type: docs
weight: 53
url: /id/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) metode

Membuat salinan baris templat yang ditentukan dan menyisipkannya di bagian bawah tabel.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) yang digunakan sebagai templat. |
| withAttachedColumns | **bool** | True untuk menyalin juga semua kolom yang terlampir pada baris templat. |

### Nilai Kembali

Kolom yang ditambahkan.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IColumn](../../icolumn/)
* Kelas [ColumnCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)