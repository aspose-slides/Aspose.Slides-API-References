---
title: InsertTable()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat tabel baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.
type: docs
weight: 482
url: /id/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) metode

Membuat tabel baru dan menyisipkannya ke dalam koleksi shape pada indeks yang ditentukan.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol tempat menyisipkan tabel. |
| x | **float** | Koordinat x tabel, dalam poin. |
| y | **float** | Koordinat y tabel, dalam poin. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Array double yang mewakili lebar kolom tabel, dalam poin. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Array double yang mewakili tinggi baris tabel, dalam poin. |

### Nilai Kembalian

[ITable](../../itable/) yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [ITable](../../itable/)
* Kelas [ShapeCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)