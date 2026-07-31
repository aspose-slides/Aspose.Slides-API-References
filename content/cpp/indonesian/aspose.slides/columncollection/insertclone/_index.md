---
title: InsertClone()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat salinan kolom templat yang ditentukan dan menyisipkannya pada posisi yang ditentukan dalam tabel.
type: docs
weight: 66
url: /id/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) metode

Membuat salinan kolom templat yang ditentukan dan menyisipkannya pada posisi yang ditentukan dalam tabel.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks kolom baru. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) yang digunakan sebagai templat. |
| withAttachedColumns | **bool** | True to copy also all columns attached to the template column. |

### Nilai Kembali

Kolom yang disisipkan.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IColumn](../../icolumn/)
* Kelas [ColumnCollection](../)
* Ruang nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)