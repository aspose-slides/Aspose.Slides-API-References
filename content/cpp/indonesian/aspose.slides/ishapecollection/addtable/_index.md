---
title: AddTable()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat tabel baru dan menambahkannya ke akhir koleksi shape.
type: docs
weight: 430
url: /id/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method


Membuat tabel baru dan menambahkannya ke akhir koleksi shape.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari tabel, dalam poin. |
| y | **float** | Koordinat y dari tabel, dalam poin. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Array berisi double yang mewakili lebar kolom tabel, dalam poin. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Array berisi double yang mewakili tinggi baris tabel, dalam poin. |

### Nilai Kembali

[ITable](../../itable/) yang baru dibuat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [ITable](../../itable/)
* Kelas [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)