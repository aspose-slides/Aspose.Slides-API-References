---
title: AddClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat salinan baris templat yang ditentukan dan menyisipkannya di bagian bawah tabel.
type: docs
weight: 14
url: /id/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) metode


Membuat salinan baris templat yang ditentukan dan menyisipkannya di bagian bawah tabel.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) yang digunakan sebagai templat. |
| withAttachedRows | **bool** | True untuk menyalin juga semua baris yang terlampir pada baris templat. |

### Nilai Kembali

Baris yang ditambahkan.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IRow](../../irow/)
* Kelas [IRowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)