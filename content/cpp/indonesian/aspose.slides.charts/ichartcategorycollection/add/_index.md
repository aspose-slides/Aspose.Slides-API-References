---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Jika kategori ada dalam koleksi, kembalikan. Jika tidak, buat kategori bagan baru dari IChartDataCell dan tambahkan ke koleksi.
type: docs
weight: 53
url: /id/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) method

Jika kategori sudah ada dalam koleksi, kembalikan. Jika tidak, buat kategori bagan baru dari [IChartDataCell](../../ichartdatacell/) dan tambahkan ke koleksi.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### Argument

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) digunakan untuk membuat kategori bagan. |

### Nilai Kembali

Kategori yang ditambahkan atau yang sudah ada.

## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) method

Membuat [IChartCategory](../../ichartcategory/) baru dari nilai dan menambahkannya ke koleksi.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```

### Argument

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Nilainya. |

### Nilai Kembali

Menambahkan [IChartCategory](../../ichartcategory/).

## Catatan

Metode ini menambahkan lembar kerja dengan nama AUTO_DATA dan menambahkan semua nilai di sana. Jika Anda menggunakan [IChartDataWorkbook](../../ichartdataworkbook/) untuk menambah atau mengedit nilai sel, pastikan Anda tidak menggunakan lembar kerja ini. Jumlah maksimum nilai yang ditambahkan menggunakan metode ini tidak boleh melebihi 16711680

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartCategory](../../ichartcategory/)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCategoryCollection](../)
* Class [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)