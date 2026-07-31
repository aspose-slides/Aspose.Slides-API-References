---
title: InsertClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat salinan kolom templat yang ditentukan dan menyisipkannya pada posisi yang ditentukan dalam tabel.
type: docs
weight: 27
url: /id/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) metode

Membuat salinan kolom templat yang ditentukan dan menyisipkannya pada posisi yang ditentukan dalam tabel.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks kolom baru. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) yang digunakan sebagai templat. |
| withAttachedColumns | **bool** | True untuk menyalin juga semua kolom yang terlampir pada kolom templat. |

### Nilai Kembali

Kolom yang disisipkan.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumn](../../icolumn/)
* Class [IColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)