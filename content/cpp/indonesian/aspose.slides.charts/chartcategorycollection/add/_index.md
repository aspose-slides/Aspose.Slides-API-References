---
title: Add()
second_title: Aspose.Slides untuk Referensi API C++
description: Jika kategori ada dalam koleksi, kembalikan. Jika tidak, buat kategori diagram baru dari IChartDataCell dan tambahkan ke koleksi.
type: docs
weight: 92
url: /id/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) metode

Jika kategori sudah ada dalam koleksi, kembalikan. Jika tidak, buat kategori diagram baru dari [IChartDataCell](../../ichartdatacell/) dan tambahkan ke koleksi.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) yang digunakan untuk membuat kategori diagram. |

### Nilai Kembalian

Kategori yang ditambahkan atau yang sudah ada.



## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) metode

Membuat [ChartCategory](../../chartcategory/) baru dari nilai dan menambahkannya ke koleksi.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Nilainya. |

### Nilai Kembalian

[IChartCategory](../../ichartcategory/) yang ditambahkan.

## Catatan

Metode ini menambahkan lembar kerja dengan nama AUTO_DATA dan menambahkan semua nilai di sana. Jika Anda menggunakan [ChartDataWorkbook](../../chartdataworkbook/) untuk menambah atau mengedit nilai sel, pastikan Anda tidak menggunakan lembar kerja ini. Jumlah maksimum nilai yang ditambahkan menggunakan metode ini tidak boleh melebihi 16711680

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChartCategory](../../ichartcategory/)
* Kelas [IChartDataCell](../../ichartdatacell/)
* Kelas [ChartCategoryCollection](../)
* Kelas [Object](../../../system/object/)
* Ruang nama [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)