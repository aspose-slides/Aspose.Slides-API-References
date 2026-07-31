---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Tambahkan sel baru ke koleksi.
type: docs
weight: 53
url: /id/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) method


Tambahkan sel baru ke koleksi.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Sel baru untuk ditambahkan. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) method


Membuat [ChartDataCell](../../chartdatacell/) dari nilai yang ditentukan dan menambahkannya ke koleksi.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Nilainya. |
## Catatan



Metode ini menambahkan lembar kerja dengan nama AUTO_DATA dan menambahkan semua nilai di sana. Jika Anda menggunakan [ChartDataWorkbook](../../chartdataworkbook/) untuk menambah atau mengedit nilai [Cell](../../../aspose.slides/cell/), pastikan Anda tidak menggunakan lembar kerja ini. Jumlah maksimum nilai yang ditambahkan menggunakan metode ini tidak boleh melebihi 16711680



## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IChartDataCell](../../ichartdatacell/)
* Kelas [ChartCellCollection](../)
* Kelas [Object](../../../system/object/)
* Ruang nama [Aspose::Slides::Charts](../../)
* Pustaka [Aspose.Slides](../../../)